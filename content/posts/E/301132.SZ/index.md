---
title: "C满坤 - 301132.SZ"
date: 2022-08-16T20:26:55+08:00
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
        const D_v = [224621.39,155921.6,137541.34,109431.46,84154.21]
const D_histogram = [0.0,-0.1684786325,-0.3312322205,-0.5723699636,-0.722971193]
const D_fast = [0.0,-0.2105982906,-0.4561599338,-0.8403901678,-1.1717341954]
const D_slow = [0.0,-0.0421196581,-0.1249277132,-0.2680202042,-0.4487630024]
const D_data = [['2022-08-10', 50.49, 44.83, 43.88, 50.49],['2022-08-11', 40.1, 42.19, 39.33, 43.35],['2022-08-12', 41.4, 41.15, 40.94, 44.93],['2022-08-15', 39.88, 38.68, 38.48, 40.3],['2022-08-16', 38.01, 38.18, 37.86, 38.94]]
const W_v = [518084.33,193585.67]
const W_histogram = [0.0,-0.1895384615]
const W_fast = [0.0,-0.2369230769]
const W_slow = [0.0,-0.0473846154]
const W_data = [['2022-08-12', 50.49, 41.15, 39.33, 50.49],['2022-08-19', 39.88, 38.18, 37.86, 40.3]]
const M_v = [711669.9999999999]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 50.49, 38.18, 37.86, 50.49]]
        const D_a = [null,39.33,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}