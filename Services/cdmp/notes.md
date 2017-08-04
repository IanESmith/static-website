## Common Data Matching Platform
Release Candidate 1 status as at 8th Aug 201

### What is blocking us
- We've no longer have a tech lead. The team can continue in the short term but this is a blocker

### Just done
- start reporting on progres and added reporting metrics to this page
- added a (part time) security resource

### About to do

- agree the scope of the security assurance for Release Candidate 1
- start reporting on estimated due date
- finalise the live support model


### Things to be aware off

- we'll need to grow the team (including tech lead, user researchers and developers)

### Metrics

| Goal  | Completed  | Due | Predicted|
|:-----| :-----:|:-----:|:-----:|
|A live accredited and supported platform for Advance Border Controls. | 0% |11-Oct-17 | tbc |

------

| Deliverable | Completed  |
|:-------------| :-----:|
| [Accreditation](https://jira.digital.homeoffice.gov.uk/browse/CDMP-88)| 0% |
| [Services](https://jira.digital.homeoffice.gov.uk/browse/CDMP-85)| 0% |
| [Infrastructure](https://jira.digital.homeoffice.gov.uk/browse/CDMP-83) | 0% |
| [Security](https://jira.digital.homeoffice.gov.uk/browse/CDMP-86)| 0% |
| [Monitoring](https://jira.digital.homeoffice.gov.uk/browse/CDMP-87) | 0% |
| [Live Support](https://jira.digital.homeoffice.gov.uk/browse/CDMP-19) | 25% |
| [A plan for our next set of customers](https://jira.digital.homeoffice.gov.uk/browse/CDMP-80)| 0% |

### Burn up

<div id="chart"></div>
<script>

var chart = c3.generate
(
{
data: {
columns: [
['done', 0.3, 0, 0, 0, 0, 0],
['to do', 51.8, 0, 0, 0, 0, 0],
['required', 9, 17, 26, 35, 43, 52],
],

type: 'bar',
types: {
required: 'line',
},
groups: [ 
['to do','done'] ] } 

}
)
;

</script>

