---
title: "C宇邦 - 301266.SZ"
date: 2022-06-15T17:37:00+08:00
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
        const D_v = [170511.64,130856.79,109706.71,101290.0,98756.23,100775.14]
const D_histogram = [0.0,-0.0650940171,-0.1540252952,-0.1718358944,-0.3485988209,-0.6353509072]
const D_fast = [0.0,-0.0813675214,-0.2088051233,-0.2695746961,-0.5334873278,-0.979077141]
const D_slow = [0.0,-0.0162735043,-0.0547798281,-0.0977388017,-0.1848885069,-0.3437262337]
const D_data = [['2022-06-08', 45.0, 45.52, 44.03, 50.26],['2022-06-09', 46.6, 44.5, 44.19, 48.66],['2022-06-10', 42.0, 43.69, 40.3, 44.2],['2022-06-13', 42.99, 44.15, 42.0, 46.5],['2022-06-14', 42.33, 41.4, 41.0, 45.58],['2022-06-15', 41.76, 38.33, 38.31, 42.55]]
const W_v = [411075.14,300821.37]
const W_histogram = [0.0,-0.3420626781]
const W_fast = [0.0,-0.4275783476]
const W_slow = [0.0,-0.0855156695]
const W_data = [['2022-06-10', 45.0, 43.69, 40.3, 50.26],['2022-06-17', 42.99, 38.33, 38.31, 46.5]]
const M_v = [711896.51]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-06-30', 45.0, 38.33, 38.31, 50.26]]
        const D_a = [null,null,40.3,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}