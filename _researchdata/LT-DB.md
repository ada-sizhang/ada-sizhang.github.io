---
title: "Low-thrust trajectories: For Deep Learning Model Construction"
collection: researchdata
type: ".MAT format"
permalink: /researchdata/LT-DB
venue: "Journals"
date: 2021-03-01
---

This database stores randomly generated low-thrust(LT) trajectories between NEAs. This database can be used for training interesting machine learning models. For example, using both feasible LT samples and infeasible samples to build a DNN classification model to distinguish LT transfer feasibilities. This database is valuable – obtaining such database requires hundreds of thousands of cores hours of high-performance computing system.

## Database Summary

| Item                            | Description                                                                         |
|---------------------------------|-------------------------------------------------------------------------------------|
| Number of feasible trajectories | 300,000                                                                             |
| Number of feasible trajectories | 2,000,000                                                                           |
| File Format                     | .MAT                                                                                |
| File Size                       | 3 GB                                                                                |
| Precision                       | double-precision floating-point                                                     |
| Columns                         | exitflag, SPK1, SPK2, depart date, tof, spacecraft mass, PV1, PV2, Control Vectors  |

## Statistical

|        | Time of flight (days) | Initial Mass (KG) | Lambert Delta-V (KM/S) |
|--------|-----------------------|-------------------|------------------------|
| Min    | 126                   | 1053              | 0.15                   |
| Max    | 1460                  | 3000              | 116.27                 |
| Mean   | 875.9                 | 1830.5            | 45.00                  |
| Median | 883                   | 1732              | 41.65                  |

![DB3-stats1](/images/DB3-stats1.png "DB3-stats1")
![DB3-stats2](/images/DB3-stats2.png "DB3-stats2")
![DB3-stats3](/images/DB3-stats3.png "DB3-stats3")

## Download Link
The link will be released later. Contact: ruida.space@gmail.com
