## Common Data Matching Platform
### Metrics

| Release |Completed  | Due | Predicted |
|:-----| :-----:|:-----:|:-----:|
|Release 1.1  | 0% |31 Mar 2018 |  |



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
['x', 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11],
['done', 6, 13, 19, 25, 31, 38, 44, 50, 53, 53, 66],
['to do', 73, 67, 60, 54, 48, 42, 35,29 ,26 , 26, 13.2],
['required', 7, 14, 22, 29, 36, 43, 50, 57, 65, 72, 79],
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
['x', '2017-07-07', '2017-08-07', '2017-09-12', '2017-10-12', '2017-11-14', '2017-12-14'],
['data1', 2.8 , 4.0, 4.0 ,4.3 ,4.0 ,3.3],
['data2', 3.2 , 3.8,3.7 ,4.3 ,3.7 ,4.3],
['data3', 3.6,3.0 ,4.0 ,4.8 ,4.3 , 4.3],
['data4', 2.6,3.5 ,4.0 ,4.5 ,3.9 ,3.7],
['data5', 3.3,4.5 ,4.0 ,4.8 ,4.3 , 4.0],
['data6', 2.9,3.3 ,3.0 ,3.0 ,3.3 ,3.0],
['data7', 3.7 , 3.5,4.3 ,3.5 ,3.0 ,4.0],
['data8', 3.4, 2.8,3.3 ,3.5 ,4.0 ,3.3],
['data9', 3.2, 3.5,4.0 ,4.5 ,4.0 , 4.3],
['data10', 3.2,3.8 ,4.0 ,4.0 ,4.5 ,4.3],
['data11', 3.0 ,3.8 ,4.0 ,3.5 ,4.3 ,4.0],
['data12', 4.0 ,4.0 ,4.0 ,5.0 ,4.6 ,4.3]
],

names: {
data1: 'I dont know whats going on',
data2: 'I feel like I am working on my own',
data3: 'I feel like work is being pushed on me',
data4: 'I dont know what work is next',
data5: 'I dont feel my work contributes to the goal',
data6: 'I am not happy with my working environment',
data7: 'I dont get time to improve my skills/knowledge',
data8: 'I dont get enough time to tackle technical debt',
data9: 'I dont feel I can raise anything with the whole team',
data10:'I dont feel my voice is being heard',
data11:'I dont feel supported by my team',
data12:'I dont understand the work that I am doing'
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

Every month the team anonomously scored how they feeling, from 1 to 5. The lower the number, the worse the team 'health' (which has a negative impact on quality). The results are averaged on this chart. Note that this is the last time you'll see this report, from next year we are expanding it to show programme health (so will include more data)


[Click here for sprint notes](notes.html)
