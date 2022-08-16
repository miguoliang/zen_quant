---
title: "C德科立 - 688205.SH"
date: 2022-08-16T20:41:10+08:00
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
        const D_v = [148905.28,97419.14,86700.72,77812.71,47978.23,32077.05]
const D_histogram = [0.0,-0.29802849,-0.319829404,-0.594840953,-0.8908959621,-1.0651658779]
const D_fast = [0.0,-0.3725356125,-0.4742938775,-0.8980156648,-1.4167946644,-1.8573560497]
const D_slow = [0.0,-0.0745071225,-0.1544644735,-0.3031747118,-0.5258987023,-0.7921901718]
const D_data = [['2022-08-09', 60.5, 61.02, 60.05, 69.0],['2022-08-10', 58.0, 56.35, 54.03, 59.15],['2022-08-11', 55.91, 58.68, 55.87, 60.87],['2022-08-12', 58.0, 54.3, 54.2, 60.35],['2022-08-15', 53.0, 51.83, 50.99, 53.22],['2022-08-16', 52.02, 51.2, 50.96, 52.3]]
const W_v = [410837.85,80055.28]
const W_histogram = [0.0,-0.1978347578]
const W_fast = [0.0,-0.2472934473]
const W_slow = [0.0,-0.0494586895]
const W_data = [['2022-08-12', 60.5, 54.3, 54.03, 69.0],['2022-08-19', 53.0, 51.2, 50.96, 53.22]]
const M_v = [490893.13]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 60.5, 51.2, 50.96, 69.0]]
        const D_a = [null,54.03,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}