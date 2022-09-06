---
title: "联合化学 - 301209.SZ"
date: 2022-09-06T20:29:09+08:00
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
        const D_v = [132362.55,106079.36,73673.77,78629.41,59809.98,67295.74,51780.28,64226.23,102468.22]
const D_histogram = [0.0,-0.4722507123,-0.8777092394,-0.9704359003,-1.152360482,-1.1074424479,-1.0516388366,-0.8185094372,-0.3550412915]
const D_fast = [0.0,-0.5903133903,-1.2151992273,-1.5505348633,-2.0205495655,-2.2524921434,-2.4595982412,-2.4310962012,-2.0563883783]
const D_slow = [0.0,-0.1180626781,-0.3374899879,-0.580098963,-0.8681890835,-1.1450496955,-1.4079594046,-1.6125867639,-1.7013470868]
const D_data = [['2022-08-25', 37.5, 39.0, 36.36, 48.75],['2022-08-26', 32.62, 31.6, 31.53, 35.68],['2022-08-29', 30.1, 29.48, 28.88, 30.55],['2022-08-30', 29.65, 31.24, 28.91, 32.1],['2022-08-31', 30.0, 28.42, 28.26, 30.6],['2022-09-01', 28.53, 29.84, 28.1, 31.12],['2022-09-02', 29.59, 29.2, 28.65, 29.92],['2022-09-05', 29.2, 31.24, 28.95, 31.39],['2022-09-06', 30.88, 35.31, 30.51, 36.54]]
const W_v = [238441.91,331189.1800000001,166694.45]
const W_histogram = [0.0,-0.1531623932,0.1491424258]
const W_fast = [0.0,-0.1914529915,0.1481374339]
const W_slow = [0.0,-0.0382905983,-0.0010049918]
const W_data = [['2022-08-26', 37.5, 31.6, 31.53, 48.75],['2022-09-02', 30.1, 29.2, 28.1, 32.1],['2022-09-09', 29.2, 35.31, 28.95, 36.54]]
const M_v = [450555.0699999999,285770.47]
const M_histogram = [0.0,0.4397037037]
const M_fast = [0.0,0.5496296296]
const M_slow = [0.0,0.1099259259]
const M_data = [['2022-08-31', 37.5, 28.42, 28.26, 48.75],['2022-09-30', 28.53, 35.31, 28.1, 36.54]]
        const D_a = [null,null,null,null,null,28.1,null,null,null]
const W_a = [null,28.1,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}