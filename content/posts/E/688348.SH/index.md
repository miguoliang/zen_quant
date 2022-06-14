---
title: "N昱能 - 688348.SH"
date: 2022-06-14T17:55:10+08:00
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
        const D_v = [135800.51,58851.55,43211.28,35770.01,39461.86]
const D_histogram = [0.0,0.3829059829,3.4022778387,6.1301403713,8.8361315822]
const D_fast = [0.0,0.4786324786,4.348573794,8.6089714196,13.523995526]
const D_slow = [0.0,0.0957264957,0.9462959554,2.4788310482,4.6878639438]
const D_data = [['2022-06-08', 301.0, 290.1, 266.0, 311.0],['2022-06-09', 292.0, 296.1, 290.3, 311.0],['2022-06-10', 299.8, 339.98, 299.76, 341.69],['2022-06-13', 336.5, 356.0, 329.0, 363.9],['2022-06-14', 350.97, 377.0, 339.5, 385.98]]
const W_v = [237863.34,75231.87]
const W_histogram = [0.0,2.3625299145]
const W_fast = [0.0,2.9531623932]
const W_slow = [0.0,0.5906324786]
const W_data = [['2022-06-10', 301.0, 339.98, 266.0, 341.69],['2022-06-17', 336.5, 377.0, 329.0, 385.98]]
const M_v = [313095.21]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-06-30', 301.0, 377.0, 266.0, 385.98]]
        const D_a = [null,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}