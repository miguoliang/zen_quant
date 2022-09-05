---
title: "振华风光 - 688439.SH"
date: 2022-09-05T20:49:47+08:00
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
        const D_v = [303975.86,143927.96,93146.78,80382.95,90278.24,72984.2,52784.77]
const D_histogram = [0.0,0.7645356125,1.0436431652,1.4099169098,1.1351342206,1.6292959152,1.6389554802]
const D_fast = [0.0,0.9556695157,1.4956878597,2.2144408317,2.2234416977,3.124927371,3.5443258061]
const D_slow = [0.0,0.1911339031,0.4520446944,0.8045239219,1.088307477,1.4956314558,1.9053703259]
const D_data = [['2022-08-26', 96.0, 100.18, 95.2, 106.0],['2022-08-29', 99.82, 112.16, 98.12, 115.2],['2022-08-30', 113.83, 109.68, 108.22, 117.01],['2022-08-31', 109.48, 113.6, 106.01, 115.23],['2022-09-01', 113.6, 106.97, 103.33, 115.74],['2022-09-02', 107.0, 118.5, 106.0, 118.5],['2022-09-05', 116.5, 115.35, 111.5, 117.3]]
const W_v = [303975.86,480720.13,52784.77]
const W_histogram = [0.0,1.1691396011,1.6369550767]
const W_fast = [0.0,1.4614245014,2.3384787461]
const W_slow = [0.0,0.2922849003,0.7015236695]
const W_data = [['2022-08-26', 96.0, 100.18, 95.2, 106.0],['2022-09-02', 99.82, 118.5, 98.12, 118.5],['2022-09-09', 116.5, 115.35, 111.5, 117.3]]
const M_v = [621433.5499999999,216047.21]
const M_histogram = [0.0,0.1116809117]
const M_fast = [0.0,0.1396011396]
const M_slow = [0.0,0.0279202279]
const M_data = [['2022-08-31', 96.0, 113.6, 95.2, 117.01],['2022-09-30', 113.6, 115.35, 103.33, 118.5]]
        const D_a = [null,null,117.01,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}