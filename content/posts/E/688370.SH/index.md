---
title: "丛麟科技 - 688370.SH"
date: 2022-09-06T20:48:28+08:00
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
        const D_v = [123286.59,70775.09,27909.24,19773.27,23485.57,11891.32,11424.94,10944.74,12961.43]
const D_histogram = [0.0,-0.1812421652,-0.2747163156,-0.3382854498,-0.4326141167,-0.46307201,-0.4368049658,-0.4193994128,-0.3762339472]
const D_fast = [0.0,-0.2265527066,-0.3887059358,-0.5368464324,-0.7393286285,-0.8855545243,-0.9684887216,-1.0559330218,-1.106826043]
const D_slow = [0.0,-0.0453105413,-0.1139896202,-0.1985609827,-0.3067145118,-0.4224825143,-0.5316837558,-0.636533609,-0.7305920958]
const D_data = [['2022-08-25', 49.0, 45.48, 45.44, 50.58],['2022-08-26', 44.12, 42.64, 42.57, 44.76],['2022-08-29', 42.81, 42.8, 42.51, 43.57],['2022-08-30', 43.05, 42.48, 42.33, 43.15],['2022-08-31', 42.5, 41.32, 41.25, 42.62],['2022-09-01', 41.16, 41.37, 41.13, 41.88],['2022-09-02', 41.2, 41.64, 41.16, 42.06],['2022-09-05', 41.6, 41.22, 41.16, 41.79],['2022-09-06', 41.4, 41.29, 40.91, 41.49]]
const W_v = [194061.68,94484.34,23906.17]
const W_histogram = [0.0,-0.0638176638,-0.1226626407]
const W_fast = [0.0,-0.0797720798,-0.1692827169]
const W_slow = [0.0,-0.015954416,-0.0466200761]
const W_data = [['2022-08-26', 49.0, 42.64, 42.57, 50.58],['2022-09-02', 42.81, 41.64, 41.13, 43.57],['2022-09-09', 41.6, 41.29, 40.91, 41.79]]
const M_v = [265229.76,47222.43]
const M_histogram = [0.0,-0.0019145299]
const M_fast = [0.0,-0.0023931624]
const M_slow = [0.0,-0.0004786325]
const M_data = [['2022-08-31', 49.0, 41.32, 41.25, 50.58],['2022-09-30', 41.16, 41.29, 40.91, 42.06]]
        const D_a = [null,null,null,null,null,41.13,null,null,null]
const W_a = [null,null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}