---
title: "C建科 - 301115.SZ"
date: 2022-09-06T20:24:53+08:00
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
        const D_v = [167933.88,147156.45,106503.57,51059.07,55159.05]
const D_histogram = [0.0,0.1021082621,-0.0219961851,-0.096259257,-0.1734609315]
const D_fast = [0.0,0.1276353276,-0.0019681658,-0.100296052,-0.2208629594]
const D_slow = [0.0,0.0255270655,0.0200280193,-0.004036795,-0.0474020279]
const D_data = [['2022-08-31', 32.55, 33.8, 32.5, 39.9],['2022-09-01', 33.47, 35.4, 32.0, 37.61],['2022-09-02', 33.9, 32.54, 32.51, 33.92],['2022-09-05', 32.32, 32.58, 32.06, 33.15],['2022-09-06', 32.84, 32.02, 31.81, 32.96]]
const W_v = [421593.9,106218.12]
const W_histogram = [0.0,-0.0331851852]
const W_fast = [0.0,-0.0414814815]
const W_slow = [0.0,-0.0082962963]
const W_data = [['2022-09-02', 32.55, 32.54, 32.0, 39.9],['2022-09-09', 32.32, 32.02, 31.81, 33.15]]
const M_v = [167933.88,359878.14]
const M_histogram = [0.0,-0.1135954416]
const M_fast = [0.0,-0.141994302]
const M_slow = [0.0,-0.0283988604]
const M_data = [['2022-08-31', 32.55, 33.8, 32.5, 39.9],['2022-09-30', 33.47, 32.02, 31.81, 37.61]]
        const D_a = [null,null,null,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}