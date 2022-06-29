---
title: "C华如 - 301302.SZ"
date: 2022-06-29T17:11:59+08:00
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
        const D_v = [159723.4,109244.08,86030.0,77225.32,69980.99]
const D_histogram = [0.0,-0.3471680912,-0.464089324,-0.4058967932,-0.4021686419]
const D_fast = [0.0,-0.433960114,-0.6669036777,-0.7101853453,-0.8069993545]
const D_slow = [0.0,-0.0867920228,-0.2028143538,-0.3042885521,-0.4048307126]
const D_data = [['2022-06-23', 60.0, 67.04, 60.0, 72.99],['2022-06-24', 63.0, 61.6, 61.56, 64.79],['2022-06-27', 61.88, 62.88, 60.03, 64.8],['2022-06-28', 61.71, 64.53, 60.3, 64.94],['2022-06-29', 63.51, 63.64, 62.35, 67.21]]
const W_v = [268967.48,233236.31]
const W_histogram = [0.0,0.1301880342]
const W_fast = [0.0,0.1627350427]
const W_slow = [0.0,0.0325470085]
const W_data = [['2022-06-24', 60.0, 61.6, 60.0, 72.99],['2022-07-01', 61.88, 63.64, 60.03, 67.21]]
const M_v = [502203.79]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-06-30', 60.0, 63.64, 60.0, 72.99]]
        const D_a = [null,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}