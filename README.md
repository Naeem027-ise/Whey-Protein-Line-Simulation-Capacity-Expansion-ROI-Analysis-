### A two-shift whey-protein factory was plagued by long queues at preparation, weighing, and mixing stations—especially when mixers had to stop for flavor-change sanitation—constraining throughput and profit. 

Goal: Quantify bottlenecks and recommend practical changes that cut waiting lines and raise annual profit, while validating any proposed system against real factory data. 

### Solution Approach (high-level)
Built and validated a discrete-event simulation of the current line in Simio using manager-supplied distributions.

Ran scenario experiments:
Capital investment: tested adding a third weighing station and a fourth mixer.
Process change: dedicated one mixer to chocolate and the others to vanilla to eliminate sanitation downtime.
Resource allocation: evaluated extra prep-station labor.

Compared scenarios with T-tests and ROI analysis; the best option (add weighing + mixing stations and dedicate flavors) cut queues, lifted yearly profit 24 % ($416 k → $519 k), and paid back the $135 k investment in ~13 weeks. 
