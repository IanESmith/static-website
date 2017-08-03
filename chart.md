
| Phase           | Completed  | Due | Predicted|
|:-------------| :-----:|:-----:|:-----:|
| Release Candidate 1A | 0% |11 October 2017 | tbc |

| Deliverable          | Completed  |
|:-------------| :-----:|
| Epic 1 | 0% |
| Epic 2 | 0% |
| Epic 3 | 0% |
| Epic 4 | 0% |

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
required: 'spline',
},
groups: [ 
['to do','done'] ] } });
</script>
