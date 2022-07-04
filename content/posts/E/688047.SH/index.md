---
title: "龙芯中科 - 688047.SH"
date: 2022-07-04T20:23:38+08:00
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
        const D_v = [242084.44,168538.85,136532.85,118443.71,80043.24,58107.03,57203.59]
const D_histogram = [0.0,0.7434757835,1.3481308756,0.8616158523,0.5685970066,0.3145577286,0.0854249504]
const D_fast = [0.0,0.9293447293,1.8710325403,1.5999214801,1.4490518861,1.2736520403,1.0658754996]
const D_slow = [0.0,0.1858689459,0.5229016648,0.7383056278,0.8804548795,0.9590943116,0.9804505492]
const D_data = [['2022-06-24', 96.28, 89.07, 82.4, 99.67],['2022-06-27', 90.5, 100.72, 88.8, 105.88],['2022-06-28', 101.08, 103.53, 97.74, 106.63],['2022-06-29', 100.0, 91.15, 91.0, 100.77],['2022-06-30', 92.2, 92.15, 88.02, 93.05],['2022-07-01', 91.5, 91.64, 88.5, 92.96],['2022-07-04', 91.0, 90.94, 86.66, 92.45]]
const W_v = [242084.44,561665.6800000001,57203.59]
const W_histogram = [0.0,0.164011396,0.2131666334]
const W_fast = [0.0,0.205014245,0.3074611407]
const W_slow = [0.0,0.041002849,0.0942945073]
const W_data = [['2022-06-24', 96.28, 89.07, 82.4, 99.67],['2022-07-01', 90.5, 91.64, 88.02, 106.63],['2022-07-08', 91.0, 90.94, 86.66, 92.45]]
const M_v = [745643.09,115310.62]
const M_histogram = [0.0,-0.0772193732]
const M_fast = [0.0,-0.0965242165]
const M_slow = [0.0,-0.0193048433]
const M_data = [['2022-06-30', 96.28, 92.15, 82.4, 106.63],['2022-07-29', 91.5, 90.94, 86.66, 92.96]]
        const D_a = [null,null,106.63,null,null,null,null]
const W_a = [null,106.63,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}