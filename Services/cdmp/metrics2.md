### Release 1A Burn up
<div id="chart"></div>
<script>
var chart = c3.generate

({

data: {
x: 'x',
columns: [
['x', 1, 2, 3, 4, 5, 6,7],
['done', 15.3, 12.5, 0, 0, 0, 0, 0],
['to do', 42.8, 52.5, 0, 0, 0, 0, 0],
['required', 7, 19, 28, 37, 46, 56, 65],
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
},

legend: {
position: 'right'
},

names: 
{
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
data12: 'line' },
    
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

groups: 
[['data1', 'data2', 'data3', 'data4', 'data5', 'data6', 'data7', 'data8', 'data9','data10','data11','data12']]
},

bindto: '#chart1'

});
</script>
