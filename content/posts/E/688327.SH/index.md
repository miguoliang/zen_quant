---
title: "云从科技-UW - 688327.SH"
date: 2022-06-10T17:29:27+08:00
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
        const D_v = [547836.02,348091.72,542045.73,461015.32,463703.82,353423.6,331139.87,317081.6,290639.99,209799.14]
const D_histogram = [0.0,-0.1250826211,0.2360439022,0.5218782564,0.9881310381,1.2855020478,1.5657163109,1.3746627685,1.0335942339,0.6797550081]
const D_fast = [0.0,-0.1563532764,0.2637842225,0.6800881408,1.393373682,2.0121202036,2.6837635444,2.8363756942,2.7537057181,2.5698052443]
const D_slow = [0.0,-0.0312706553,0.0277403203,0.1582098844,0.4052426439,0.7266181558,1.1180472336,1.4617129257,1.7201114842,1.8900502362]
const D_data = [['2022-05-27', 24.0, 21.4, 19.65, 25.06],['2022-05-30', 21.8, 19.44, 19.28, 22.1],['2022-05-31', 19.1, 26.22, 18.6, 27.24],['2022-06-01', 25.5, 27.35, 25.06, 27.99],['2022-06-02', 27.0, 32.3, 26.2, 35.1],['2022-06-06', 33.59, 33.25, 31.7, 34.7],['2022-06-07', 32.43, 35.88, 31.31, 36.6],['2022-06-08', 35.0, 31.58, 31.33, 35.5],['2022-06-09', 31.4, 29.45, 28.88, 32.36],['2022-06-10', 29.1, 28.35, 28.13, 29.66]]
const W_v = [547836.02,1814856.5900000001,1502084.2000000002]
const W_histogram = [0.0,0.6956125356,0.8414786244]
const W_fast = [0.0,0.8695156695,1.2257514144]
const W_slow = [0.0,0.1739031339,0.38427279]
const W_data = [['2022-05-27', 24.0, 21.4, 19.65, 25.06],['2022-06-02', 21.8, 32.3, 18.6, 35.1],['2022-06-10', 33.59, 28.35, 28.13, 36.6]]
const M_v = [1437973.47,2426803.3400000003]
const M_histogram = [0.0,0.1359316239]
const M_fast = [0.0,0.1699145299]
const M_slow = [0.0,0.033982906]
const M_data = [['2022-05-31', 24.0, 26.22, 18.6, 27.24],['2022-06-30', 25.5, 28.35, 25.06, 36.6]]
        const D_a = [null,null,18.6,null,null,null,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}