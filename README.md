# DCIC2021
- 学习课程链接：https://coggle.club/learn/DCIC2021/ 

- 视频讲解链接：https://www.bilibili.com/video/BV1Af4y1C7fv?zw 

- 论坛地址：http://datawhale.club/t/topic/1420
- baseline：https://cdn.coggle.club/dcic2021/DCIC-baseline.html



#### **早高峰共享单车潮汐点的群智优化**

##### 任务描述

- 任务一：根据给定的共享单车数据，识别出工作日早高峰07:00-09:00潮汐现象最突出的40个区域，列出各区域所包含的共享单车停车点位编号名称
- 任务二：根据任务一Top40区域计算结果进一步设计高峰期共享单车潮汐点优化方案，通过主动引导停车用户到邻近停车点位停车，进行削峰填谷，缓解潮汐点停车位（如地铁口）的拥堵问题。（本题涉及的“潮汐现象”聚焦“还不进”的问题，识别出早高峰共享单车最淤积的40个区域）

##### 数据描述

| Description                          | Filename            | Format                                                       |
| ------------------------------------ | ------------------- | ------------------------------------------------------------ |
| **共享单车轨迹数据-1221-1225**       | gxdc_gj202012**.csv | csv: BICYCLE_ID：车辆编码，LOCATING_TIME：定位时间，LATITUDE：纬度（WGS84坐标），LONGITUDE：经度（WGS84坐标） |
| **共享单车停车点位（电子围栏）数据** | gxdc_tcd.csv        | csv: FENCE_ID：电子围栏唯一编号，FENCE_LOC：电子围栏位置坐标串（包括电子围栏所在位置四个顶点的坐标信息，WGS84坐标） |
| **共享单车订单数据**                 | gxdc_dd.csv         | csv: BICYCLE_ID：车辆编码，LATITUDE：纬度（WGS84坐标），LONGITUDE：经度（WGS84坐标），LOCK_STATUS：锁的状态（0-开锁，1-关锁），UPDATE_TIME：锁状态更新时间 |

##### 任务分析



##### 提交记录

![](https://github.com/LiuXiangYuan/DCIC2021/blob/main/pictures/result.png)

##### baseline 分析

