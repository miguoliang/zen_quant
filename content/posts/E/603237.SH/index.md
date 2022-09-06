---
title: "五芳斋 - 603237.SH"
date: 2022-09-06T20:48:49+08:00
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
        const D_v = [13176.53,4242.54,3764.4,170011.38,114623.63]
const D_histogram = [0.0,0.3152592593,0.8427807956,0.9345105372,0.5898025851]
const D_fast = [0.0,0.3940740741,1.1322908093,1.4576481853,1.2603908794]
const D_slow = [0.0,0.0788148148,0.2895100137,0.523137648,0.6705882943]
const D_data = [['2022-08-31', 41.18, 49.42, 41.18, 49.42],['2022-09-01', 54.36, 54.36, 54.36, 54.36],['2022-09-02', 59.8, 59.8, 59.8, 59.8],['2022-09-05', 59.8, 56.79, 54.5, 63.0],['2022-09-06', 54.0, 51.33, 51.3, 55.0]]
const W_v = [21183.47,284635.01]
const W_histogram = [0.0,-0.5405356125]
const W_fast = [0.0,-0.6756695157]
const W_slow = [0.0,-0.1351339031]
const W_data = [['2022-09-02', 41.18, 59.8, 41.18, 59.8],['2022-09-09', 59.8, 51.33, 51.3, 63.0]]
const M_v = [13176.53,292641.95]
const M_histogram = [0.0,0.1218917379]
const M_fast = [0.0,0.1523646724]
const M_slow = [0.0,0.0304729345]
const M_data = [['2022-08-31', 41.18, 49.42, 41.18, 49.42],['2022-09-30', 54.36, 51.33, 51.3, 63.0]]
        const D_a = [null,null,null,63.0,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}