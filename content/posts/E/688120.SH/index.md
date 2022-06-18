---
title: "华海清科 - 688120.SH"
date: 2022-06-18T17:14:54+08:00
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
        const D_v = [155096.52,80248.87,53506.99,40815.86,39709.46,29135.58,24810.31,20837.0]
const D_histogram = [0.0,0.1589059829,1.0098812575,1.0709231819,0.8367022944,0.4692691102,0.552817835,0.4634790075]
const D_fast = [0.0,0.1986324786,1.3020780675,1.6308507874,1.6058054735,1.3556895669,1.5774427505,1.6039736749]
const D_slow = [0.0,0.0397264957,0.2921968101,0.5599276056,0.7691031792,0.8864204567,1.0246249155,1.1404946673]
const D_data = [['2022-06-08', 235.0, 224.1, 218.86, 246.6],['2022-06-09', 226.23, 226.59, 222.23, 236.61],['2022-06-10', 228.0, 238.5, 220.57, 244.03],['2022-06-13', 235.65, 231.97, 223.0, 235.8],['2022-06-14', 227.0, 228.66, 214.0, 232.88],['2022-06-15', 226.0, 226.0, 223.0, 237.77],['2022-06-16', 225.95, 231.43, 225.16, 241.0],['2022-06-17', 226.99, 229.81, 223.42, 235.35]]
const W_v = [288852.38,155308.21]
const W_histogram = [0.0,-0.5545754986]
const W_fast = [0.0,-0.6932193732]
const W_slow = [0.0,-0.1386438746]
const W_data = [['2022-06-10', 235.0, 238.5, 218.86, 246.6],['2022-06-17', 235.65, 229.81, 214.0, 241.0]]
const M_v = [444160.59]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-06-30', 235.0, 229.81, 214.0, 246.6]]
        const D_a = [null,null,null,null,214.0,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}