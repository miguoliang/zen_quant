---
title: "紫建电子 - 301121.SZ"
date: 2022-08-18T20:25:06+08:00
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
        const D_v = [119371.99,105769.89,57856.77,63423.73,47820.6,31666.85,28296.1,32008.49,29917.7]
const D_histogram = [0.0,0.8392022792,0.8770365176,1.3748059463,1.4034669409,1.2227433448,1.2020952743,1.6043157621,2.3470341794]
const D_fast = [0.0,1.049002849,1.3060962168,2.147567132,2.5270948619,2.6520571019,2.9319328501,3.7352322784,5.0647092405]
const D_slow = [0.0,0.2098005698,0.4290596992,0.7727611858,1.123627921,1.4293137572,1.7298375758,2.1309165163,2.7176750611]
const D_data = [['2022-08-08', 89.05, 88.77, 79.8, 90.0],['2022-08-09', 85.4, 101.92, 83.21, 106.88],['2022-08-10', 95.0, 94.99, 92.2, 100.0],['2022-08-11', 92.1, 103.2, 91.03, 108.89],['2022-08-12', 100.88, 100.0, 94.5, 107.74],['2022-08-15', 97.98, 98.2, 95.95, 102.5],['2022-08-16', 97.5, 100.86, 94.8, 104.87],['2022-08-17', 98.39, 108.6, 96.5, 115.49],['2022-08-18', 109.07, 117.91, 109.0, 118.8]]
const W_v = [394242.98,121889.14]
const W_histogram = [0.0,1.142974359]
const W_fast = [0.0,1.4287179487]
const W_slow = [0.0,0.2857435897]
const W_data = [['2022-08-12', 89.05, 100.0, 79.8, 108.89],['2022-08-19', 97.98, 117.91, 94.8, 118.8]]
const M_v = [516132.1199999999]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 89.05, 117.91, 79.8, 118.8]]
        const D_a = [null,null,null,108.89,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}