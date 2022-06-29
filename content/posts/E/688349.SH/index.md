---
title: "C三一 - 688349.SH"
date: 2022-06-29T17:28:27+08:00
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
        const D_v = [894458.27,456830.36,353826.67,277881.59,216676.06,232743.08]
const D_histogram = [0.0,0.0931737892,0.1439239227,0.256992729,0.1639306174,-0.0946688263]
const D_fast = [0.0,0.1164672365,0.2031983507,0.3805153393,0.328435882,0.0461692317]
const D_slow = [0.0,0.0232934473,0.059274428,0.1235226102,0.1645052646,0.140838058]
const D_data = [['2022-06-22', 40.0, 40.96, 37.81, 43.34],['2022-06-23', 40.8, 42.42, 38.6, 42.52],['2022-06-24', 42.5, 42.38, 41.88, 46.24],['2022-06-27', 41.25, 43.78, 41.2, 44.2],['2022-06-28', 43.61, 41.44, 40.89, 44.2],['2022-06-29', 41.06, 38.46, 38.4, 41.16]]
const W_v = [1705115.2999999998,727300.73]
const W_histogram = [0.0,-0.2501652422]
const W_fast = [0.0,-0.3127065527]
const W_slow = [0.0,-0.0625413105]
const W_data = [['2022-06-24', 40.0, 42.38, 37.81, 46.24],['2022-07-01', 41.25, 38.46, 38.4, 44.2]]
const M_v = [2432416.0299999998]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-06-30', 40.0, 38.46, 37.81, 46.24]]
        const D_a = [null,null,46.24,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}