---
title: "东田微 - 301183.SZ"
date: 2022-06-07T16:14:35+08:00
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
        const D_v = [127460.47,104128.44,104166.92,90951.43,60271.88,111096.1,87247.0,100897.59,83783.24,94704.87]
const D_histogram = [0.0,-0.2654814815,-0.385449235,-0.6986911019,-0.8323480733,-0.647982698,-0.5571017114,-0.3828050391,-0.1919310559,-0.2114716826]
const D_fast = [0.0,-0.3318518519,-0.5481819141,-1.0360965565,-1.3778405463,-1.3554708454,-1.4038652867,-1.3252698742,-1.182378655,-1.2547872023]
const D_slow = [0.0,-0.0663703704,-0.1627326791,-0.3374054546,-0.5454924729,-0.7074881474,-0.8467635753,-0.9424648351,-0.990447599,-1.0433155197]
const D_data = [['2022-05-24', 46.0, 41.96, 41.92, 48.0],['2022-05-25', 38.5, 37.8, 37.0, 40.62],['2022-05-26', 36.8, 38.3, 35.66, 40.47],['2022-05-27', 37.0, 34.23, 34.21, 38.13],['2022-05-30', 33.2, 34.59, 33.2, 35.05],['2022-05-31', 34.2, 38.03, 33.62, 41.51],['2022-06-01', 36.2, 37.01, 35.37, 38.26],['2022-06-02', 37.81, 38.27, 37.03, 41.0],['2022-06-06', 37.0, 39.1, 36.36, 39.93],['2022-06-07', 39.05, 36.62, 36.5, 41.0]]
const W_v = [426707.26,359512.57,178488.11]
const W_histogram = [0.0,0.2578233618,0.3000197466]
const W_fast = [0.0,0.3222792023,0.4394805237]
const W_slow = [0.0,0.0644558405,0.1394607771]
const W_data = [['2022-05-27', 46.0, 34.23, 34.21, 48.0],['2022-06-02', 33.2, 38.27, 33.2, 41.51],['2022-06-10', 37.0, 36.62, 36.36, 41.0]]
const M_v = [598075.24,366632.7]
const M_histogram = [0.0,-0.089982906]
const M_fast = [0.0,-0.1124786325]
const M_slow = [0.0,-0.0224957265]
const M_data = [['2022-05-31', 46.0, 38.03, 33.2, 48.0],['2022-06-30', 36.2, 36.62, 35.37, 41.0]]
        const D_a = [null,null,null,null,33.2,null,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}