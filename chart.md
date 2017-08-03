<div id="chart"></div>
<script>
var chart = c3.generate({
data: {
columns: [
['done', 3, 5, 8, 10, 12, 13],
['to do', 2, 3, 4, 5, 6, 7],
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
