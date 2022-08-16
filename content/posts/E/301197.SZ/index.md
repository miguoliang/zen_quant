---
title: "工大科雅 - 301197.SZ"
date: 2022-08-16T20:29:48+08:00
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
        const D_v = [182758.37,133379.34,80413.02,67007.99,66513.63,67630.05,37856.88]
const D_histogram = [0.0,-0.1627350427,-0.3356045487,-0.4182071012,-0.4931937494,-0.6413148471,-0.6850117248]
const D_fast = [0.0,-0.2034188034,-0.4601894465,-0.6473437743,-0.84562886,-1.1540786694,-1.3690284782]
const D_slow = [0.0,-0.0406837607,-0.1245848978,-0.2291366731,-0.3524351105,-0.5127638223,-0.6840167535]
const D_data = [['2022-08-08', 44.0, 37.48, 37.35, 44.08],['2022-08-09', 34.3, 34.93, 33.0, 35.96],['2022-08-10', 33.52, 33.68, 33.2, 34.47],['2022-08-11', 33.6, 33.79, 33.41, 34.29],['2022-08-12', 33.58, 33.05, 33.0, 34.42],['2022-08-15', 32.2, 31.01, 30.95, 32.28],['2022-08-16', 31.03, 31.18, 30.8, 31.45]]
const W_v = [530072.35,105486.93]
const W_histogram = [0.0,-0.1193390313]
const W_fast = [0.0,-0.1491737892]
const W_slow = [0.0,-0.0298347578]
const W_data = [['2022-08-12', 44.0, 33.05, 33.0, 44.08],['2022-08-19', 32.2, 31.18, 30.8, 32.28]]
const M_v = [635559.28]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 44.0, 31.18, 30.8, 44.08]]
        const D_a = [null,null,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}