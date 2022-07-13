---
title: "超卓航科 - 688237.SH"
date: 2022-07-13T20:38:52+08:00
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
        const D_v = [143001.2,74178.47,53751.21,48723.31,47502.85,33674.74,31536.7,28775.37,21551.47]
const D_histogram = [0.0,-0.1263589744,-0.3243671853,-0.7782500038,-0.9208575225,-1.2442478608,-1.5820269165,-1.5258822163,-1.3065384574]
const D_fast = [0.0,-0.1579487179,-0.4370487253,-1.0854940446,-1.458315944,-2.0927682475,-2.8260540323,-3.1513798861,-3.2586707416]
const D_slow = [0.0,-0.0315897436,-0.1126815399,-0.3072440409,-0.5374584215,-0.8485203867,-1.2440271158,-1.6254976699,-1.9521322842]
const D_data = [['2022-07-01', 58.96, 69.5, 56.81, 75.4],['2022-07-04', 69.03, 67.52, 64.51, 72.4],['2022-07-05', 65.01, 65.55, 64.2, 68.97],['2022-07-06', 65.5, 60.1, 60.1, 67.17],['2022-07-07', 58.99, 61.64, 58.08, 63.97],['2022-07-08', 62.68, 57.14, 57.14, 63.4],['2022-07-11', 56.5, 53.88, 53.35, 57.74],['2022-07-12', 54.56, 56.6, 54.2, 58.2],['2022-07-13', 57.8, 58.0, 56.24, 59.6]]
const W_v = [143001.2,257830.58,81863.54]
const W_histogram = [0.0,-0.7887863248,-1.1851518348]
const W_fast = [0.0,-0.985982906,-1.6786363747]
const W_slow = [0.0,-0.1971965812,-0.4934845399]
const W_data = [['2022-07-01', 58.96, 69.5, 56.81, 75.4],['2022-07-08', 69.03, 57.14, 57.14, 72.4],['2022-07-15', 56.5, 58.0, 53.35, 59.6]]
const M_v = [482695.3199999999]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 58.96, 58.0, 53.35, 75.4]]
        const D_a = [null,null,null,null,null,null,53.35,null,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}