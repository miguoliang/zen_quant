---
title: "C井松 - 688251.SH"
date: 2022-06-14T17:49:55+08:00
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
        const D_v = [104696.43,75949.34,56916.51,57857.33,34496.94,29442.42,25658.11]
const D_histogram = [0.0,-0.470974359,-0.6670189495,-1.1754470595,-1.4750915211,-1.6624569685,-1.7926404418]
const D_fast = [0.0,-0.5887179487,-0.9515172766,-1.7538071515,-2.4222244933,-3.0252041829,-3.6035477666]
const D_slow = [0.0,-0.1177435897,-0.2844983271,-0.578360092,-0.9471329723,-1.3627472144,-1.8109073248]
const D_data = [['2022-06-06', 54.05, 55.76, 48.32, 65.0],['2022-06-07', 51.01, 48.38, 48.2, 53.87],['2022-06-08', 48.38, 49.53, 48.38, 53.59],['2022-06-09', 46.0, 42.9, 42.49, 46.51],['2022-06-10', 42.0, 42.15, 41.4, 43.16],['2022-06-13', 41.91, 40.81, 40.18, 42.45],['2022-06-14', 40.66, 39.05, 38.25, 40.66]]
const W_v = [329916.55,55100.53]
const W_histogram = [0.0,-0.1978347578]
const W_fast = [0.0,-0.2472934473]
const W_slow = [0.0,-0.0494586895]
const W_data = [['2022-06-10', 54.05, 42.15, 41.4, 65.0],['2022-06-17', 41.91, 39.05, 38.25, 42.45]]
const M_v = [385017.08]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-06-30', 54.05, 39.05, 38.25, 65.0]]
        const D_a = [null,null,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}