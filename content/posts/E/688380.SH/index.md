---
title: "中微半导 - 688380.SH"
date: 2022-08-17T20:52:12+08:00
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
        const D_v = [429065.11,273462.82,174446.02,128844.41,124732.68,153573.17,80015.86,61788.65,68086.08]
const D_histogram = [0.0,-0.5169230769,-0.9243252246,-1.1962223463,-1.2551650788,-1.4299521304,-1.500276808,-1.4278210932,-1.3519330192]
const D_fast = [0.0,-0.6461538462,-1.2846373,-1.8555900083,-2.2283240105,-2.7605990946,-3.2059929743,-3.4904925328,-3.7525877135]
const D_slow = [0.0,-0.1292307692,-0.3603120754,-0.659367662,-0.9731589317,-1.3306469643,-1.7057161663,-2.0626714396,-2.4006546944]
const D_data = [['2022-08-05', 46.88, 56.2, 46.06, 60.58],['2022-08-08', 53.0, 48.1, 47.8, 53.6],['2022-08-09', 46.88, 46.35, 44.78, 47.53],['2022-08-10', 45.69, 45.28, 45.15, 47.48],['2022-08-11', 46.2, 45.95, 45.6, 47.15],['2022-08-12', 45.58, 42.62, 42.53, 46.38],['2022-08-15', 42.8, 41.87, 41.6, 43.35],['2022-08-16', 42.13, 42.22, 41.6, 42.57],['2022-08-17', 42.08, 41.23, 40.8, 42.08]]
const W_v = [429065.11,855059.1,209890.59]
const W_histogram = [0.0,-0.8666438746,-1.4511398576]
const W_fast = [0.0,-1.0833048433,-2.0305857907]
const W_slow = [0.0,-0.2166609687,-0.5794459331]
const W_data = [['2022-08-05', 46.88, 56.2, 46.06, 60.58],['2022-08-12', 53.0, 42.62, 42.53, 53.6],['2022-08-19', 42.8, 41.23, 40.8, 43.35]]
const M_v = [1494014.8]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 46.88, 41.23, 40.8, 60.58]]
        const D_a = [null,null,null,null,null,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}