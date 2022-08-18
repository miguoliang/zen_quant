---
title: "C海光 - 688041.SH"
date: 2022-08-18T20:21:25+08:00
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
        const D_v = [1191336.25,594756.3,452262.22,309650.39,203799.82]
const D_histogram = [0.0,-0.2093219373,-0.0820964245,-0.1920299809,-0.2491276222]
const D_fast = [0.0,-0.2616524217,-0.154951015,-0.3128920666,-0.4322716134]
const D_slow = [0.0,-0.0523304843,-0.0728545905,-0.1208620857,-0.1831439912]
const D_data = [['2022-08-12', 70.0, 60.1, 60.1, 73.8],['2022-08-15', 57.0, 56.82, 56.7, 61.19],['2022-08-16', 56.0, 60.69, 55.01, 61.66],['2022-08-17', 60.35, 57.64, 56.8, 61.86],['2022-08-18', 57.02, 57.65, 55.5, 58.79]]
const W_v = [1191336.25,1560468.7300000002]
const W_histogram = [0.0,-0.1563532764]
const W_fast = [0.0,-0.1954415954]
const W_slow = [0.0,-0.0390883191]
const W_data = [['2022-08-12', 70.0, 60.1, 60.1, 73.8],['2022-08-19', 57.0, 57.65, 55.01, 61.86]]
const M_v = [2751804.98]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 70.0, 57.65, 55.01, 73.8]]
        const D_a = [null,null,55.01,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}