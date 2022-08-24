---
title: "C熵基 - 301330.SZ"
date: 2022-08-23T21:50:18+08:00
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
        const D_v = [200564.96,131907.27,81698.7,68962.12,61288.69]
const D_histogram = [0.0,-0.4231111111,-0.7653581513,-1.0640390158,-1.158424958]
const D_fast = [0.0,-0.5288888889,-1.0624754669,-1.6271660854,-2.011158267]
const D_slow = [0.0,-0.1057777778,-0.2971173156,-0.5631270696,-0.8527333091]
const D_data = [['2022-08-17', 56.33, 54.9, 54.81, 68.0],['2022-08-18', 49.5, 48.27, 47.51, 51.47],['2022-08-19', 47.5, 46.7, 46.61, 48.85],['2022-08-22', 46.17, 44.71, 44.65, 46.41],['2022-08-23', 44.9, 45.21, 44.72, 46.48]]
const W_v = [414170.93,130250.81]
const W_histogram = [0.0,-0.0950883191]
const W_fast = [0.0,-0.1188603989]
const W_slow = [0.0,-0.0237720798]
const W_data = [['2022-08-19', 56.33, 46.7, 46.61, 68.0],['2022-08-26', 46.17, 45.21, 44.65, 46.48]]
const M_v = [544421.74]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 56.33, 45.21, 44.65, 68.0]]
        const D_a = [null,null,null,44.65,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}