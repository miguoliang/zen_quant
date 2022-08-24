---
title: "C路维 - 688401.SH"
date: 2022-08-23T22:10:46+08:00
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
        const D_v = [233484.08,180146.79,108210.34,80769.21,80885.69]
const D_histogram = [0.0,-0.4269401709,-0.9353891348,-1.394026595,-1.4228045642]
const D_fast = [0.0,-0.5336752137,-1.2759714613,-2.0831155702,-2.4675946804]
const D_slow = [0.0,-0.1067350427,-0.3405823264,-0.6890889752,-1.0447901162]
const D_data = [['2022-08-17', 53.1, 57.49, 46.18, 60.0],['2022-08-18', 51.58, 50.8, 48.82, 52.99],['2022-08-19', 52.0, 46.66, 46.66, 53.47],['2022-08-22', 45.06, 43.65, 43.57, 46.4],['2022-08-23', 44.0, 46.46, 43.61, 47.38]]
const W_v = [521841.21,161654.9]
const W_histogram = [0.0,-0.0127635328]
const W_fast = [0.0,-0.015954416]
const W_slow = [0.0,-0.0031908832]
const W_data = [['2022-08-19', 53.1, 46.66, 46.18, 60.0],['2022-08-26', 45.06, 46.46, 43.57, 47.38]]
const M_v = [683496.1099999999]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 53.1, 46.46, 43.57, 60.0]]
        const D_a = [null,null,null,43.57,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}