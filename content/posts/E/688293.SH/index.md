---
title: "奥浦迈 - 688293.SH"
date: 2022-09-15T20:43:49+08:00
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
        const D_v = [124348.97,87280.66,47108.06,27485.47,47353.44,21504.33,25302.53,21349.42,15330.1]
const D_histogram = [0.0,-0.7811282051,-1.0339901527,-1.0282013064,-0.5825628279,-0.4359294169,-0.3761861085,0.175653637,0.2280256956]
const D_fast = [0.0,-0.9764102564,-1.4877697421,-1.7390312225,-1.439033451,-1.4013823941,-1.4356856129,-0.8399324582,-0.7305539756]
const D_slow = [0.0,-0.1952820513,-0.4537795895,-0.7108299161,-0.856470623,-0.9654529773,-1.0594995044,-1.0155860951,-0.9585796712]
const D_data = [['2022-09-02', 125.0, 127.24, 122.28, 134.05],['2022-09-05', 127.2, 115.0, 111.16, 131.5],['2022-09-06', 111.99, 118.04, 108.0, 121.0],['2022-09-07', 116.99, 119.7, 116.4, 123.56],['2022-09-08', 122.88, 125.68, 118.89, 128.0],['2022-09-09', 123.59, 123.0, 121.0, 126.72],['2022-09-13', 125.0, 122.0, 120.1, 133.17],['2022-09-14', 119.82, 129.6, 118.34, 130.6],['2022-09-15', 128.03, 125.0, 123.2, 132.0]]
const W_v = [124348.97,230731.96,61982.05]
const W_histogram = [0.0,-0.2705868946,-0.2977488559]
const W_fast = [0.0,-0.3382336182,-0.4398327936]
const W_slow = [0.0,-0.0676467236,-0.1420839376]
const W_data = [['2022-09-02', 125.0, 127.24, 122.28, 134.05],['2022-09-09', 127.2, 123.0, 108.0, 131.5],['2022-09-16', 125.0, 125.0, 118.34, 133.17]]
const M_v = [417062.98]
const M_histogram = [0.0]
const M_fast = [0.0]
const M_slow = [0.0]
const M_data = [['2022-09-30', 125.0, 125.0, 108.0, 134.05]]
        const D_a = [null,null,108.0,null,null,null,null,null,null]
const W_a = [null,108.0,null]
const M_a = [null]
        const D_b = []
const W_b = []
const M_b = []
    </script>
{{< /rawhtml >}}