# Network Architecture Search (NAS)

> - Method [Type/Venue] Name+link: introduction


### 2020
- **SGAS [Gradient/CVPR]** [SGAS: Sequential Greedy Architecture Search](https://www.deepgcns.org/auto/sgas): 基于[DARTS](#DARTS)框架,使用贪心的方式来搜索局部最优的architecture, 可以用于CNN和GCN. 事先定义好多少层feature,然后搜索的是feature之间的*卷积类型*或者是*skip-connection*, 并不涉及到architecture的大小扩增.

### 2019
- <span id="DARTS"> **DARTS [Gradient/ICLR]** [DARTS: Differentiable Architecture Search](https://openreview.net/pdf?id=S1eYHoC5FX):