---
title: "五芳斋 - 603237.SH"
date: 2022-09-14T20:48:48+08:00
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
        const D_v = [13176.53,4242.54,3764.4,170011.38,114623.63,80188.88,82433.66,52380.75,49364.72,59056.57]
const D_histogram = [0.0,0.3152592593,0.8427807956,0.9345105372,0.5898025851,0.3367142672,-0.0812977738,-0.4210384739,-0.5551046592,-0.565366586]
const D_fast = [0.0,0.3940740741,1.1322908093,1.4576481853,1.2603908794,1.0914811283,0.6531446438,0.2081443253,-0.0646980249,-0.2163015981]
const D_slow = [0.0,0.0788148148,0.2895100137,0.523137648,0.6705882943,0.7547668611,0.7344424177,0.6291827992,0.4904066344,0.3490649879]
const D_data = [['2022-08-31', 41.18, 49.42, 41.18, 49.42],['2022-09-01', 54.36, 54.36, 54.36, 54.36],['2022-09-02', 59.8, 59.8, 59.8, 59.8],['2022-09-05', 59.8, 56.79, 54.5, 63.0],['2022-09-06', 54.0, 51.33, 51.3, 55.0],['2022-09-07', 50.1, 51.33, 49.53, 52.73],['2022-09-08', 50.61, 47.65, 47.64, 51.0],['2022-09-09', 47.1, 46.47, 46.37, 47.8],['2022-09-13', 46.01, 47.45, 45.94, 47.74],['2022-09-14', 46.51, 48.22, 46.3, 48.97]]
const W_v = [21183.47,499638.3,108421.29]
const W_histogram = [0.0,-0.8506894587,-1.2256707786]
const W_fast = [0.0,-1.0633618234,-1.744760838]
const W_slow = [0.0,-0.2126723647,-0.5190900593]
const W_data = [['2022-09-02', 41.18, 59.8, 41.18, 59.8],['2022-09-09', 59.8, 46.47, 46.37, 63.0],['2022-09-16', 46.01, 48.22, 45.94, 48.97]]
const M_v = [13176.53,616066.5299999999]
const M_histogram = [0.0,-0.0765811966]
const M_fast = [0.0,-0.0957264957]
const M_slow = [0.0,-0.0191452991]
const M_data = [['2022-08-31', 41.18, 49.42, 41.18, 49.42],['2022-09-30', 54.36, 48.22, 45.94, 63.0]]
        const D_a = [null,null,null,63.0,null,null,null,null,45.94,null]
const W_a = [null,63.0,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}