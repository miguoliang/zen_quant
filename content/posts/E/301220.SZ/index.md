---
title: "C亚香 - 301220.SZ"
date: 2022-06-29T17:11:25+08:00
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
        const D_v = [125310.43,97776.18,66290.45,64814.0,49757.26,43689.08]
const D_histogram = [0.0,-0.29802849,-0.5444675806,-0.5880584626,-0.6572358835,-0.6473431769]
const D_fast = [0.0,-0.3725356125,-0.7550915983,-0.945697096,-1.1791834876,-1.3311265753]
const D_slow = [0.0,-0.0745071225,-0.2106240177,-0.3576386333,-0.5219476042,-0.6837833984]
const D_data = [['2022-06-22', 49.2, 48.98, 48.88, 51.8],['2022-06-23', 45.25, 44.31, 43.51, 45.74],['2022-06-24', 43.39, 43.12, 42.76, 43.99],['2022-06-27', 43.6, 44.38, 43.12, 44.73],['2022-06-28', 43.8, 43.19, 42.99, 43.8],['2022-06-29', 42.81, 43.41, 42.56, 43.82]]
const W_v = [289377.06,158260.34]
const W_histogram = [0.0,0.0185071225]
const W_fast = [0.0,0.0231339031]
const W_slow = [0.0,0.0046267806]
const W_data = [['2022-06-24', 49.2, 43.12, 42.76, 51.8],['2022-07-01', 43.6, 43.41, 42.56, 44.73]]
const M_v = [447637.4]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-06-30', 49.2, 43.41, 42.56, 51.8]]
        const D_a = [null,null,42.76,null,null,null]
const W_a = [null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}