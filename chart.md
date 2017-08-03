<div id="chart"></div>
<script>
var chart2 = c3.generate({
data: {
columns: [
['done', 30, 20, , , , ],
['to do', 200, 130, , , , ],
['required', 9, 17, 26, 34, 43, 41],
],
type: 'bar',
types: {
required: 'line',
},
groups: [
['to do','done']
]
}
});
</script>
