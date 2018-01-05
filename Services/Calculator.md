<script src="https://cdnjs.cloudflare.com/ajax/libs/numeral.js/2.0.6/numeral.min.js"></script>
<script src="http://cdn.bossanova.uk/js/excel-formula.min.js"></script>

<script src="https://bossanova.uk/components/jexcel/dist/js/jquery.jexcel.js"></script>
<link rel="stylesheet" href="https://bossanova.uk/components/jexcel/dist/css/jquery.jexcel.css" type="text/css" />
<div id="script1"></div>
<script>
var data = [
['Furnace',1,10000,'=B1*C1'],
['Tower',2,6000,'=B2*C2'],
['Drum',3,5000,'=B3*C3'],
['Pump',4,4000,'=B4*C4'],
['Total','=SUM(B1:B4)','=(C1+C2+C3+C4)','=SUM(D1:D4)']
]

$('#my').jexcel({
data:data,
columns: [
{ type:'text' },
{ type:'numeric' },
{ type:'numeric' },
{ type:'numeric' },
],
colHeaders: ['Equipment','Quantity', 'Price', 'Total'],
colWidths: [ 400, 100, 200 ],
colWidths: [300, 150, 150, 150, 150],
});

$('#my').jexcel('updateSettings', {
cells: function (cell, col, row) {
if (col > 0) {
value = $('#my').jexcel('getValue', $(cell));
val = numeral($(cell).text()).format('0,0.00');
$(cell).html('' + val);
}
}
bindto: '#script1'   
    
});
</script>
