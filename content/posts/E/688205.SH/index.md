---
title: "德科立 - 688205.SH"
date: 2022-08-23T21:59:37+08:00
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
        const D_v = [148905.28,97419.14,86700.72,77812.71,47978.23,32077.05,31710.27,29015.52,43676.31,25363.22,16887.83]
const D_histogram = [0.0,-0.29802849,-0.319829404,-0.594840953,-0.8908959621,-1.0651658779,-1.1311183587,-1.0644319335,-0.9437595406,-0.8955328785,-0.8051324416]
const D_fast = [0.0,-0.3725356125,-0.4742938775,-0.8980156648,-1.4167946644,-1.8573560497,-2.2060881202,-2.4055096783,-2.5207771706,-2.6964337281,-2.8073164016]
const D_slow = [0.0,-0.0745071225,-0.1544644735,-0.3031747118,-0.5258987023,-0.7921901718,-1.0749697614,-1.3410777448,-1.57701763,-1.8009008496,-2.00218396]
const D_data = [['2022-08-09', 60.5, 61.02, 60.05, 69.0],['2022-08-10', 58.0, 56.35, 54.03, 59.15],['2022-08-11', 55.91, 58.68, 55.87, 60.87],['2022-08-12', 58.0, 54.3, 54.2, 60.35],['2022-08-15', 53.0, 51.83, 50.99, 53.22],['2022-08-16', 52.02, 51.2, 50.96, 52.3],['2022-08-17', 51.2, 50.89, 49.66, 51.39],['2022-08-18', 50.6, 51.5, 50.45, 52.18],['2022-08-19', 51.75, 51.67, 51.67, 54.11],['2022-08-22', 51.95, 50.24, 49.7, 53.15],['2022-08-23', 50.1, 50.19, 49.5, 50.85]]
const W_v = [410837.85,184457.38,42251.05]
const W_histogram = [0.0,-0.1678404558,-0.358308728]
const W_fast = [0.0,-0.2098005698,-0.489846024]
const W_slow = [0.0,-0.041960114,-0.131537296]
const W_data = [['2022-08-12', 60.5, 54.3, 54.03, 69.0],['2022-08-19', 53.0, 51.67, 49.66, 54.11],['2022-08-26', 51.95, 50.19, 49.5, 53.15]]
const M_v = [637546.2799999999]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-08-31', 60.5, 50.19, 49.5, 69.0]]
        const D_a = [null,null,null,null,null,null,49.66,null,null,null,null]
const W_a = [null,null,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}