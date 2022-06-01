---
title: "C菲菱 - 301191.SZ"
date: 2022-06-01T20:46:53+08:00
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
        const D_v = [76789.79,62011.32,31240.86,41637.41,41365.89]
const D_histogram = [0.0,-0.7217777778,-1.2329714467,-1.2424191195,-1.3303628276]
const D_fast = [0.0,-0.9022222222,-1.7216587528,-2.0417112054,-2.4622456204]
const D_slow = [0.0,-0.1804444444,-0.4886873061,-0.799292086,-1.1318827929]
const D_data = [['2022-05-26', 94.0, 90.02, 90.0, 105.13],['2022-05-27', 85.96, 78.71, 78.38, 86.6],['2022-05-30', 77.0, 77.17, 76.03, 79.2],['2022-05-31', 77.0, 80.96, 76.6, 82.9],['2022-06-01', 80.0, 78.54, 78.5, 83.85]]
const W_v = [138801.11,114244.16]
const W_histogram = [0.0,-0.0108490028]
const W_fast = [0.0,-0.0135612536]
const W_slow = [0.0,-0.0027122507]
const W_data = [['2022-05-27', 94.0, 78.71, 78.38, 105.13],['2022-06-02', 77.0, 78.54, 76.03, 83.85]]
const M_v = [211679.38,41365.89]
const M_histogram = [0.0,-0.1544387464]
const M_fast = [0.0,-0.193048433]
const M_slow = [0.0,-0.0386096866]
const M_data = [['2022-05-31', 94.0, 80.96, 76.03, 105.13],['2022-06-30', 80.0, 78.54, 78.5, 83.85]]
        const D_a = [null,null,76.03,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}