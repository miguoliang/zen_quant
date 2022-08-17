---
title: "快可电子 - 301278.SZ"
date: 2022-08-17T20:34:43+08:00
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
        const D_v = [120736.34,99964.73,63562.29,73116.86,56333.35,47718.7,47536.34,41300.07,45543.29,69435.34]
const D_histogram = [0.0,-1.6030997151,-2.5176479282,-2.4529963239,-2.3729237299,-2.4791713041,-2.9768836777,-2.6404730918,-2.0353745437,-0.5339858587]
const D_fast = [0.0,-2.0038746439,-3.547834839,-4.0964323157,-4.6095906542,-5.3356310544,-6.5775643474,-6.9012720345,-6.8050171223,-5.437124902]
const D_slow = [0.0,-0.4007749288,-1.0301869108,-1.6434359918,-2.2366669243,-2.8564597503,-3.6006806697,-4.2607989427,-4.7696425786,-4.9031390433]
const D_data = [['2022-08-04', 90.0, 128.01, 88.18, 144.0],['2022-08-05', 105.33, 102.89, 102.0, 122.79],['2022-08-08', 96.88, 102.93, 94.56, 107.14],['2022-08-09', 100.0, 110.71, 99.09, 118.45],['2022-08-10', 105.46, 109.08, 103.11, 114.88],['2022-08-11', 112.0, 104.36, 103.5, 113.0],['2022-08-12', 102.99, 95.16, 95.01, 103.6],['2022-08-15', 93.3, 102.36, 93.3, 102.81],['2022-08-16', 101.0, 105.76, 100.89, 108.0],['2022-08-17', 107.0, 120.99, 106.11, 126.0]]
const W_v = [220701.07,288267.54,156278.7]
const W_histogram = [0.0,-0.4933105413,0.8728867331]
const W_fast = [0.0,-0.6166381766,0.967780781]
const W_slow = [0.0,-0.1233276353,0.0948940479]
const W_data = [['2022-08-05', 90.0, 102.89, 88.18, 144.0],['2022-08-12', 96.88, 95.16, 94.56, 118.45],['2022-08-19', 93.3, 120.99, 93.3, 126.0]]
const M_v = [665247.3099999999]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 90.0, 120.99, 88.18, 144.0]]
        const D_a = [null,null,null,null,null,null,null,93.3,null,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}