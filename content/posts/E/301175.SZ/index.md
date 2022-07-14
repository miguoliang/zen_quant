---
title: "C中科环 - 301175.SZ"
date: 2022-07-14T20:24:13+08:00
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
        const D_v = [2357125.8399999999,1571374.4299999999,1940893.1699999999,1874111.6399999999,1751677.96]
const D_histogram = [0.0,-0.067008547,-0.0262088782,0.0315824165,0.0962840586]
const D_fast = [0.0,-0.0837606838,-0.0495132345,0.0161736644,0.1049463211]
const D_slow = [0.0,-0.0167521368,-0.0233043563,-0.0154087522,0.0086622625]
const D_data = [['2022-07-08', 7.05, 8.03, 7.04, 9.07],['2022-07-11', 7.58, 6.98, 6.97, 7.76],['2022-07-12', 6.79, 8.22, 6.72, 8.35],['2022-07-13', 8.18, 8.7, 8.0, 8.98],['2022-07-14', 8.5, 9.17, 8.14, 9.47]]
const W_v = [2357125.8399999999,7138057.1999999993]
const W_histogram = [0.0,0.0727521368]
const W_fast = [0.0,0.0909401709]
const W_slow = [0.0,0.0181880342]
const W_data = [['2022-07-08', 7.05, 8.03, 7.04, 9.07],['2022-07-15', 7.58, 9.17, 6.72, 9.47]]
const M_v = [9495183.0399999991]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 7.05, 9.17, 6.72, 9.47]]
        const D_a = [null,null,6.72,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}