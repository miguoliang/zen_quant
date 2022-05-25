---
title: "铭科精技 - 001319.SZ"
date: 2022-05-25T17:15:33+08:00
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
        const D_v = [13423.89,2313.82,3327.66,3969.77,3300.77,13306.33,26203.79,288934.3,272609.66,205772.51]
const D_histogram = [0.0,0.1365698006,0.3653083076,0.6536709748,0.9793912072,1.3277265368,1.6887335761,2.0572456288,1.9552639057,1.5222611625]
const D_fast = [0.0,0.1707122507,0.4907778346,0.9425582455,1.5131262797,2.1933932436,2.9765836768,3.8594071368,4.2462413901,4.1938039375]
const D_slow = [0.0,0.0341424501,0.125469527,0.2888872707,0.5337350725,0.8656667067,1.2878501008,1.802161508,2.2909774844,2.671542775]
const D_data = [['2022-05-12', 17.87, 21.44, 17.87, 21.44],['2022-05-13', 23.58, 23.58, 23.58, 23.58],['2022-05-16', 25.94, 25.94, 25.94, 25.94],['2022-05-17', 28.53, 28.53, 28.53, 28.53],['2022-05-18', 31.38, 31.38, 31.38, 31.38],['2022-05-19', 34.52, 34.52, 34.52, 34.52],['2022-05-20', 37.97, 37.97, 37.97, 37.97],['2022-05-23', 40.69, 41.77, 39.15, 41.77],['2022-05-24', 41.0, 38.5, 37.65, 44.5],['2022-05-25', 34.65, 34.65, 34.65, 36.67]]
const W_v = [15737.71,50108.32,767316.47]
const W_histogram = [0.0,0.9183361823,1.2318230923]
const W_fast = [0.0,1.1479202279,1.769362911]
const W_slow = [0.0,0.2295840456,0.5375398187]
const W_data = [['2022-05-13', 17.87, 23.58, 17.87, 23.58],['2022-05-20', 25.94, 37.97, 25.94, 37.97],['2022-05-27', 40.69, 34.65, 34.65, 44.5]]
const M_v = [833162.5]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-05-31', 17.87, 34.65, 17.87, 44.5]]
        const D_a = [null,null,null,null,null,null,null,null,44.5,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}