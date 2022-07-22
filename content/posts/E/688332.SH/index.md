---
title: "C中科 - 688332.SH"
date: 2022-07-22T20:46:45+08:00
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
        const D_v = [117835.29,72610.66,49271.93,34778.79,47696.87,40215.76]
const D_histogram = [0.0,-0.1391225071,-0.2078626764,-0.2373457985,-0.2286496714,-0.3070009921]
const D_fast = [0.0,-0.1739031339,-0.2946089723,-0.3834285441,-0.4318948348,-0.5869964035]
const D_slow = [0.0,-0.0347806268,-0.0867462959,-0.1460827455,-0.2032451634,-0.2799954114]
const D_data = [['2022-07-15', 69.96, 64.3, 63.4, 69.96],['2022-07-18', 63.8, 62.12, 60.93, 63.8],['2022-07-19', 62.0, 62.29, 61.52, 63.4],['2022-07-20', 62.73, 62.32, 61.88, 62.95],['2022-07-21', 62.32, 62.53, 62.06, 64.33],['2022-07-22', 62.56, 61.0, 60.75, 62.8]]
const W_v = [117835.29,244574.01]
const W_histogram = [0.0,-0.2105982906]
const W_fast = [0.0,-0.2632478632]
const W_slow = [0.0,-0.0526495726]
const W_data = [['2022-07-15', 69.96, 64.3, 63.4, 69.96],['2022-07-22', 63.8, 61.0, 60.75, 64.33]]
const M_v = [362409.3]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 69.96, 61.0, 60.75, 69.96]]
        const D_a = [null,60.93,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}