---
title: "紫建电子 - 301121.SZ"
date: 2022-08-17T20:26:09+08:00
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
        const D_v = [119371.99,105769.89,57856.77,63423.73,47820.6,31666.85,28296.1,32008.49]
const D_histogram = [0.0,0.8392022792,0.8770365176,1.3748059463,1.4034669409,1.2227433448,1.2020952743,1.6043157621]
const D_fast = [0.0,1.049002849,1.3060962168,2.147567132,2.5270948619,2.6520571019,2.9319328501,3.7352322784]
const D_slow = [0.0,0.2098005698,0.4290596992,0.7727611858,1.123627921,1.4293137572,1.7298375758,2.1309165163]
const D_data = [['2022-08-08', 89.05, 88.77, 79.8, 90.0],['2022-08-09', 85.4, 101.92, 83.21, 106.88],['2022-08-10', 95.0, 94.99, 92.2, 100.0],['2022-08-11', 92.1, 103.2, 91.03, 108.89],['2022-08-12', 100.88, 100.0, 94.5, 107.74],['2022-08-15', 97.98, 98.2, 95.95, 102.5],['2022-08-16', 97.5, 100.86, 94.8, 104.87],['2022-08-17', 98.39, 108.6, 96.5, 115.49]]
const W_v = [394242.98,91971.44]
const W_histogram = [0.0,0.5488319088]
const W_fast = [0.0,0.686039886]
const W_slow = [0.0,0.1372079772]
const W_data = [['2022-08-12', 89.05, 100.0, 79.8, 108.89],['2022-08-19', 97.98, 108.6, 94.8, 115.49]]
const M_v = [486214.4199999999]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 89.05, 108.6, 79.8, 115.49]]
        const D_a = [null,null,null,108.89,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}