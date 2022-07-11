---
title: "中无人机 - 688297.SH"
date: 2022-07-11T23:08:51+08:00
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
        const D_v = [889932.4,444860.19,400302.91,239863.13,309968.65,184363.6,230048.78,140851.6,184336.42]
const D_histogram = [0.0,-0.2437834758,-0.279224279,-0.2677395035,-0.1004755283,-0.0298208203,-0.156095539,-0.2928891826,-0.604574134]
const D_fast = [0.0,-0.3047293447,-0.4099762177,-0.465426318,-0.3232812249,-0.260081722,-0.4253803255,-0.6353962647,-1.0982247496]
const D_slow = [0.0,-0.0609458689,-0.1307519387,-0.1976868146,-0.2228056966,-0.2302609017,-0.2692847865,-0.3425070821,-0.4936506156]
const D_data = [['2022-06-29', 50.43, 57.0, 50.2, 57.53],['2022-06-30', 54.5, 53.18, 52.55, 55.8],['2022-07-01', 52.9, 54.81, 52.12, 57.6],['2022-07-04', 53.8, 55.09, 53.15, 56.99],['2022-07-05', 54.8, 57.35, 53.75, 59.57],['2022-07-06', 57.0, 56.7, 55.61, 57.7],['2022-07-07', 56.69, 53.97, 53.66, 58.19],['2022-07-08', 53.0, 52.9, 52.5, 54.48],['2022-07-11', 52.99, 49.07, 48.72, 53.11]]
const W_v = [1735095.5,1105095.76,184336.42]
const W_histogram = [0.0,-0.1218917379,-0.4360451879]
const W_fast = [0.0,-0.1523646724,-0.5755294194]
const W_slow = [0.0,-0.0304729345,-0.1394842315]
const W_data = [['2022-07-01', 50.43, 54.81, 50.2, 57.6],['2022-07-08', 53.8, 52.9, 52.5, 59.57],['2022-07-15', 52.99, 49.07, 48.72, 53.11]]
const M_v = [1334792.5900000001,1689735.0900000001]
const M_histogram = [0.0,-0.2622905983]
const M_fast = [0.0,-0.3278632479]
const M_slow = [0.0,-0.0655726496]
const M_data = [['2022-06-30', 50.43, 53.18, 50.2, 57.53],['2022-07-29', 52.9, 49.07, 48.72, 59.57]]
        const D_a = [null,null,null,null,59.57,null,null,null,null]
const W_a = [null,59.57,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}