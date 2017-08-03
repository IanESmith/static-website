<div id="chart"></div>
<script>
var chart = c3.generate({
data: {
columns: [
['done', 0, 0, 0, 0, 0, 0],
['to do', 51, 0, 0, 0, 0, 0],
['required', 9, 17, 26, 34, 43, 51],
],
type: 'bar',
types: {
required: 'line',
},
groups: [
['to do','done']
]
}

axis: {
x: {
label: 'X Label'
},
y: {
label: 'Y Label'
},
y2: {
show: true,
label: 'Y2 Label'
}
   

});
</script>
