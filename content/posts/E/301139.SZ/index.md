---
title: "C元道 - 301139.SZ"
date: 2022-07-14T20:23:29+08:00
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
        const D_v = [145186.77,86317.2,77722.39,53743.98,57955.65]
const D_histogram = [0.0,-0.3184501425,-0.3768227596,-0.4826923284,-0.5070210866]
const D_fast = [0.0,-0.3980626781,-0.5506409851,-0.777183636,-0.9282676658]
const D_slow = [0.0,-0.0796125356,-0.1738182255,-0.2944913076,-0.4212465792]
const D_data = [['2022-07-08', 38.46, 37.87, 37.36, 43.46],['2022-07-11', 33.5, 32.88, 32.53, 34.55],['2022-07-12', 32.63, 34.82, 32.1, 35.96],['2022-07-13', 33.99, 33.4, 33.01, 33.99],['2022-07-14', 32.7, 33.62, 32.57, 34.84]]
const W_v = [145186.77,275739.22]
const W_histogram = [0.0,-0.2712250712]
const W_fast = [0.0,-0.339031339]
const W_slow = [0.0,-0.0678062678]
const W_data = [['2022-07-08', 38.46, 37.87, 37.36, 43.46],['2022-07-15', 33.5, 33.62, 32.1, 35.96]]
const M_v = [420925.99]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 38.46, 33.62, 32.1, 43.46]]
        const D_a = [null,null,32.1,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}