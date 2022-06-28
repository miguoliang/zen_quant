---
title: "C龙芯 - 688047.SH"
date: 2022-06-28T17:06:59+08:00
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
        const D_v = [242084.44,168538.85,136532.85]
const D_histogram = [0.0,0.7434757835,1.3481308756]
const D_fast = [0.0,0.9293447293,1.8710325403]
const D_slow = [0.0,0.1858689459,0.5229016648]
const D_data = [['2022-06-24', 96.28, 89.07, 82.4, 99.67],['2022-06-27', 90.5, 100.72, 88.8, 105.88],['2022-06-28', 101.08, 103.53, 97.74, 106.63]]
const W_v = [242084.44,305071.7]
const W_histogram = [0.0,0.9228034188]
const W_fast = [0.0,1.1535042735]
const W_slow = [0.0,0.2307008547]
const W_data = [['2022-06-24', 96.28, 89.07, 82.4, 99.67],['2022-07-01', 90.5, 103.53, 88.8, 106.63]]
const M_v = [547156.14]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-06-30', 96.28, 103.53, 82.4, 106.63]]
        const D_a = [null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}