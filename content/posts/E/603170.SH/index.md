---
title: "宝立食品 - 603170.SH"
date: 2022-07-25T20:49:01+08:00
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
        const D_v = [13231.81,2529.05,1790.15,2187.77,17207.01,27130.97,14513.39]
const D_histogram = [0.0,0.0925356125,0.2469434501,0.4416852779,0.6619794702,0.8973577751,1.1412080394]
const D_fast = [0.0,0.1156695157,0.3318132158,0.636976363,1.0227654229,1.4824831716,2.0116354457]
const D_slow = [0.0,0.0231339031,0.0848697657,0.1952910851,0.3607859527,0.5851253965,0.8704274063]
const D_data = [['2022-07-15', 12.06, 14.47, 12.06, 14.47],['2022-07-18', 15.92, 15.92, 15.92, 15.92],['2022-07-19', 17.51, 17.51, 17.51, 17.51],['2022-07-20', 19.26, 19.26, 19.26, 19.26],['2022-07-21', 21.19, 21.19, 21.19, 21.19],['2022-07-22', 23.31, 23.31, 23.31, 23.31],['2022-07-25', 25.64, 25.64, 25.64, 25.64]]
const W_v = [13231.81,50844.95,14513.39]
const W_histogram = [0.0,0.5641481481,1.0355810489]
const W_fast = [0.0,0.7051851852,1.4355133481]
const W_slow = [0.0,0.141037037,0.3999322993]
const W_data = [['2022-07-15', 12.06, 14.47, 12.06, 14.47],['2022-07-22', 15.92, 23.31, 15.92, 23.31],['2022-07-29', 25.64, 25.64, 25.64, 25.64]]
const M_v = [78590.15]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 12.06, 25.64, 12.06, 25.64]]
        const D_a = [null,null,null,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}