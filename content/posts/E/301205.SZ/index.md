---
title: "C联特 - 301205.SZ"
date: 2022-09-16T20:28:38+08:00
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
        const D_v = [92116.01,68180.7,59155.52,44840.05]
const D_histogram = [0.0,0.0912592593,0.0515693996,-0.1818292016]
const D_fast = [0.0,0.1140740741,0.0872765643,-0.1915793372]
const D_slow = [0.0,0.0228148148,0.0357071647,-0.0097501357]
const D_data = [['2022-09-13', 54.99, 49.51, 49.46, 58.0],['2022-09-14', 45.96, 50.94, 45.8, 52.7],['2022-09-15', 50.0, 49.5, 48.18, 52.33],['2022-09-16', 48.0, 46.28, 46.23, 49.46]]
const W_v = [264292.28]
const W_histogram = [0.0]
const W_fast = [0.0]
const W_slow = [0.0]
const W_data = [['2022-09-16', 54.99, 46.28, 45.8, 58.0]]
const M_v = [264292.28]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-09-30', 54.99, 46.28, 45.8, 58.0]]
        const D_a = [null,null,null,null]
const W_a = [null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}