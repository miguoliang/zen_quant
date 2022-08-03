---
title: "国博电子 - 688375.SH"
date: 2022-08-03T20:55:42+08:00
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
        const D_v = [212466.68,112403.67,87698.87,46147.87,54667.87,43317.23,53971.74,37517.82,54805.2]
const D_histogram = [0.0,0.0006381766,0.4860175096,0.7189844798,0.6324742429,0.2479834461,0.7442006854,0.7729934523,0.9516279128]
const D_fast = [0.0,0.0007977208,0.6076814312,1.0203945213,1.0920028452,0.7695079098,1.4517753205,1.6738164505,2.0903578892]
const D_slow = [0.0,0.0001595442,0.1216639216,0.3014100415,0.4595286022,0.5215244637,0.7075746351,0.9008229982,1.1387299764]
const D_data = [['2022-07-22', 94.0, 95.99, 92.55, 100.44],['2022-07-25', 97.0, 96.0, 91.4, 99.51],['2022-07-26', 95.0, 103.6, 95.0, 105.83],['2022-07-27', 102.0, 102.9, 100.03, 105.55],['2022-07-28', 104.0, 99.89, 99.15, 104.97],['2022-07-29', 98.8, 95.3, 94.01, 100.7],['2022-08-01', 95.0, 107.13, 95.0, 109.22],['2022-08-02', 106.5, 103.42, 102.3, 108.49],['2022-08-03', 104.1, 106.7, 102.88, 112.05]]
const W_v = [212466.68,344235.51,146294.76]
const W_histogram = [0.0,-0.044034188,0.6582961112]
const W_fast = [0.0,-0.055042735,0.811861592]
const W_slow = [0.0,-0.011008547,0.1535654808]
const W_data = [['2022-07-22', 94.0, 95.99, 92.55, 100.44],['2022-07-29', 97.0, 95.3, 91.4, 105.83],['2022-08-05', 95.0, 106.7, 95.0, 112.05]]
const M_v = [556702.1899999999,146294.76]
const M_histogram = [0.0,0.7275213675]
const M_fast = [0.0,0.9094017094]
const M_slow = [0.0,0.1818803419]
const M_data = [['2022-07-29', 94.0, 95.3, 91.4, 105.83],['2022-08-31', 95.0, 106.7, 95.0, 112.05]]
        const D_a = [null,91.4,null,null,null,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}