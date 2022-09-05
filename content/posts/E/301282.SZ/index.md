---
title: "金禄电子 - 301282.SZ"
date: 2022-09-05T20:30:29+08:00
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
        const D_v = [226271.73,149242.34,127028.11,102607.91,82710.68,110082.16,156125.87]
const D_histogram = [0.0,-0.3458917379,-0.3989033076,-0.6213958673,-0.6900617545,-0.5716240246,-0.1838277739]
const D_fast = [0.0,-0.4323646724,-0.585102069,-0.9629435955,-1.2041249214,-1.2285931976,-0.8867538903]
const D_slow = [0.0,-0.0864729345,-0.1861987614,-0.3415477282,-0.5140631668,-0.656969173,-0.7029261164]
const D_data = [['2022-08-26', 42.1, 39.8, 38.83, 49.9],['2022-08-29', 35.0, 34.38, 33.4, 37.88],['2022-08-30', 33.8, 36.65, 33.5, 37.77],['2022-08-31', 35.28, 33.33, 33.3, 36.2],['2022-09-01', 33.0, 33.88, 32.99, 35.3],['2022-09-02', 33.35, 35.77, 33.21, 37.24],['2022-09-05', 37.0, 40.12, 36.71, 42.83]]
const W_v = [226271.73,571671.2,156125.87]
const W_histogram = [0.0,-0.2571851852,-0.1267087897]
const W_fast = [0.0,-0.3214814815,-0.2226822834]
const W_slow = [0.0,-0.0642962963,-0.0959734937]
const W_data = [['2022-08-26', 42.1, 39.8, 38.83, 49.9],['2022-09-02', 35.0, 35.77, 32.99, 37.88],['2022-09-09', 37.0, 40.12, 36.71, 42.83]]
const M_v = [605150.09,348918.71]
const M_histogram = [0.0,0.4333219373]
const M_fast = [0.0,0.5416524217]
const M_slow = [0.0,0.1083304843]
const M_data = [['2022-08-31', 42.1, 33.33, 33.3, 49.9],['2022-09-30', 33.0, 40.12, 32.99, 42.83]]
        const D_a = [null,null,null,null,32.99,null,null]
const W_a = [null,32.99,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}