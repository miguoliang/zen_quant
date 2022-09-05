---
title: "五芳斋 - 603237.SH"
date: 2022-09-05T20:48:26+08:00
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
        const D_v = [13176.53,4242.54,3764.4,170011.38]
const D_histogram = [0.0,0.3152592593,0.8427807956,0.9345105372]
const D_fast = [0.0,0.3940740741,1.1322908093,1.4576481853]
const D_slow = [0.0,0.0788148148,0.2895100137,0.523137648]
const D_data = [['2022-08-31', 41.18, 49.42, 41.18, 49.42],['2022-09-01', 54.36, 54.36, 54.36, 54.36],['2022-09-02', 59.8, 59.8, 59.8, 59.8],['2022-09-05', 59.8, 56.79, 54.5, 63.0]]
const W_v = [21183.47,170011.38]
const W_histogram = [0.0,-0.1920911681]
const W_fast = [0.0,-0.2401139601]
const W_slow = [0.0,-0.048022792]
const W_data = [['2022-09-02', 41.18, 59.8, 41.18, 59.8],['2022-09-09', 59.8, 56.79, 54.5, 63.0]]
const M_v = [13176.53,178018.32]
const M_histogram = [0.0,0.4703361823]
const M_fast = [0.0,0.5879202279]
const M_slow = [0.0,0.1175840456]
const M_data = [['2022-08-31', 41.18, 49.42, 41.18, 49.42],['2022-09-30', 54.36, 56.79, 54.36, 63.0]]
        const D_a = [null,null,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}