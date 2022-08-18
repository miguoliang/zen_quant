---
title: "麦澜德 - 688273.SH"
date: 2022-08-18T20:43:58+08:00
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
        const D_v = [160695.61,100454.64,86806.52,66856.63,65394.97,33966.59]
const D_histogram = [0.0,-0.0395669516,-0.3327892988,-0.4453126842,-0.5889117049,-0.6844061342]
const D_fast = [0.0,-0.0494586895,-0.4258783614,-0.6497299179,-0.9405568648,-1.2071528276]
const D_slow = [0.0,-0.0098917379,-0.0930890626,-0.2044172336,-0.3516451599,-0.5227466934]
const D_data = [['2022-08-11', 42.44, 44.07, 42.35, 50.58],['2022-08-12', 42.86, 43.45, 42.06, 46.5],['2022-08-15', 42.99, 39.21, 38.18, 43.0],['2022-08-16', 39.01, 40.04, 38.18, 40.58],['2022-08-17', 40.5, 38.5, 38.18, 41.45],['2022-08-18', 37.5, 37.88, 37.35, 38.4]]
const W_v = [261150.25,253024.71]
const W_histogram = [0.0,-0.3554643875]
const W_fast = [0.0,-0.4443304843]
const W_slow = [0.0,-0.0888660969]
const W_data = [['2022-08-12', 42.44, 43.45, 42.06, 50.58],['2022-08-19', 42.99, 37.88, 37.35, 43.0]]
const M_v = [514174.96]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 42.44, 37.88, 37.35, 50.58]]
        const D_a = [null,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}