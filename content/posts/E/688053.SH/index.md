---
title: "C思科 - 688053.SH"
date: 2022-07-13T20:21:23+08:00
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
        const D_v = [122234.74,73224.8,60591.3,33504.96]
const D_histogram = [0.0,-0.2329344729,-0.0904992654,-0.0257366468]
const D_fast = [0.0,-0.2911680912,-0.1713577,-0.1130292431]
const D_slow = [0.0,-0.0582336182,-0.0808584346,-0.0872925963]
const D_data = [['2022-07-08', 58.0, 53.8, 49.0, 58.0],['2022-07-11', 50.0, 50.15, 48.7, 52.38],['2022-07-12', 50.0, 54.47, 49.98, 55.3],['2022-07-13', 54.4, 54.0, 51.0, 54.66]]
const W_v = [122234.74,167321.06]
const W_histogram = [0.0,0.0127635328]
const W_fast = [0.0,0.015954416]
const W_slow = [0.0,0.0031908832]
const W_data = [['2022-07-08', 58.0, 53.8, 49.0, 58.0],['2022-07-15', 50.0, 54.0, 48.7, 55.3]]
const M_v = [289555.8]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 58.0, 54.0, 48.7, 58.0]]
        const D_a = [null,48.7,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}