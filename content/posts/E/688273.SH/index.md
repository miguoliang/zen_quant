---
title: "麦澜德 - 688273.SH"
date: 2022-08-23T22:03:38+08:00
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
        const D_v = [160695.61,100454.64,86806.52,66856.63,65394.97,33966.59,43867.54,22303.67,20993.35]
const D_histogram = [0.0,-0.0395669516,-0.3327892988,-0.4453126842,-0.5889117049,-0.6844061342,-0.7999813825,-0.827087145,-0.8184102791]
const D_fast = [0.0,-0.0494586895,-0.4258783614,-0.6497299179,-0.9405568648,-1.2071528276,-1.5227234215,-1.7566009703,-1.9525266741]
const D_slow = [0.0,-0.0098917379,-0.0930890626,-0.2044172336,-0.3516451599,-0.5227466934,-0.722742039,-0.9295138253,-1.1341163951]
const D_data = [['2022-08-11', 42.44, 44.07, 42.35, 50.58],['2022-08-12', 42.86, 43.45, 42.06, 46.5],['2022-08-15', 42.99, 39.21, 38.18, 43.0],['2022-08-16', 39.01, 40.04, 38.18, 40.58],['2022-08-17', 40.5, 38.5, 38.18, 41.45],['2022-08-18', 37.5, 37.88, 37.35, 38.4],['2022-08-19', 37.9, 36.37, 35.99, 38.23],['2022-08-22', 36.29, 36.32, 35.75, 36.77],['2022-08-23', 36.19, 35.91, 35.53, 36.4]]
const W_v = [261150.25,296892.25,43297.02]
const W_histogram = [0.0,-0.4518290598,-0.7396674508]
const W_fast = [0.0,-0.5647863248,-1.0375415784]
const W_slow = [0.0,-0.112957265,-0.2978741276]
const W_data = [['2022-08-12', 42.44, 43.45, 42.06, 50.58],['2022-08-19', 42.99, 36.37, 35.99, 43.0],['2022-08-26', 36.29, 35.91, 35.53, 36.77]]
const M_v = [601339.52]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 42.44, 35.91, 35.53, 50.58]]
        const D_a = [null,null,null,null,null,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}