---
title: "C洛耐 - 688119.SH"
date: 2022-06-11T17:14:48+08:00
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
        const D_v = [1163541.3400000001,865072.58,575672.62,469328.3,265702.53]
const D_histogram = [0.0,-0.1518860399,-0.2317570279,-0.32942191,-0.3813149554]
const D_fast = [0.0,-0.1898575499,-0.3276677949,-0.5076881545,-0.6549099387]
const D_slow = [0.0,-0.03797151,-0.095910767,-0.1782662445,-0.2735949833]
const D_data = [['2022-06-06', 14.01, 12.68, 11.6, 14.98],['2022-06-07', 12.22, 10.3, 10.3, 12.22],['2022-06-08', 10.0, 10.41, 9.81, 10.92],['2022-06-09', 10.31, 9.46, 9.36, 10.33],['2022-06-10', 9.33, 9.31, 9.24, 9.55]]
const W_v = [3339317.3700000001]
const W_histogram = [0.0]
const W_fast = [0.0]
const W_slow = [0.0]
const W_data = [['2022-06-10', 14.01, 9.31, 9.24, 14.98]]
const M_v = [3339317.3700000001]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-06-30', 14.01, 9.31, 9.24, 14.98]]
        const D_a = [null,null,null,null,null]
const W_a = [null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}