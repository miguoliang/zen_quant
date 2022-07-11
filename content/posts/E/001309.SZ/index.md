---
title: "德明利 - 001309.SZ"
date: 2022-07-11T22:43:18+08:00
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
        const D_v = [3863.32,739.51,643.0,1161.36,3002.93,3168.94,122209.61]
const D_histogram = [0.0,0.2437834758,0.6512812591,1.1653493086,1.7466034749,2.3680644397,2.2268933884]
const D_fast = [0.0,0.3047293447,0.8750474428,1.6804528194,2.6983578545,3.9118349291,4.3273872249]
const D_slow = [0.0,0.0609458689,0.2237661837,0.5151035109,0.9517543796,1.5437704895,2.1004938366]
const D_data = [['2022-07-01', 31.85, 38.22, 31.85, 38.22],['2022-07-04', 42.04, 42.04, 42.04, 42.04],['2022-07-05', 46.24, 46.24, 46.24, 46.24],['2022-07-06', 50.86, 50.86, 50.86, 50.86],['2022-07-07', 55.95, 55.95, 55.95, 55.95],['2022-07-08', 61.55, 61.55, 61.55, 61.55],['2022-07-11', 67.69, 55.4, 55.4, 67.69]]
const W_v = [3863.32,8715.74,122209.61]
const W_histogram = [0.0,1.4888660969,1.9481376417]
const W_fast = [0.0,1.8610826211,2.8073885764]
const W_slow = [0.0,0.3722165242,0.8592509347]
const W_data = [['2022-07-01', 31.85, 38.22, 31.85, 38.22],['2022-07-08', 42.04, 61.55, 42.04, 61.55],['2022-07-15', 67.69, 55.4, 55.4, 67.69]]
const M_v = [134788.67]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 31.85, 55.4, 31.85, 67.69]]
        const D_a = [null,null,null,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}