---
title: "菲菱科思 - 301191.SZ"
date: 2022-06-07T16:14:53+08:00
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
        const D_v = [76789.79,62011.32,31240.86,41637.41,41365.89,38633.22,37376.24,30027.53]
const D_histogram = [0.0,-0.7217777778,-1.2329714467,-1.2424191195,-1.3303628276,-1.1535392231,-0.8544190777,-0.7999799479]
const D_fast = [0.0,-0.9022222222,-1.7216587528,-2.0417112054,-2.4622456204,-2.5738068217,-2.4882914458,-2.6338473029]
const D_slow = [0.0,-0.1804444444,-0.4886873061,-0.799292086,-1.1318827929,-1.4202675986,-1.6338723681,-1.833867355]
const D_data = [['2022-05-26', 94.0, 90.02, 90.0, 105.13],['2022-05-27', 85.96, 78.71, 78.38, 86.6],['2022-05-30', 77.0, 77.17, 76.03, 79.2],['2022-05-31', 77.0, 80.96, 76.6, 82.9],['2022-06-01', 80.0, 78.54, 78.5, 83.85],['2022-06-02', 78.0, 80.92, 76.2, 81.88],['2022-06-06', 79.86, 82.72, 79.0, 84.6],['2022-06-07', 82.72, 79.7, 79.41, 84.27]]
const W_v = [138801.11,152877.38,67403.77]
const W_histogram = [0.0,0.141037037,0.1438639232]
const W_fast = [0.0,0.1762962963,0.2150891632]
const W_slow = [0.0,0.0352592593,0.0712252401]
const W_data = [['2022-05-27', 94.0, 78.71, 78.38, 105.13],['2022-06-02', 77.0, 80.92, 76.03, 83.85],['2022-06-10', 79.86, 79.7, 79.0, 84.6]]
const M_v = [211679.38,147402.88]
const M_histogram = [0.0,-0.0804102564]
const M_fast = [0.0,-0.1005128205]
const M_slow = [0.0,-0.0201025641]
const M_data = [['2022-05-31', 94.0, 80.96, 76.03, 105.13],['2022-06-30', 80.0, 79.7, 76.2, 84.6]]
        const D_a = [null,null,76.03,null,null,null,null,null]
const W_a = [null,76.03,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}