---
title: "西测测试 - 301306.SZ"
date: 2022-08-05T20:23:49+08:00
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
        const D_v = [119155.26,102485.77,88787.87,71228.58,46540.8,61106.72,70334.51,59098.01,62278.05]
const D_histogram = [0.0,0.2029401709,0.0490894197,-0.2693836124,-0.4631315479,-0.5081416245,-0.5010803971,-0.4133849117,-0.2730608001]
const D_fast = [0.0,0.2536752137,0.1120968174,-0.2737221178,-0.5832529403,-0.755298423,-0.8735072949,-0.8891580374,-0.8170991258]
const D_slow = [0.0,0.0507350427,0.0630073977,-0.0043385054,-0.1201213924,-0.2471567985,-0.3724268978,-0.4757731257,-0.5440383257]
const D_data = [['2022-07-26', 57.0, 56.01, 54.1, 58.7],['2022-07-27', 57.0, 59.19, 55.11, 59.69],['2022-07-28', 57.1, 54.96, 54.88, 57.87],['2022-07-29', 54.0, 51.53, 51.41, 54.2],['2022-08-01', 52.33, 51.4, 51.31, 53.21],['2022-08-02', 51.61, 52.2, 51.61, 53.97],['2022-08-03', 50.0, 52.3, 48.7, 55.05],['2022-08-04', 52.72, 53.14, 51.12, 54.86],['2022-08-05', 51.9, 54.07, 50.3, 55.55]]
const W_v = [381657.48,299358.09]
const W_histogram = [0.0,0.1620968661]
const W_fast = [0.0,0.2026210826]
const W_slow = [0.0,0.0405242165]
const W_data = [['2022-07-29', 57.0, 51.53, 51.41, 59.69],['2022-08-05', 52.33, 54.07, 48.7, 55.55]]
const M_v = [381657.48,299358.09]
const M_histogram = [0.0,0.1620968661]
const M_fast = [0.0,0.2026210826]
const M_slow = [0.0,0.0405242165]
const M_data = [['2022-07-29', 57.0, 51.53, 51.41, 59.69],['2022-08-31', 52.33, 54.07, 48.7, 55.55]]
        const D_a = [null,59.69,null,null,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}