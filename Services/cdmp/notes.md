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
- changed the name of this phase from MVP to Release Candidate 1
- start reporting on progress and added reporting metrics to this page
- added a (part time) security resource
- sized the work and started tracking progress

[Click here for detail](https://jira.digital.homeoffice.gov.uk/secure/Dashboard.jspa)

### About to do/doing

- build the plan for accreditation of the services (ABC/CDP/IBM)
- finalise the live support model

[Click here for detail](https://jira.digital.homeoffice.gov.uk/secure/Dashboard.jspa?selectPageId=13111)

### Things to be aware off

- we're tracking to the October dates to sync with our ABC colleagues. This is a very challenging deadline so we may need to adjust end dates (or reduce scope) in the coming days
- ive provided some links to the Jira instance we use so you can drill down if you need (but cant guarantee that everyone will have Jira access so may remove these links if thats the case)

### Metrics for Release Candidate 1

| Deliverable | Completed  |
|:-------------| :-----:|
| 1A| 30% |
| [Infrastructure](https://jira.digital.homeoffice.gov.uk/browse/CDMP-83) |  |
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
['done', 0.3, 0, 0, 0, 0, 0],
['to do', 51.8, 0, 0, 0, 0, 0],
['required', 9, 17, 26, 35, 43, 52],
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
