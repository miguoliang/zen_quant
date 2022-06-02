---
title: "思特威-W - 688213.SH"
date: 2022-06-02T17:25:58+08:00
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
        const D_v = [236289.13,145094.17,103765.78,73821.75,77929.13,73508.23,57052.83,82156.22,64492.14,84763.93]
const D_histogram = [0.0,-0.1627350427,-0.6170404461,-0.9984929365,-1.3879535152,-1.6465347263,-1.6283621398,-1.3407931157,-0.9857352577,-0.5096544165]
const D_fast = [0.0,-0.2034188034,-0.8119843183,-1.4430600429,-2.1795090004,-2.849723893,-3.2386418414,-3.2862710963,-3.1776470527,-2.8289798157]
const D_slow = [0.0,-0.0406837607,-0.1949438722,-0.4445671063,-0.7915554851,-1.2031891667,-1.6102797017,-1.9454779806,-2.191911795,-2.3193253991]
const D_data = [['2022-05-20', 51.01, 56.66, 47.71, 56.66],['2022-05-23', 56.5, 54.11, 53.88, 59.75],['2022-05-24', 54.0, 48.45, 48.45, 54.53],['2022-05-25', 48.07, 46.4, 45.25, 48.8],['2022-05-26', 46.0, 43.16, 42.85, 46.2],['2022-05-27', 43.65, 41.68, 40.6, 43.78],['2022-05-30', 42.4, 42.98, 42.34, 44.08],['2022-05-31', 43.0, 45.74, 41.0, 47.77],['2022-06-01', 45.4, 47.1, 44.55, 47.47],['2022-06-02', 46.34, 49.95, 45.8, 52.21]]
const W_v = [236289.13,474119.06,288465.12]
const W_histogram = [0.0,-0.955988604,-0.9751182669]
const W_fast = [0.0,-1.194985755,-1.4578949846]
const W_slow = [0.0,-0.238997151,-0.4827767177]
const W_data = [['2022-05-20', 51.01, 56.66, 47.71, 56.66],['2022-05-27', 56.5, 41.68, 40.6, 59.75],['2022-06-02', 42.4, 49.95, 41.0, 52.21]]
const M_v = [849617.24,149256.07]
const M_histogram = [0.0,0.2686723647]
const M_fast = [0.0,0.3358404558]
const M_slow = [0.0,0.0671680912]
const M_data = [['2022-05-31', 51.01, 45.74, 40.6, 59.75],['2022-06-30', 45.4, 49.95, 44.55, 52.21]]
        const D_a = [null,59.75,null,null,null,40.6,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}