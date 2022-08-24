---
title: "C汇成 - 688403.SH"
date: 2022-08-23T22:10:46+08:00
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
        const D_v = [975357.85,798351.1899999999,558301.4300000001,278692.11]
const D_histogram = [0.0,0.0350997151,-0.0935156046,-0.1767519308]
const D_fast = [0.0,0.0438746439,-0.108119577,-0.2355438858]
const D_slow = [0.0,0.0087749288,-0.0146039724,-0.0587919551]
const D_data = [['2022-08-18', 17.88, 16.94, 16.58, 18.3],['2022-08-19', 17.55, 17.49, 16.88, 19.18],['2022-08-22', 17.25, 15.16, 15.12, 17.4],['2022-08-23', 14.82, 15.04, 14.71, 15.66]]
const W_v = [1773709.04,836993.54]
const W_histogram = [0.0,-0.1563532764]
const W_fast = [0.0,-0.1954415954]
const W_slow = [0.0,-0.0390883191]
const W_data = [['2022-08-19', 17.88, 17.49, 16.58, 19.18],['2022-08-26', 17.25, 15.04, 14.71, 17.4]]
const M_v = [2610702.5800000001]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 17.88, 15.04, 14.71, 19.18]]
        const D_a = [null,19.18,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}