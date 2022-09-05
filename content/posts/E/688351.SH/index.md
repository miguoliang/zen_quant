---
title: "C电生理-U - 688351.SH"
date: 2022-09-05T20:47:40+08:00
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
        const D_v = [318357.22,205560.82,110474.67,215364.32]
const D_histogram = [0.0,0.0236125356,0.0090410175,0.0510518108]
const D_fast = [0.0,0.0295156695,0.0172044058,0.0719781518]
const D_slow = [0.0,0.0059031339,0.0081633883,0.020926341]
const D_data = [['2022-08-31', 15.5, 13.15, 13.02, 15.65],['2022-09-01', 13.0, 13.52, 12.75, 14.09],['2022-09-02', 13.38, 13.08, 12.85, 13.5],['2022-09-05', 14.15, 13.89, 13.56, 15.39]]
const W_v = [634392.71,215364.32]
const W_histogram = [0.0,0.0516923077]
const W_fast = [0.0,0.0646153846]
const W_slow = [0.0,0.0129230769]
const W_data = [['2022-09-02', 15.5, 13.08, 12.75, 15.65],['2022-09-09', 14.15, 13.89, 13.56, 15.39]]
const M_v = [318357.22,531399.8100000001]
const M_histogram = [0.0,0.0472250712]
const M_fast = [0.0,0.059031339]
const M_slow = [0.0,0.0118062678]
const M_data = [['2022-08-31', 15.5, 13.15, 13.02, 15.65],['2022-09-30', 13.0, 13.89, 12.75, 15.39]]
        const D_a = [null,12.75,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}