## Common Data Matching Platform

| Status as at 8th Aug 201  | Completed  | Due | Predicted |
|:-----| :-----:|:-----:|:-----:|
|Release Candidate 1A  | 16% |25-Oct-17 | 25-Oct-17 |
|Release Candidate 1B  | 0% |March 2018 | March 2018 |

### Summary
Working with our Advanced Border Control colleagues to provide a platform for their data.  We're doing this in two steps:
- Release 1A (test data through ABC and stored on CDP)
- Release 1B (live data, accredited, supported via Service Now)

We are also starting to onboard HMPO

### What is blocking us
- Our main challenge is now around people. We no longer have a tech lead, the team is very small, and the challenges around folk away on holiday or affected by the Waterloo disruption will reduce our effectiveness. We'll track progress and be able to see the team velocity (and its impact on due dates) in the coming weeks.

### Just done
- updated the due dates in line with ABC plans
- finalised the plan for accreditation of the platform and started the work
- added team health metrics to this page
- with some scope changes, a few of the epics have been added or increased/decreased) in size (reflected in the metrics/burndown)
- created the complete [roadmap for all the ABC and CDP releases](https://jira.digital.homeoffice.gov.uk/secure/Dashboard.jspa?selectPageId=13201)
- met with Neeraj Dad and Gary OReilly to start planning onboarding HMPO

### About to do/doing
- finalise the (light touch) live support model using Service Now
- show and tell our work around security accreditation
- start building a roadmap for onboarding HMPO

### Things to be aware off
- the Delivery Manager is on holiday for the next two weeks
- we've provided some links to the Jira instance we use so you can drill down if you need (but cant guarantee that everyone will have Jira access so may remove these links if thats the case)

### Metrics for Release Candidate 1

| Deliverable | Completed  |
|:-------------| :-----:|
| Release Candidate 1A|  |
| [Infrastructure](https://jira.digital.homeoffice.gov.uk/browse/CDMP-83) | 75% |
| [Services](https://jira.digital.homeoffice.gov.uk/browse/CDMP-85)| 25% |
| [Security](https://jira.digital.homeoffice.gov.uk/browse/CDMP-86) | 0% |
| [Monitoring](https://jira.digital.homeoffice.gov.uk/browse/CDMP-87) | 0% |
| [Create Roadmap for HMPO](https://jira.digital.homeoffice.gov.uk/browse/CDMP-80) | 0% |
| Release Candidate 1B|  |
| [Infrastructure](https://jira.digital.homeoffice.gov.uk/browse/CDMP-83) | 0% |
| [Accreditation](https://jira.digital.homeoffice.gov.uk/browse/CDMP-88)| 0% |
| [Live Support](https://jira.digital.homeoffice.gov.uk/browse/CDMP-19) | 25% |
| [Privacy principles for Global Data Protection Regulation](https://jira.digital.homeoffice.gov.uk/browse/CDMP-19) | 0% |


### Release 1A Burn up

<div id="chart"></div>
<script>
var chart = c3.generate({

data: {
x: 'x',
columns: [
['x', 1, 2, 3, 4, 5, 6,7],
['done', 15.3, 12.5, 0, 0, 0, 0, 0],
['to do', 42.8, 52.5, 0, 0, 0, 0, 0],
['required', 8, 19, 28, 37, 46, 56, 65],
],

type: 'bar',
types: {
required: 'spline',
},


groups: [ 
['to do','done'] ] 
},

bindto: '#chart'

});
</script>
### Team Health
<div id="chart1"></div>
<script>
var chart = c3.generate({
data: {
columns: [
['data1', 2.8, 3.3],
['data2', 2.8, 4.0],
['data3', 3.2, 3.5],
['data4', 3.2, 3.8],
['data5',3.0, 4.5],
['data6', 3.0, 3.8],
['data7', 3.4, 2.8],
['data8', 2.6, 3.5],
['data9', 4.0, 3.5],
['data10', 3.2, 4.0],
['data11', 4.0, 3.8],
['data12', 3.2, 3.0]
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
data9: 'line',
data10: 'line',
data11: 'line',
data12: 'line'

},
groups: [['data1', 'data2', 'data3', 'data4', 'data5', 'data6', 'data7', 'data8', 'data9','data10','data11','data12']]
},

bindto: '#chart1'

});
</script>
