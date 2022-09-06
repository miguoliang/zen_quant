---
title: "C电生理-U - 688351.SH"
date: 2022-09-06T20:47:28+08:00
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
        const D_v = [318357.22,205560.82,110474.67,215364.32,121007.82]
const D_histogram = [0.0,0.0236125356,0.0090410175,0.0510518108,0.0483511183]
const D_fast = [0.0,0.0295156695,0.0172044058,0.0719781518,0.0813652389]
const D_slow = [0.0,0.0059031339,0.0081633883,0.020926341,0.0330141206]
const D_data = [['2022-08-31', 15.5, 13.15, 13.02, 15.65],['2022-09-01', 13.0, 13.52, 12.75, 14.09],['2022-09-02', 13.38, 13.08, 12.85, 13.5],['2022-09-05', 14.15, 13.89, 13.56, 15.39],['2022-09-06', 13.54, 13.48, 13.11, 13.7]]
const W_v = [634392.71,336372.14]
const W_histogram = [0.0,0.0255270655]
const W_fast = [0.0,0.0319088319]
const W_slow = [0.0,0.0063817664]
const W_data = [['2022-09-02', 15.5, 13.08, 12.75, 15.65],['2022-09-09', 14.15, 13.48, 13.11, 15.39]]
const M_v = [318357.22,652407.6300000001]
const M_histogram = [0.0,0.0210598291]
const M_fast = [0.0,0.0263247863]
const M_slow = [0.0,0.0052649573]
const M_data = [['2022-08-31', 15.5, 13.15, 13.02, 15.65],['2022-09-30', 13.0, 13.48, 12.75, 15.39]]
        const D_a = [null,12.75,null,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}