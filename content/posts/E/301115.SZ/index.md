---
title: "C建科 - 301115.SZ"
date: 2022-09-05T20:24:24+08:00
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
        const D_v = [167933.88,147156.45,106503.57,51059.07]
const D_histogram = [0.0,0.1021082621,-0.0219961851,-0.096259257]
const D_fast = [0.0,0.1276353276,-0.0019681658,-0.100296052]
const D_slow = [0.0,0.0255270655,0.0200280193,-0.004036795]
const D_data = [['2022-08-31', 32.55, 33.8, 32.5, 39.9],['2022-09-01', 33.47, 35.4, 32.0, 37.61],['2022-09-02', 33.9, 32.54, 32.51, 33.92],['2022-09-05', 32.32, 32.58, 32.06, 33.15]]
const W_v = [421593.9,51059.07]
const W_histogram = [0.0,0.0025527066]
const W_fast = [0.0,0.0031908832]
const W_slow = [0.0,0.0006381766]
const W_data = [['2022-09-02', 32.55, 32.54, 32.0, 39.9],['2022-09-09', 32.32, 32.58, 32.06, 33.15]]
const M_v = [167933.88,304719.09]
const M_histogram = [0.0,-0.0778575499]
const M_fast = [0.0,-0.0973219373]
const M_slow = [0.0,-0.0194643875]
const M_data = [['2022-08-31', 32.55, 33.8, 32.5, 39.9],['2022-09-30', 33.47, 32.58, 32.0, 37.61]]
        const D_a = [null,null,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}