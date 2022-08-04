---
title: "C英诺特 - 688253.SH"
date: 2022-08-04T20:41:36+08:00
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
        const D_v = [218808.27,139787.96,68708.14,66662.78,64277.93,41774.66]
const D_histogram = [0.0,-0.1991111111,-0.3117421969,-0.4828934784,-0.5204691037,-0.5375364352]
const D_fast = [0.0,-0.2488888889,-0.4394555239,-0.731330175,-0.8990230763,-1.0504745166]
const D_slow = [0.0,-0.0497777778,-0.127713327,-0.2484366966,-0.3785539725,-0.5129380813]
const D_data = [['2022-07-28', 33.42, 33.0, 32.03, 35.38],['2022-07-29', 31.98, 29.88, 29.8, 31.98],['2022-08-01', 29.61, 29.9, 29.1, 30.89],['2022-08-02', 30.3, 28.05, 27.75, 30.46],['2022-08-03', 28.3, 28.71, 28.2, 29.89],['2022-08-04', 29.5, 28.33, 28.18, 29.66]]
const W_v = [358596.23,241423.51]
const W_histogram = [0.0,-0.0989173789]
const W_fast = [0.0,-0.1236467236]
const W_slow = [0.0,-0.0247293447]
const W_data = [['2022-07-29', 33.42, 29.88, 29.8, 35.38],['2022-08-05', 29.61, 28.33, 27.75, 30.89]]
const M_v = [358596.23,241423.51]
const M_histogram = [0.0,-0.0989173789]
const M_fast = [0.0,-0.1236467236]
const M_slow = [0.0,-0.0247293447]
const M_data = [['2022-07-29', 33.42, 29.88, 29.8, 35.38],['2022-08-31', 29.61, 28.33, 27.75, 30.89]]
        const D_a = [null,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}