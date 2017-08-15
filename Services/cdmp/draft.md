## Common Data Matching Platform

| Status as at 8th Aug 201  | Completed  | Due | Predicted |
|:-----| :-----:|:-----:|:-----:|
|Release Candidate 1  | 16% |25-Oct-17 | 25-Oct-17 |

### What are we doing
Working with our Advanced Border Control colleagues to provide a platform for their data.  We're doing this in two steps:
- Release 1A (test data through ABC and stored on CDP)
- Release 1B	(live data, accredited, supported via Service Now)

### What is blocking us
- Our main challenge is now around people. We no longer have a tech lead, the team is very small, and the challenges around folk away on holiday or affected by the Waterloo disruption will reduce our effectiveness. We'll track progress and be able to see the team velocity (and its impact on due dates) in the coming weeks.

[Click here for all blockers](https://jira.digital.homeoffice.gov.uk/secure/Dashboard.jspa?selectPageId=13109)

### Just done
- finalised the plan for accreditation of the services (ABC/ CDP/IBM)
- finalised the (light touch) live support model using Service Now

[Click here for detail](https://jira.digital.homeoffice.gov.uk/secure/Dashboard.jspa)

### About to do/doing


[Click here for detail](https://jira.digital.homeoffice.gov.uk/secure/Dashboard.jspa?selectPageId=13111)

### Things to be aware off
- the Delivery Manager is on holiday for the next two weeks
- ive provided some links to the Jira instance we use so you can drill down if you need (but cant guarantee that everyone will have Jira access so may remove these links if thats the case)

### Metrics for Release Candidate 1

| Deliverable | Completed  |
|:-------------| :-----:|
| 1A|  |
| [Infrastructure](https://jira.digital.homeoffice.gov.uk/browse/CDMP-83) | 75% |
| [Services](https://jira.digital.homeoffice.gov.uk/browse/CDMP-85)| 25% |
| [Security](https://jira.digital.homeoffice.gov.uk/browse/CDMP-86) | 0% |
| [Monitoring](https://jira.digital.homeoffice.gov.uk/browse/CDMP-87) | 0% |
| 1B|  |
| [Infrastructure](https://jira.digital.homeoffice.gov.uk/browse/CDMP-83) | 0% |
| [Accreditation](https://jira.digital.homeoffice.gov.uk/browse/CDMP-88)| 0% |
| [Live Support](https://jira.digital.homeoffice.gov.uk/browse/CDMP-19) | 25% |
| [Privacy principles for Global Data Protection Regulation](https://jira.digital.homeoffice.gov.uk/browse/CDMP-19) | 0% |


[Click here for detail](https://jira.digital.homeoffice.gov.uk/secure/Dashboard.jspa?selectPageId=13107)

### Burn up

<div id="chart"></div>
<script>
var chart = c3.generate({
data: {
columns: [
['done', 15.3, 0, 0, 0, 0, 0, 0],
['to do', 42.8, 0, 0, 0, 0, 0, 0],
['required', 8, 17, 25, 33, 41, 50, 58],
],


type: 'bar',
types: {
required: 'spline',
},
groups: [ 
['to do','done'] ] 
}


});
</script>
### Team Health
<div id="chart1"></div>
<script>
var chart = c3.generate({
data: {
columns: [
['data1', 2.8, 1.5],
['data2', 3.2, 100],
['data3', 3.6, 100],
['data4', 2.8, 100],
['data5', 2.8, 100],
['data6', 2.8, 100],
['data7', 2.8, 100],
['data8', 2.8, 100],
['data9', 2.8, 100]
],
types: {
data1: 'line',
data2: 'line',
data3: 'line',
data4: 'line',
data5: 'line',
data6: 'line',
data7: 'line',
data8: 'line',
data9: 'line'

},
groups: [['data1', 'data2', 'data3', 'data4', 'data5', 'data6', 'data7', 'data8', 'data9']]
}
});
</script>
