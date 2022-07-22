---
title: "劲旅环境 - 001230.SZ"
date: 2022-07-22T20:16:08+08:00
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
        const D_v = [137602.62,109727.86,97740.24,61230.16,63365.46,52828.8]
const D_histogram = [0.0,-0.2833504274,-0.615204461,-0.8010314736,-0.9654511162,-0.9920379847]
const D_fast = [0.0,-0.3541880342,-0.8398431831,-1.225928064,-1.6317104857,-1.9063068504]
const D_slow = [0.0,-0.0708376068,-0.2246387221,-0.4248965905,-0.6662593695,-0.9142688657]
const D_data = [['2022-07-15', 41.41, 44.49, 41.41, 49.69],['2022-07-18', 40.04, 40.05, 40.04, 44.0],['2022-07-19', 38.95, 37.39, 37.35, 38.95],['2022-07-20', 37.1, 37.2, 36.61, 37.36],['2022-07-21', 37.0, 35.73, 35.71, 37.0],['2022-07-22', 35.61, 36.04, 35.52, 36.85]]
const W_v = [137602.62,384892.52]
const W_histogram = [0.0,-0.5392592593]
const W_fast = [0.0,-0.6740740741]
const W_slow = [0.0,-0.1348148148]
const W_data = [['2022-07-15', 41.41, 44.49, 41.41, 49.69],['2022-07-22', 40.04, 36.04, 35.52, 44.0]]
const M_v = [522495.14]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 41.41, 36.04, 35.52, 49.69]]
        const D_a = [null,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}