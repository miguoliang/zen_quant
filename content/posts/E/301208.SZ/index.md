---
title: "中亦科技 - 301208.SZ"
date: 2022-07-14T20:25:27+08:00
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
        const D_v = [86002.98,63459.37,32813.03,30146.85,22190.62,23176.58]
const D_histogram = [0.0,-0.4933105413,-0.8865662584,-0.9960008372,-1.0899281586,-1.0518560446]
const D_fast = [0.0,-0.6166381766,-1.2315354583,-1.5899702464,-1.9563796075,-2.1812715046]
const D_slow = [0.0,-0.1233276353,-0.3449691999,-0.5939694092,-0.8664514489,-1.12941546]
const D_data = [['2022-07-07', 61.1, 56.4, 56.3, 63.3],['2022-07-08', 51.97, 48.67, 48.58, 51.99],['2022-07-11', 48.0, 46.93, 46.59, 48.0],['2022-07-12', 46.68, 48.3, 46.59, 48.65],['2022-07-13', 47.7, 47.0, 46.7, 47.72],['2022-07-14', 46.7, 47.5, 46.7, 48.09]]
const W_v = [149462.35,108327.08]
const W_histogram = [0.0,-0.0746666667]
const W_fast = [0.0,-0.0933333333]
const W_slow = [0.0,-0.0186666667]
const W_data = [['2022-07-08', 61.1, 48.67, 48.58, 63.3],['2022-07-15', 48.0, 47.5, 46.59, 48.65]]
const M_v = [257789.43]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-07-29', 61.1, 47.5, 46.59, 63.3]]
        const D_a = [null,null,46.59,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}