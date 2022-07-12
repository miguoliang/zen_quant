---
title: "C思科 - 688053.SH"
date: 2022-07-12T17:17:08+08:00
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
        const D_v = [122234.74,73224.8,60591.3]
const D_histogram = [0.0,-0.2329344729,-0.0904992654]
const D_fast = [0.0,-0.2911680912,-0.1713577]
const D_slow = [0.0,-0.0582336182,-0.0808584346]
const D_data = [['2022-07-08', 58.0, 53.8, 49.0, 58.0],['2022-07-11', 50.0, 50.15, 48.7, 52.38],['2022-07-12', 50.0, 54.47, 49.98, 55.3]]
const W_v = [122234.74,133816.1]
const W_histogram = [0.0,0.0427578348]
const W_fast = [0.0,0.0534472934]
const W_slow = [0.0,0.0106894587]
const W_data = [['2022-07-08', 58.0, 53.8, 49.0, 58.0],['2022-07-15', 50.0, 54.47, 48.7, 55.3]]
const M_v = [256050.84]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 58.0, 54.47, 48.7, 58.0]]
        const D_a = [null,48.7,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}