---
title: "C华大九 - 301269.SZ"
date: 2022-08-04T20:30:14+08:00
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
        const D_v = [507985.56,275999.52,255380.52,293989.36,234015.36]
const D_histogram = [0.0,0.0644558405,0.3368169025,1.2751900775,2.6210289118]
const D_fast = [0.0,0.0805698006,0.4371350882,1.6943057826,3.6954018448]
const D_slow = [0.0,0.0161139601,0.1003181857,0.4191157051,1.074372933]
const D_data = [['2022-07-29', 69.05, 75.0, 68.06, 75.5],['2022-08-01', 73.9, 76.01, 71.01, 76.01],['2022-08-02', 73.99, 79.7, 72.4, 80.11],['2022-08-03', 78.94, 92.02, 77.61, 100.46],['2022-08-04', 93.0, 105.0, 92.9, 108.38]]
const W_v = [507985.56,1059384.76]
const W_histogram = [0.0,1.9145299145]
const W_fast = [0.0,2.3931623932]
const W_slow = [0.0,0.4786324786]
const W_data = [['2022-07-29', 69.05, 75.0, 68.06, 75.5],['2022-08-05', 73.9, 105.0, 71.01, 108.38]]
const M_v = [507985.56,1059384.76]
const M_histogram = [0.0,1.9145299145]
const M_fast = [0.0,2.3931623932]
const M_slow = [0.0,0.4786324786]
const M_data = [['2022-07-29', 69.05, 75.0, 68.06, 75.5],['2022-08-31', 73.9, 105.0, 71.01, 108.38]]
        const D_a = [null,null,null,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}