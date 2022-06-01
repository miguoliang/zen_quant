---
title: "瑜欣电子 - 301107.SZ"
date: 2022-06-01T20:45:13+08:00
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
        const D_v = [128904.34,108049.95,106253.02,93020.51,58764.04,64322.98,60864.2]
const D_histogram = [0.0,0.0676467236,-0.3359103644,-0.9956573665,-1.405153401,-1.4831563796,-1.4250503776]
const D_fast = [0.0,0.0845584046,-0.4029762745,-1.3116376183,-2.0724220031,-2.5212140766,-2.8193706689]
const D_slow = [0.0,0.0169116809,-0.0670659102,-0.3159802518,-0.6672686021,-1.038057697,-1.3943202913]
const D_data = [['2022-05-24', 54.5, 55.09, 50.76, 60.03],['2022-05-25', 50.99, 56.15, 50.03, 56.34],['2022-05-26', 55.0, 49.22, 48.51, 57.8],['2022-05-27', 46.0, 42.56, 42.28, 47.68],['2022-05-30', 42.0, 41.76, 41.0, 43.51],['2022-05-31', 42.77, 43.31, 42.01, 44.54],['2022-06-01', 42.54, 43.62, 42.3, 44.68]]
const W_v = [436227.82,183951.22]
const W_histogram = [0.0,0.0676467236]
const W_fast = [0.0,0.0845584046]
const W_slow = [0.0,0.0169116809]
const W_data = [['2022-05-27', 54.5, 42.56, 42.28, 60.03],['2022-06-02', 42.0, 43.62, 41.0, 44.68]]
const M_v = [559314.84,60864.2]
const M_histogram = [0.0,0.0197834758]
const M_fast = [0.0,0.0247293447]
const M_slow = [0.0,0.0049458689]
const M_data = [['2022-05-31', 54.5, 43.31, 41.0, 60.03],['2022-06-30', 42.54, 43.62, 42.3, 44.68]]
        const D_a = [null,null,null,null,41.0,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}