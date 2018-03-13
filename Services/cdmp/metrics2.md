## Common Data Matching Platform
### Metrics

| Release |Completed  | Due | Predicted |
|:-----| :-----:|:-----:|:-----:|
|Release 1.1  | 68% |31 Mar 2018 | 14 Apr 2018 |

### Release 1.1 Burn up
<div id="chart1"></div>
<script>
var chart = c3.generate({

axis: {
x: {
label: 'Sprint'
},
y: {
label: 'Work'
}
},

data: {
x: 'x',
columns: [
['x', 1, 2, 3, 4, 5, 6],
['done', 27, 29, 39, 43, 57, 0],
['to do', 35, 51, 41, 42, 27, 0],
['required', 10, 21, 31, 41, 52, 62],
],

type: 'bar',
types: {
required: 'line',
},

groups: [ 
['to do','done'] ] 
},

legend: {
position: 'right'
},

bindto: '#chart1'

});
</script>

[Click here for sprint notes](notes.html)
