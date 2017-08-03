<div id="chart"></div>
<script>
var chart2 = c3.generate({
data: {
columns: [
['done', 30, 20, 50, 40, 60, 50],
['to do', 200, 130, 90, 240, 130, 220],
['required', 300, 200, 160, 400, 250, 250],
],
type: 'bar',
types: {
data3: 'line',
},
groups: [
['data1','data2']
]
}
});
</script>
