---
title: "C科捷 - 688455.SH"
date: 2022-09-21T20:50:28+08:00
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
        const D_v = [245513.4,165826.8,114703.95,61358.07,61299.73]
const D_histogram = [0.0,-0.2271908832,-0.466290397,-0.5805563933,-0.6143713546]
const D_fast = [0.0,-0.283988604,-0.639660717,-0.8990658117,-1.0864736116]
const D_slow = [0.0,-0.0567977208,-0.17337032,-0.3185094184,-0.472102257]
const D_data = [['2022-09-15', 23.0, 21.18, 20.83, 24.92],['2022-09-16', 20.01, 17.62, 17.52, 20.01],['2022-09-19', 17.38, 15.91, 15.71, 17.4],['2022-09-20', 16.08, 16.06, 15.88, 16.48],['2022-09-21', 15.95, 16.13, 15.4, 16.68]]
const W_v = [411340.2,237361.75]
const W_histogram = [0.0,-0.0950883191]
const W_fast = [0.0,-0.1188603989]
const W_slow = [0.0,-0.0237720798]
const W_data = [['2022-09-16', 23.0, 17.62, 17.52, 24.92],['2022-09-23', 17.38, 16.13, 15.4, 17.4]]
const M_v = [648701.9499999998]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-09-30', 23.0, 16.13, 15.4, 24.92]]
        const D_a = [null,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}