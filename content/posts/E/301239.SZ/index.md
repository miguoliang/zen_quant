---
title: "普瑞眼科 - 301239.SZ"
date: 2022-07-13T20:26:28+08:00
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
        const D_v = [228294.17,161152.17,111707.22,84026.64,93317.27,93715.21,90030.18]
const D_histogram = [0.0,0.2725014245,0.3333056582,0.4036175148,0.6986445988,0.5628851757,0.5822329712]
const D_fast = [0.0,0.3406267806,0.4847574289,0.6559736641,1.1256618978,1.1306237687,1.2955298069]
const D_slow = [0.0,0.0681253561,0.1514517707,0.2523561494,0.4270172991,0.567738593,0.7132968358]
const D_data = [['2022-07-05', 50.1, 52.72, 50.1, 55.58],['2022-07-06', 56.0, 56.99, 54.6, 60.0],['2022-07-07', 55.06, 55.5, 53.14, 57.08],['2022-07-08', 55.0, 56.3, 55.0, 58.48],['2022-07-11', 55.68, 60.6, 55.32, 61.97],['2022-07-12', 60.0, 56.21, 56.02, 62.88],['2022-07-13', 56.21, 58.39, 53.84, 58.99]]
const W_v = [585180.2000000001,277062.66]
const W_histogram = [0.0,0.1333789174]
const W_fast = [0.0,0.1667236467]
const W_slow = [0.0,0.0333447293]
const W_data = [['2022-07-08', 50.1, 56.3, 50.1, 60.0],['2022-07-15', 55.68, 58.39, 53.84, 62.88]]
const M_v = [862242.8600000001]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 50.1, 58.39, 50.1, 62.88]]
        const D_a = [null,null,null,null,null,62.88,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}