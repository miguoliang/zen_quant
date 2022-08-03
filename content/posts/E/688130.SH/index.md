---
title: "C晶华微 - 688130.SH"
date: 2022-08-03T20:39:09+08:00
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
        const D_v = [77967.15,60796.33,41503.19,75890.13]
const D_histogram = [0.0,0.1282735043,0.0491319648,0.3418012207]
const D_fast = [0.0,0.1603418803,0.0934833321,0.4716028931]
const D_slow = [0.0,0.0320683761,0.0443513673,0.1298016724]
const D_data = [['2022-07-29', 57.5, 58.15, 56.49, 62.78],['2022-08-01', 57.08, 60.16, 54.56, 60.85],['2022-08-02', 58.55, 57.77, 56.63, 60.4],['2022-08-03', 59.02, 63.18, 59.02, 67.77]]
const W_v = [77967.15,178189.65]
const W_histogram = [0.0,0.321002849]
const W_fast = [0.0,0.4012535613]
const W_slow = [0.0,0.0802507123]
const W_data = [['2022-07-29', 57.5, 58.15, 56.49, 62.78],['2022-08-05', 57.08, 63.18, 54.56, 67.77]]
const M_v = [77967.15,178189.65]
const M_histogram = [0.0,0.321002849]
const M_fast = [0.0,0.4012535613]
const M_slow = [0.0,0.0802507123]
const M_data = [['2022-07-29', 57.5, 58.15, 56.49, 62.78],['2022-08-31', 57.08, 63.18, 54.56, 67.77]]
        const D_a = [null,54.56,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}