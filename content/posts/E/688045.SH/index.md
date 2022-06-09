---
title: "必易微 - 688045.SH"
date: 2022-06-09T17:06:51+08:00
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
        const D_v = [105308.87,65499.85,36195.11,64138.52,76823.8,70306.49,55948.86,54497.99,45303.24,28058.01]
const D_histogram = [0.0,-0.4275783476,-0.7047342798,-0.4298549186,0.1673887395,0.7499228564,1.0867741667,1.2750280386,1.2520701437,0.846189686]
const D_fast = [0.0,-0.5344729345,-0.9878124366,-0.8203968051,-0.1813059621,0.5887088689,1.1972537209,1.7042646024,1.9943242434,1.7999912073]
const D_slow = [0.0,-0.1068945869,-0.2830781568,-0.3905418865,-0.3486947016,-0.1612139875,0.1104795542,0.4292365638,0.7422540997,0.9538015212]
const D_data = [['2022-05-26', 70.0, 62.6, 60.79, 71.49],['2022-05-27', 61.97, 55.9, 55.9, 62.51],['2022-05-30', 55.0, 55.39, 54.68, 57.16],['2022-05-31', 56.1, 61.8, 55.9, 64.0],['2022-06-01', 61.5, 68.05, 61.18, 68.5],['2022-06-02', 66.9, 71.4, 65.0, 77.99],['2022-06-06', 71.45, 71.55, 68.1, 74.17],['2022-06-07', 73.98, 72.1, 71.47, 79.8],['2022-06-08', 73.0, 71.0, 67.5, 73.2],['2022-06-09', 70.0, 66.0, 65.51, 70.48]]
const W_v = [170808.72,247463.92,183808.1]
const W_histogram = [0.0,0.9891737892,1.2104447204]
const W_fast = [0.0,1.2364672365,1.7603493478]
const W_slow = [0.0,0.2472934473,0.5499046274]
const W_data = [['2022-05-27', 70.0, 55.9, 55.9, 71.49],['2022-06-02', 55.0, 71.4, 54.68, 77.99],['2022-06-10', 71.45, 66.0, 65.51, 79.8]]
const M_v = [271142.35,330938.39]
const M_histogram = [0.0,0.268034188]
const M_fast = [0.0,0.335042735]
const M_slow = [0.0,0.067008547]
const M_data = [['2022-05-31', 70.0, 61.8, 54.68, 71.49],['2022-06-30', 61.5, 66.0, 61.18, 79.8]]
        const D_a = [null,null,54.68,null,null,null,null,79.8,null,null]
const W_a = [null,null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}