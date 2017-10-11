## Common Data Matching Platform
### Metrics

| Release |Completed  | Due | Predicted |
|:-----| :-----:|:-----:|:-----:|
|Release Candidate 1A  | 69% |25-Oct-17 | 16-Nov-17 |

| Epic |Completed  | 
|:-----| :-----:|
| [Infrastructure](https://jira.digital.homeoffice.gov.uk/browse/CDMP-83) | 100% | 
| [Services](https://jira.digital.homeoffice.gov.uk/browse/CDMP-85)|  100% | 
| [Security](https://jira.digital.homeoffice.gov.uk/browse/CDMP-86) | 100% |  
| [Monitoring](https://jira.digital.homeoffice.gov.uk/browse/CDMP-87) |  25% |
| [Create Roadmap for HMPO](https://jira.digital.homeoffice.gov.uk/browse/CDMP-80)|  50% |


### Release 1A Burn up
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
['x', 1, 2, 3, 4, 5, 6,7],
['done', 15.3, 15, 16, 20.75, 27.5, 31.25, 0],
['to do', 42.8, 40, 29, 24.25, 17.5, 13.75, 0],
['required', 7, 16, 21, 27, 34, 40, 47],
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



### Team Health
<div id="chart2"></div>
<script>
var chart = c3.generate({

axis: {
x: {
type: 'timeseries',
tick: {
format: '%m-%Y'
}
}
},

data: {
x: 'x',
columns: [
['x', '2017-07-07', '2017-08-07', '2017-09-12'],
['data1', 2.8, 3.3,4.0],
['data2', 2.8, 4.0,3.7],
['data3', 3.2, 3.5,3.7],
['data4', 3.2, 3.8,4.0],
['data5', 3.0, 4.5,4.0],
['data6', 3.0, 3.8,4.0],
['data7', 3.4, 2.8,3.0],
['data8', 3.4, 3.5,4.3],
['data9', 2.6, 3.5,3.3],
['data10', 4.0, 4.0,4.0],
['data11', 3.2, 3.8,4.0],
['data12', 3.6, 3.0,4.0]
],

names: {
data1: 'I am not happy with my working environment',
data2: 'I dont know whats going on',
data3: 'I dont feel I can raise anything with the whole team',
data4: 'I dont feel my voice is being heard',
data5: 'I dont feel my work contributes to the goal',
data6: 'I dont feel supported by my team',
data7: 'I dont get enough time to tackle technical debt',
data8: 'I dont get time to improve my skills/knowledge',
data9: 'I dont know what work is next',
data10:'I dont understand the work that I am doing',
data11:'I feel like I am working on my own',
data12:'I feel like work is being pushed on me'
},

types: {
data1: 'area-spline',
data2: 'area-spline',
data3: 'area-spline',
data4: 'area-spline',
data5: 'area-spline',
data6: 'area-spline',
data7: 'area-spline',
data8: 'area-spline',
data9: 'area-spline',
data10: 'area-spline',
data11: 'area-spline',
data12: 'area-spline'
},

groups: 
[['data1', 'data2', 'data3', 'data4', 'data5', 'data6', 'data7', 'data8', 'data9','data10','data11','data12']]
},

legend: {
position: 'right'
},

bindto: '#chart2'

});
</script>
Every month the team anonomously score how they feeling, from 1 to 5. The lower the number, the worse the team 'health' (which has a negative impact on quality). The results are averaged on this chart. 


[Click here for sprint notes](notes.html)
