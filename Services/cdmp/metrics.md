## Common Data Matching Platform
### Metrics

| Release |Completed  | Due | Predicted |
|:-----| :-----:|:-----:|:-----:|
|Release Candidate 1A  | 27% |25-Oct-17 | 20-Nov-17 |

| Epic |Completed  | 
|:-----| :-----:|
| [Infrastructure](https://jira.digital.homeoffice.gov.uk/browse/CDMP-83) | 75% | 
| [Services](https://jira.digital.homeoffice.gov.uk/browse/CDMP-85)|  75% | 
| [Security](https://jira.digital.homeoffice.gov.uk/browse/CDMP-86) | 0% |  
| [Monitoring](https://jira.digital.homeoffice.gov.uk/browse/CDMP-87) |  0% |
| [Create Roadmap for HMPO](https://jira.digital.homeoffice.gov.uk/browse/CDMP-80)|   0% |

| Release|Completed  | Due | Predicted |
|:-----| :-----:|:-----:|:-----:|
|Release Candidate 1B  | 5% | March 2018 | March 2018 |

| Epic |Completed  | 
|:-----| :-----:|
| [Infrastructure](https://jira.digital.homeoffice.gov.uk/browse/CDMP-83)  | 0% | 
| [Platform Accreditation](https://jira.digital.homeoffice.gov.uk/browse/CDMP-88) | 5% | 
| [Live Support](https://jira.digital.homeoffice.gov.uk/browse/CDMP-19)  | 25% | 


### Release 1A Burn up
<div id="chart"></div>
<script>
var chart = c3.generate({

data: {
x: 'x',
columns: [
['x', 1, 2, 3, 4, 5, 6,7],
['done', 15.3, 15, 0, 0, 0, 0, 0],
['to do', 42.8, 40, 0, 0, 0, 0, 0],
['required', 7, 16, 24, 32, 39, 47, 55],
],

type: 'bar',
types: {
required: 'line',
},


groups: [ 
['to do','done'] ] 
},

bindto: '#chart'

});
</script>
