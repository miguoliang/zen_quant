---
title: "智立方 - 301312.SZ"
date: 2022-07-22T20:28:32+08:00
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
        const D_v = [53238.24,40066.55,22552.21,24540.27,31257.1,21861.37,18250.42,24260.2,31092.9,32160.52]
const D_histogram = [0.0,-0.2335726496,-0.6160837266,-0.7029007388,-0.5886566459,-0.6376653247,-0.702012231,-0.4117061947,-0.152068588,0.3392877322]
const D_fast = [0.0,-0.291965812,-0.8284978206,-1.0910400175,-1.1239600861,-1.3323850961,-1.5722350601,-1.3848555725,-1.1632351128,-0.5870568596]
const D_slow = [0.0,-0.0583931624,-0.212414094,-0.3881392787,-0.5353034402,-0.6947197714,-0.8702228291,-0.9731493778,-1.0111665248,-0.9263445918]
const D_data = [['2022-07-11', 100.0, 86.99, 86.84, 105.0],['2022-07-12', 80.8, 83.33, 78.0, 85.43],['2022-07-13', 80.15, 79.43, 79.0, 81.98],['2022-07-14', 78.5, 81.29, 78.13, 83.31],['2022-07-15', 81.58, 83.3, 81.0, 88.85],['2022-07-18', 81.7, 80.85, 78.8, 81.7],['2022-07-19', 80.0, 79.7, 78.69, 80.77],['2022-07-20', 79.84, 84.18, 79.7, 84.28],['2022-07-21', 83.74, 84.92, 82.71, 88.85],['2022-07-22', 84.02, 89.8, 83.0, 92.0]]
const W_v = [171654.37,127625.41]
const W_histogram = [0.0,0.4148148148]
const W_fast = [0.0,0.5185185185]
const W_slow = [0.0,0.1037037037]
const W_data = [['2022-07-15', 100.0, 83.3, 78.0, 105.0],['2022-07-22', 81.7, 89.8, 78.69, 92.0]]
const M_v = [299279.78]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 100.0, 89.8, 78.0, 105.0]]
        const D_a = [null,78.0,null,null,null,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}