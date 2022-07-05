---
title: "C无人机 - 688297.SH"
date: 2022-07-05T18:48:08+08:00
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
        const D_v = [889932.4,444860.19,400302.91,239863.13,309968.65]
const D_histogram = [0.0,-0.2437834758,-0.279224279,-0.2677395035,-0.1004755283]
const D_fast = [0.0,-0.3047293447,-0.4099762177,-0.465426318,-0.3232812249]
const D_slow = [0.0,-0.0609458689,-0.1307519387,-0.1976868146,-0.2228056966]
const D_data = [['2022-06-29', 50.43, 57.0, 50.2, 57.53],['2022-06-30', 54.5, 53.18, 52.55, 55.8],['2022-07-01', 52.9, 54.81, 52.12, 57.6],['2022-07-04', 53.8, 55.09, 53.15, 56.99],['2022-07-05', 54.8, 57.35, 53.75, 59.57]]
const W_v = [1735095.5,549831.78]
const W_histogram = [0.0,0.1620968661]
const W_fast = [0.0,0.2026210826]
const W_slow = [0.0,0.0405242165]
const W_data = [['2022-07-01', 50.43, 54.81, 50.2, 57.6],['2022-07-08', 53.8, 57.35, 53.15, 59.57]]
const M_v = [1334792.5900000001,950134.6900000001]
const M_histogram = [0.0,0.2661196581]
const M_fast = [0.0,0.3326495726]
const M_slow = [0.0,0.0665299145]
const M_data = [['2022-06-30', 50.43, 53.18, 50.2, 57.53],['2022-07-29', 52.9, 57.35, 52.12, 59.57]]
        const D_a = [null,null,null,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}