---
title: "C昱能 - 688348.SH"
date: 2022-06-15T17:55:20+08:00
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
        const D_v = [135800.51,58851.55,43211.28,35770.01,39461.86,30194.57]
const D_histogram = [0.0,0.3829059829,3.4022778387,6.1301403713,8.8361315822,9.3229808148]
const D_fast = [0.0,0.4786324786,4.348573794,8.6089714196,13.523995526,16.3415899623]
const D_slow = [0.0,0.0957264957,0.9462959554,2.4788310482,4.6878639438,7.0186091475]
const D_data = [['2022-06-08', 301.0, 290.1, 266.0, 311.0],['2022-06-09', 292.0, 296.1, 290.3, 311.0],['2022-06-10', 299.8, 339.98, 299.76, 341.69],['2022-06-13', 336.5, 356.0, 329.0, 363.9],['2022-06-14', 350.97, 377.0, 339.5, 385.98],['2022-06-15', 372.0, 365.98, 354.05, 376.98]]
const W_v = [237863.34,105426.44]
const W_histogram = [0.0,1.6592592593]
const W_fast = [0.0,2.0740740741]
const W_slow = [0.0,0.4148148148]
const W_data = [['2022-06-10', 301.0, 339.98, 266.0, 341.69],['2022-06-17', 336.5, 365.98, 329.0, 385.98]]
const M_v = [343289.78]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-06-30', 301.0, 365.98, 266.0, 385.98]]
        const D_a = [null,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}