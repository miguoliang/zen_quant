---
title: "信邦智能 - 301112.SZ"
date: 2022-07-11T22:49:48+08:00
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
        const D_v = [195704.77,170814.67,140167.58,101584.47,130829.89,114785.36,94355.92,57310.64,59695.78]
const D_histogram = [0.0,-0.2731396011,-0.7472092077,-1.0430564584,-1.1225192279,-1.1221736891,-1.3200697206,-1.3671845632,-1.4680073194]
const D_fast = [0.0,-0.3414245014,-1.0022964099,-1.5589077752,-1.9190003516,-2.1991982352,-2.7271116968,-3.1160226802,-3.5838472662]
const D_slow = [0.0,-0.0682849003,-0.2550872022,-0.5158513168,-0.7964811238,-1.0770245461,-1.4070419762,-1.748838117,-2.1158399468]
const D_data = [['2022-06-29', 58.0, 58.76, 56.1, 63.0],['2022-06-30', 57.0, 54.48, 54.04, 63.52],['2022-07-01', 50.66, 49.5, 48.2, 51.98],['2022-07-04', 48.99, 48.87, 48.6, 51.46],['2022-07-05', 47.5, 49.6, 45.86, 50.63],['2022-07-06', 48.82, 49.35, 48.03, 51.98],['2022-07-07', 48.68, 45.17, 44.98, 48.72],['2022-07-08', 45.01, 45.09, 44.77, 46.15],['2022-07-11', 44.83, 42.6, 41.97, 44.83]]
const W_v = [506687.02,498866.28,59695.78]
const W_histogram = [0.0,-0.2814358974,-0.6013456644]
const W_fast = [0.0,-0.3517948718,-0.8220410549]
const W_slow = [0.0,-0.0703589744,-0.2206953905]
const W_data = [['2022-07-01', 58.0, 49.5, 48.2, 63.52],['2022-07-08', 48.99, 45.09, 44.77, 51.98],['2022-07-15', 44.83, 42.6, 41.97, 44.83]]
const M_v = [366519.44,698729.64]
const M_histogram = [0.0,-0.7581538462]
const M_fast = [0.0,-0.9476923077]
const M_slow = [0.0,-0.1895384615]
const M_data = [['2022-06-30', 58.0, 54.48, 54.04, 63.52],['2022-07-29', 50.66, 42.6, 41.97, 51.98]]
        const D_a = [null,null,null,null,45.86,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}