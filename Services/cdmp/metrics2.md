## Common Data Matching Platform
### Metrics

| Release |Completed  | Due | Predicted |
|:-----| :-----:|:-----:|:-----:|
|June Release  | tbc% | |  |

### June Release Burn up
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
['done', 27, 29, 39, 43, 57, 83],
['to do', 35, 51, 41, 42, 27, 1],
['required', 10, 21, 31, 41, 52, 62],
],


type: 'bar',
types: {
required: 'line',
},

groups: [
['to do', 'done']
],
order: null
},

legend: {
position: 'right'
},

bindto: '#chart1'

});
</script>
[Click here for Blockers] (https://collaboration.homeoffice.gov.uk/display/CDP/Blockers)
[Click here for sprint notes](notes.html)
