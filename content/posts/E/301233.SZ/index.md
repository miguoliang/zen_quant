---
title: "C盛帮 - 301233.SZ"
date: 2022-07-13T20:26:17+08:00
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
        const D_v = [78034.61,58476.49,39212.94,26849.2,34453.78,35786.63]
const D_histogram = [0.0,-0.5124558405,-0.9300659053,-1.199761017,-1.2041584405,-1.312436973]
const D_fast = [0.0,-0.6405698006,-1.2906963418,-1.8603317077,-2.1657687414,-2.6021565171]
const D_slow = [0.0,-0.1281139601,-0.3606304364,-0.6605706907,-0.9616103008,-1.2897195441]
const D_data = [['2022-07-06', 59.79, 57.13, 57.08, 59.79],['2022-07-07', 55.0, 49.1, 48.9, 55.0],['2022-07-08', 47.15, 47.15, 46.91, 49.72],['2022-07-11', 46.05, 46.21, 45.5, 47.5],['2022-07-12', 46.2, 47.71, 46.01, 48.73],['2022-07-13', 46.87, 44.93, 44.83, 47.38]]
const W_v = [175724.04,97089.61]
const W_histogram = [0.0,-0.1416752137]
const W_fast = [0.0,-0.1770940171]
const W_slow = [0.0,-0.0354188034]
const W_data = [['2022-07-08', 59.79, 47.15, 46.91, 59.79],['2022-07-15', 46.05, 44.93, 44.83, 48.73]]
const M_v = [272813.65]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 59.79, 44.93, 44.83, 59.79]]
        const D_a = [null,null,null,45.5,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}