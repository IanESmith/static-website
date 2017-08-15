<div id="chart"></div>
<script>
var _vertChart = c3.generate({
    bindto: '#chart',
    data: {
        x: 'x',
            columns: [
                [['x','7am','8am','9am','10am','11am','12pm','1pm','2pm','3pm','4pm','5pm','6pm','7pm','8pm','9pm','10pm'],], 
                ['My Numbers',0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],
                ['Johns Numbers',0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0]
            ],
            type: 'bar'
        },
        bar: {
            width: {
                ratio: 0.8 // this makes bar width 50% of length between ticks
            }
            // or
            //width: 100 // this makes bar width 100px
        },
        axis: {x: {type: 'category', show: true}},
        labels: true,
        tooltip: {
            show: true
        },
        color: {
            pattern: ["#5F3A81","#56AEC7", "#F09348", "#A196A9"]
        },
        grid: {
            x: {
                show: true
            },
            y: {
                show: false,
                lines: []
            }
        }
});
</script>
