---
title: "C天力 - 301152.SZ"
date: 2022-09-05T20:26:05+08:00
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
        const D_v = [171525.71,117834.3,89626.21,70490.97,59640.33,56100.84]
const D_histogram = [0.0,-0.3152592593,-0.8383135591,-1.0946899644,-1.2152082082,-1.0991723273]
const D_fast = [0.0,-0.3940740741,-1.1267067637,-1.6567556601,-2.0810759559,-2.2398331569]
const D_slow = [0.0,-0.0788148148,-0.2883932046,-0.5620656957,-0.8658677477,-1.1406608296]
const D_data = [['2022-08-29', 79.11, 68.69, 68.68, 82.0],['2022-08-30', 64.77, 63.75, 61.71, 65.7],['2022-08-31', 62.01, 58.38, 58.08, 63.2],['2022-09-01', 58.4, 58.77, 57.88, 60.99],['2022-09-02', 57.88, 58.42, 56.76, 59.85],['2022-09-05', 57.86, 60.3, 57.6, 60.3]]
const W_v = [509117.5200000001,56100.84]
const W_histogram = [0.0,0.119977208]
const W_fast = [0.0,0.14997151]
const W_slow = [0.0,0.029994302]
const W_data = [['2022-09-02', 79.11, 58.42, 56.76, 82.0],['2022-09-09', 57.86, 60.3, 57.6, 60.3]]
const M_v = [378986.22,186232.14]
const M_histogram = [0.0,0.1225299145]
const M_fast = [0.0,0.1531623932]
const M_slow = [0.0,0.0306324786]
const M_data = [['2022-08-31', 79.11, 58.38, 58.08, 82.0],['2022-09-30', 58.4, 60.3, 56.76, 60.99]]
        const D_a = [null,null,null,null,56.76,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}