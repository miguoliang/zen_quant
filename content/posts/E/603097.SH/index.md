---
title: "江苏华辰 - 603097.SH"
date: 2022-05-24T19:38:37+08:00
draft: false
---
{{< rawhtml >}}
    <div style="text-align: center">
        <label style="padding: 1rem;"><input style="margin-right: .5rem" type="radio" name="period" value="D" checked onclick="period_change(this)">日</label>
        <label style="padding: 1rem;"><input style="margin-right: .5rem" type="radio" name="period" value="W" onclick="period_change(this)">周</label>
        <label style="padding: 1rem;"><input style="margin-right: .5rem" type="radio" name="period" value="M" onclick="period_change(this)">月</label>
    </div>
    <div id="chart" style="height: 700px;"></div> 
    <script type="text/javascript">
        const D_v = [10549.47,2606.14,3198.31,7126.37,6187.89,6320.34,20490.56,7341.53,140020.37]
const D_histogram = [0.0,0.0784957265,0.20955539,0.3751476005,0.5624211375,0.7623958764,0.9695980012,1.1810218567,1.3953567216]
const D_fast = [0.0,0.0981196581,0.2815681691,0.5409472797,0.8688261011,1.2593998091,1.7090014343,2.2156807539,2.7788547991]
const D_slow = [0.0,0.0196239316,0.0720127791,0.1657996792,0.3064049636,0.4970039327,0.739403433,1.0346588972,1.3834980776]
const D_data = [['2022-05-12', 10.24, 12.28, 10.24, 12.28],['2022-05-13', 13.51, 13.51, 13.51, 13.51],['2022-05-16', 14.86, 14.86, 14.86, 14.86],['2022-05-17', 16.35, 16.35, 16.35, 16.35],['2022-05-18', 17.99, 17.99, 17.99, 17.99],['2022-05-19', 19.79, 19.79, 19.79, 19.79],['2022-05-20', 21.77, 21.77, 21.77, 21.77],['2022-05-23', 23.95, 23.95, 23.95, 23.95],['2022-05-24', 26.35, 26.35, 26.35, 26.35]]
const W_v = [13155.61,43323.47,147361.9]
const W_histogram = [0.0,0.5271339031,1.1209814466]
const W_fast = [0.0,0.6589173789,1.533010284]
const W_slow = [0.0,0.1317834758,0.4120288374]
const W_data = [['2022-05-13', 10.24, 13.51, 10.24, 13.51],['2022-05-20', 14.86, 21.77, 14.86, 21.77],['2022-05-27', 23.95, 26.35, 23.95, 26.35]]
const M_v = [203840.98]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-05-31', 10.24, 26.35, 10.24, 26.35]]
        const D_a = [null,null,null,null,null,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}