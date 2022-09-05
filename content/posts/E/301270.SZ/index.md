---
title: "C汉仪 - 301270.SZ"
date: 2022-09-05T20:30:22+08:00
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
        const D_v = [122141.13,123296.39,108269.86,84501.51]
const D_histogram = [0.0,0.7205014245,0.6463951169,0.4493507436]
const D_fast = [0.0,0.9006267806,0.9881192523,0.9034125648]
const D_slow = [0.0,0.1801253561,0.3417241354,0.4540618212]
const D_data = [['2022-08-31', 38.01, 39.51, 36.51, 45.05],['2022-09-01', 38.01, 50.8, 37.15, 58.0],['2022-09-02', 47.0, 43.18, 42.81, 52.3],['2022-09-05', 40.88, 41.4, 40.51, 44.67]]
const W_v = [353707.38,84501.51]
const W_histogram = [0.0,-0.1135954416]
const W_fast = [0.0,-0.141994302]
const W_slow = [0.0,-0.0283988604]
const W_data = [['2022-09-02', 38.01, 43.18, 36.51, 58.0],['2022-09-09', 40.88, 41.4, 40.51, 44.67]]
const M_v = [122141.13,316067.76]
const M_histogram = [0.0,0.1206153846]
const M_fast = [0.0,0.1507692308]
const M_slow = [0.0,0.0301538462]
const M_data = [['2022-08-31', 38.01, 39.51, 36.51, 45.05],['2022-09-30', 38.01, 41.4, 37.15, 58.0]]
        const D_a = [null,58.0,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}