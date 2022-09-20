---
title: "C嘉曼 - 301276.SZ"
date: 2022-09-20T20:31:11+08:00
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
        const D_v = [104974.18,75161.04,39626.28,44154.81,42444.11,37475.86,20381.28]
const D_histogram = [0.0,-0.1735840456,-0.292033266,-0.3403321906,-0.4466538188,-0.6044493894,-0.6495648156]
const D_fast = [0.0,-0.216980057,-0.4084375939,-0.5418195661,-0.759804649,-1.068712567,-1.2762191971]
const D_slow = [0.0,-0.0433960114,-0.1164043279,-0.2014873755,-0.3131508302,-0.4642631776,-0.6266543815]
const D_data = [['2022-09-09', 34.01, 34.03, 33.9, 38.0],['2022-09-13', 32.63, 31.31, 31.23, 32.72],['2022-09-14', 30.61, 31.01, 30.33, 31.56],['2022-09-15', 31.16, 31.16, 30.81, 31.82],['2022-09-16', 31.15, 29.66, 29.6, 31.39],['2022-09-19', 29.23, 27.82, 27.82, 29.23],['2022-09-20', 27.75, 28.1, 27.75, 28.26]]
const W_v = [104974.18,201386.24,57857.14]
const W_histogram = [0.0,-0.2788831909,-0.5379821787]
const W_fast = [0.0,-0.3486039886,-0.7421985211]
const W_slow = [0.0,-0.0697207977,-0.2042163424]
const W_data = [['2022-09-09', 34.01, 34.03, 33.9, 38.0],['2022-09-16', 32.63, 29.66, 29.6, 32.72],['2022-09-23', 29.23, 28.1, 27.75, 29.23]]
const M_v = [364217.5599999999]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-09-30', 34.01, 28.1, 27.75, 38.0]]
        const D_a = [null,null,30.33,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}