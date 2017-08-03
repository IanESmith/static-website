<div id="chart"></div>

<script>
var chart1 = c3.generate({
data: {
columns: [
['data1', 30, 200, 100, 400, 150, 250],
['data2', 50, 20, 10, 40, 15, 25]
],
axes: {
data1: 'y',
data2: 'y2',
}
},
axis: {
x: {
label: 'X Label'
},
y: {
label: {
text: 'Y Axis Label',
position: 'outer-middle'
}
},
y2: {
show: true,
label: {
text: 'Y2 Axis Label',
position: 'outer-middle'
}
}
},
tooltip: {
//          enabled: false
},
zoom: {
//          enabled: true
},
subchart: {
//          show: true
}
});

setTimeout(function () {
chart.axis.labels({
x: 'New X Axis Label',
y: 'New Y Axis Label',
y2: 'New Y2 Axis Label',
});
}, 1000);

setTimeout(function () {
chart.load({
columns: [
['data1', 100, 300, 600, 200, 400, 500]
]
});
chart.axis.labels({y: 'New Y Axis Label Again'});
}, 2000);
</script>

<div id="chart"></div>
<script>
var chart2 = c3.generate({
data: {
columns: [
['data1', 30, 20, 50, 40, 60, 50],
['data2', 200, 130, 90, 240, 130, 220],
['data3', 300, 200, 160, 400, 250, 250],
['data4', 200, 130, 90, 240, 130, 220],
['data5', 130, 120, 150, 140, 160, 150],
['data6', 90, 70, 20, 50, 60, 120],
],
type: 'bar',
types: {
data3: 'spline',
data4: 'line',
data6: 'area',
},
groups: [
['data1','data2']
]
}
});
</script>
