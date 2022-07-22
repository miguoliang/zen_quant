---
title: "思科瑞 - 688053.SH"
date: 2022-07-22T20:22:48+08:00
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
        const D_v = [122234.74,73224.8,60591.3,33504.96,56830.35,29732.73,27661.36,31161.12,22971.46,27627.82,37713.72]
const D_histogram = [0.0,-0.2329344729,-0.0904992654,-0.0257366468,0.2671655375,0.3794967014,0.3087164259,0.4944001595,0.5881009337,0.7417024882,1.1681659831]
const D_fast = [0.0,-0.2911680912,-0.1713577,-0.1130292431,0.2466643256,0.4538696649,0.4602684958,0.7695522693,1.0102782769,1.3493054534,2.0678104441]
const D_slow = [0.0,-0.0582336182,-0.0808584346,-0.0872925963,-0.0205012119,0.0743729634,0.1515520699,0.2751521098,0.4221773432,0.6076029652,0.899644461]
const D_data = [['2022-07-08', 58.0, 53.8, 49.0, 58.0],['2022-07-11', 50.0, 50.15, 48.7, 52.38],['2022-07-12', 50.0, 54.47, 49.98, 55.3],['2022-07-13', 54.4, 54.0, 51.0, 54.66],['2022-07-14', 53.76, 57.92, 53.28, 60.9],['2022-07-15', 58.02, 57.02, 56.6, 59.8],['2022-07-18', 57.11, 55.13, 53.5, 57.38],['2022-07-19', 55.88, 59.01, 55.0, 59.9],['2022-07-20', 59.12, 59.1, 57.75, 60.75],['2022-07-21', 58.13, 61.13, 58.13, 62.3],['2022-07-22', 62.0, 67.0, 61.2, 69.2]]
const W_v = [122234.74,253884.14,147135.48]
const W_histogram = [0.0,0.2054928775,0.9599514809]
const W_fast = [0.0,0.2568660969,1.2513125705]
const W_slow = [0.0,0.0513732194,0.2913610896]
const W_data = [['2022-07-08', 58.0, 53.8, 49.0, 58.0],['2022-07-15', 50.0, 57.02, 48.7, 60.9],['2022-07-22', 57.11, 67.0, 53.5, 69.2]]
const M_v = [523254.36]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 58.0, 67.0, 48.7, 69.2]]
        const D_a = [null,48.7,null,null,null,null,null,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}