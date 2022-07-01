---
title: "三一重能 - 688349.SH"
date: 2022-07-01T17:30:40+08:00
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
        const D_v = [894458.27,456830.36,353826.67,277881.59,216676.06,232743.08,226300.45,160102.69]
const D_histogram = [0.0,0.0931737892,0.1439239227,0.256992729,0.1639306174,-0.0946688263,-0.106932795,-0.0570856304]
const D_fast = [0.0,0.1164672365,0.2031983507,0.3805153393,0.328435882,0.0461692317,0.0071720643,0.0427478212]
const D_slow = [0.0,0.0232934473,0.059274428,0.1235226102,0.1645052646,0.140838058,0.1141048593,0.0998334517]
const D_data = [['2022-06-22', 40.0, 40.96, 37.81, 43.34],['2022-06-23', 40.8, 42.42, 38.6, 42.52],['2022-06-24', 42.5, 42.38, 41.88, 46.24],['2022-06-27', 41.25, 43.78, 41.2, 44.2],['2022-06-28', 43.61, 41.44, 40.89, 44.2],['2022-06-29', 41.06, 38.46, 38.4, 41.16],['2022-06-30', 38.6, 40.75, 38.02, 41.76],['2022-07-01', 40.45, 41.58, 40.1, 43.0]]
const W_v = [1705115.2999999998,1113703.8699999999]
const W_histogram = [0.0,-0.0510541311]
const W_fast = [0.0,-0.0638176638]
const W_slow = [0.0,-0.0127635328]
const W_data = [['2022-06-24', 40.0, 42.38, 37.81, 46.24],['2022-07-01', 41.25, 41.58, 38.02, 44.2]]
const M_v = [2658716.48,160102.69]
const M_histogram = [0.0,0.052968661]
const M_fast = [0.0,0.0662108262]
const M_slow = [0.0,0.0132421652]
const M_data = [['2022-06-30', 40.0, 40.75, 37.81, 46.24],['2022-07-29', 40.45, 41.58, 40.1, 43.0]]
        const D_a = [null,null,46.24,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}