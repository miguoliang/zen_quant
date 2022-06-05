---
title: "观典防务 - 688287.SH"
date: 2022-06-05T10:58:00+08:00
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
        const D_v = [257886.35,231462.46,154937.05,84971.56,198677.43,217001.14,222914.57]
const D_histogram = [0.0,0.0906210826,0.0633296678,0.0055389619,0.0848111444,0.2130958008,0.3585081779]
const D_fast = [0.0,0.1132763533,0.1018173554,0.04541139,0.1458863586,0.3274449652,0.5624843867]
const D_slow = [0.0,0.0226552707,0.0384876876,0.0398724281,0.0610752142,0.1143491644,0.2039762088]
const D_data = [['2022-05-25', 17.5, 16.71, 16.68, 19.7],['2022-05-26', 15.79, 18.13, 15.56, 19.6],['2022-05-27', 17.46, 16.89, 16.44, 17.98],['2022-05-30', 16.8, 16.31, 16.0, 16.8],['2022-05-31', 16.26, 18.13, 16.26, 19.31],['2022-06-01', 17.76, 19.44, 17.6, 20.7],['2022-06-02', 19.58, 20.65, 18.6, 21.05]]
const W_v = [644285.86,723564.7]
const W_histogram = [0.0,0.239954416]
const W_fast = [0.0,0.2999430199]
const W_slow = [0.0,0.059988604]
const W_data = [['2022-05-27', 17.5, 16.89, 15.56, 19.7],['2022-06-02', 16.8, 20.65, 16.0, 21.05]]
const M_v = [927934.8499999999,439915.71]
const M_histogram = [0.0,0.1608205128]
const M_fast = [0.0,0.201025641]
const M_slow = [0.0,0.0402051282]
const M_data = [['2022-05-31', 17.5, 18.13, 15.56, 19.7],['2022-06-30', 17.76, 20.65, 17.6, 21.05]]
        const D_a = [null,15.56,null,null,null,null,null]
const W_a = [null,null]
const M_a = [null,null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}