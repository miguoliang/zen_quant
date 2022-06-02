---
title: "联翔股份 - 603272.SH"
date: 2022-06-02T17:31:20+08:00
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
        const D_v = [9528.05,2863.84,3983.98,2185.54,5581.54,9047.83,195105.7,31373.88,137970.21,136749.29]
const D_histogram = [0.0,0.1250826211,0.3344860123,0.5990402816,0.8976064096,1.2170241247,1.2811040729,1.0486761495,0.8029319898,0.4373638272]
const D_fast = [0.0,0.1563532764,0.4493781706,0.8636925104,1.3866602408,2.010333987,2.3946899535,2.4244310674,2.3794199052,2.1231926994]
const D_slow = [0.0,0.0312706553,0.1148921583,0.2646522287,0.4890538312,0.7933098623,1.1135858806,1.3757549179,1.5764879154,1.6858288722]
const D_data = [['2022-05-20', 16.37, 19.64, 16.37, 19.64],['2022-05-23', 21.6, 21.6, 21.6, 21.6],['2022-05-24', 23.76, 23.76, 23.76, 23.76],['2022-05-25', 26.14, 26.14, 26.14, 26.14],['2022-05-26', 28.75, 28.75, 28.75, 28.75],['2022-05-27', 31.63, 31.63, 31.63, 31.63],['2022-05-30', 33.79, 30.61, 30.49, 34.0],['2022-05-31', 27.61, 27.55, 27.55, 27.98],['2022-06-01', 25.61, 27.04, 25.61, 28.9],['2022-06-02', 26.51, 24.61, 24.34, 26.8]]
const W_v = [9528.05,23662.73,501199.0800000001]
const W_histogram = [0.0,0.7651737892,0.7549142361]
const W_fast = [0.0,0.9564672365,1.1349362424]
const W_slow = [0.0,0.1912934473,0.3800220063]
const W_data = [['2022-05-20', 16.37, 19.64, 16.37, 19.64],['2022-05-27', 21.6, 31.63, 21.6, 31.63],['2022-06-02', 33.79, 24.61, 24.34, 34.0]]
const M_v = [259670.36,274719.5]
const M_histogram = [0.0,-0.1876239316]
const M_fast = [0.0,-0.2345299145]
const M_slow = [0.0,-0.0469059829]
const M_data = [['2022-05-31', 16.37, 27.55, 16.37, 34.0],['2022-06-30', 25.61, 24.61, 24.34, 28.9]]
        const D_a = [null,null,null,null,null,null,34.0,null,null,null]
const W_a = [null,null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}