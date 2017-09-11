### Release 1A Burn up
<div id="chart"></div>
<script>
var chart = c3.generate({

axis: {
x: {
label: 'Your X Axis'
}
},

data: {
x: 'x',
columns: [
['x', 1, 2, 3, 4, 5, 6,7],
['done', 15.3, 15, 16, 0, 0, 0, 0],
['to do', 42.8, 40, 29, 0, 0, 0, 0],
['required', 7, 16, 21, 27, 33, 40, 47],
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
['data5', 3.0, 4.5],
['data6', 3.0, 3.8],
['data7', 3.4, 2.8],
['data8', 3.4, 3.5],
['data9', 2.6, 3.5],
['data10', 4.0, 4.0],
['data11', 3.2, 3.8],
['data12', 3.6, 3.0]
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

bindto: '#chart1'

});
</script>
Every month the team anonomously score how they feeling. The results are averaged and displayed here. The lower the number, the worse the team 'health'.
