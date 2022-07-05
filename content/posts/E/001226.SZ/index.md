---
title: "拓山重工 - 001226.SZ"
date: 2022-07-05T18:22:28+08:00
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
        const D_v = [6310.96,1123.82,4183.42,1348.14,1362.31,135043.16,21801.28,83274.29,67992.12,50290.12]
const D_histogram = [0.0,0.2265527066,0.6056859928,1.0840874451,1.6246004069,1.8816359136,1.598615004,1.1210307926,0.4897337565,-0.0361750831]
const D_fast = [0.0,0.2831908832,0.8137456676,1.5631689812,2.5098320447,3.2372765299,3.3539093712,3.156582858,2.647719261,2.1127666507]
const D_slow = [0.0,0.0566381766,0.2080596748,0.4790815361,0.8852316378,1.3556406162,1.7552943672,2.0355520654,2.1579855045,2.1489417338]
const D_data = [['2022-06-22', 29.59, 35.51, 29.59, 35.51],['2022-06-23', 39.06, 39.06, 39.06, 39.06],['2022-06-24', 42.97, 42.97, 42.97, 42.97],['2022-06-27', 47.27, 47.27, 47.27, 47.27],['2022-06-28', 52.0, 52.0, 52.0, 52.0],['2022-06-29', 57.2, 52.18, 48.0, 57.2],['2022-06-30', 47.01, 46.96, 46.96, 48.5],['2022-07-01', 42.26, 43.82, 42.26, 48.84],['2022-07-04', 42.2, 39.83, 39.8, 42.28],['2022-07-05', 39.41, 38.5, 38.28, 39.77]]
const W_v = [11618.2,242829.18,118282.24]
const W_histogram = [0.0,0.0542450142,-0.2542324819]
const W_fast = [0.0,0.0678062678,-0.3042293488]
const W_slow = [0.0,0.0135612536,-0.0499968669]
const W_data = [['2022-06-24', 29.59, 42.97, 29.59, 42.97],['2022-07-01', 47.27, 43.82, 42.26, 57.2],['2022-07-08', 42.2, 38.5, 38.28, 42.28]]
const M_v = [171173.09,201556.53]
const M_histogram = [0.0,-0.5398974359]
const M_fast = [0.0,-0.6748717949]
const M_slow = [0.0,-0.134974359]
const M_data = [['2022-06-30', 29.59, 46.96, 29.59, 57.2],['2022-07-29', 42.26, 38.5, 38.28, 48.84]]
        const D_a = [null,null,null,null,null,57.2,null,null,null,null]
const W_a = [null,57.2,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}