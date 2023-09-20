# 航天器系统仿真软件SpaceSim

# 一、SpaceSim软件介绍

航天器系统仿真软件SpaceSim是一款诞生于哈尔滨工业大学、依托航天科研院所支持、完全国产的航天器系统仿真软件。航天器系统仿真软件SpaceSim入选2023版科技创新成果推荐目录，并以工信部十四五规划教材《航天器系统仿真技术》作为软件配套教材。

SpaceSim软件能够支持航天器姿态轨道动力学与控制、导航星座设计与信号特性、通信卫星覆盖及干扰特性、空间光学遥感成像、星座任务规划与调度、空间博弈对抗等系统仿真，涵盖航天器设计、测试、发射、运行和任务应用等各个阶段，已成功应用于高校教学、科研院所及国防单位的工程任务，正逐渐在教学实践、型号设计、体系应用、评估演训等领域发挥重要作用。

<div align=middle><img src="http://118.195.139.164:8000/spacesim_ims/main_page/clip_image001.png" alt="img" style="zoom:80%;" /></div>

<center>图 1 航天器系统仿真软件SpaceSim</center>

<div align=middle><img src="http://118.195.139.164:8000/spacesim_ims/main_page/clip_image003.jpg" alt="教材封面" style="zoom:100%;" /></div>

<center>图 2 《航天器系统仿真技术》教材图片</center>

# 二、SpaceSim主要功能

软件模块组成如下图所示。

<div align=middle><img src="http://118.195.139.164:8000/spacesim_ims/main_page/clip_image005.jpg" alt="软件模块组成图-初稿" style="zoom:100%;" /></div>

<center>图 3 SpaceSim软件模块组成图</center>

**具体功能包括：**

①**轨道递推**——提供多种轨道递推模型，包括理想二体（可单独考虑J2、J4摄动）、SGP4轨道运动模型和高精度轨道动力学模型HPOP等，可实现万级规模航天器同时在轨运行仿真；

②**轨道机动**——提供基于指令驱动的异面变轨功能，包括Lambert变轨策略自动计算模块，适用于卫星在轨运行中的即时变轨；

③**装备建模**——提供星座设计与管理功能，提供多卫星TLE双行元文件批量导入功能，支持空天装备（卫星、导弹、火箭、飞机、舰船、地面站等）的实体模型导入；

④**空间环境**——提供大气、地磁、辐射带、等离子体、原子氧等空间环境基础模型；

⑤**通信载荷**——提供通信天线指向计算、信号特性、覆盖特性、干扰特性、星间链路、动态路由等分析模型，支持天线方向图GRD导入；

⑥**导航载荷**——提供导航接收机、导航星设置、几何精度因子、定位误差计算、导航星优选等功能；

⑦**遥感载荷**——提供光学、SAR等遥感载荷的成像模拟功能，支持高精度瓦片地图；

⑧**数据接口**——提供TCP、UDP等远程通讯数据交互功能，支持Matlab、Python、MBSE等第三方软件接口；

⑨**二次开发**——支持类库级二次开发，能够支持大规模空天装备异构网络自主管控、通导遥协同智能应用、星群轨道博弈、星座协同对地搜索观测、空天智能算法的试训、评估与轻量化迁移等航天任务或地空天应用任务的仿真分析。

# 三、SpaceSim软件特点

①轨道模型采用递推计算，而非预运算方式，采用指令驱动，在轨道机动仿真方面具有显著优势；

②实现基于GPU的轨道推演与通信特性计算，支持万颗以上航天器同时在轨运行，适合超大规模星座的轨道推演、通信覆盖等仿真；

③成像模拟功能，可为光学遥感载荷设计、图像畸变矫正算法验证等提供仿真支持环境；

④与Matlab、Python、MBSE等第三方软件接口实现双向数据打通，无需通过其他软件中转数据；

⑤软件功能库与界面独立开发，支持用户自有界面与渲染；

⑥依托工程需求开发，功能精炼、用途明确、人机交互简易；

⑦软件基于C++开发，具有完全自主的知识产权，完全国产，支持Windows、Linux、麒麟等操作系统。

 

# 四、SpaceSim典型应用案例

<div align=middle><img src="https://pic.imgdb.cn/item/650a906cc458853aef58f7a8.gif" alt="img" style="zoom:100%;" /></div>

<center>图 4 万颗卫星仿真</center>

<div align=middle><img src="https://pic.imgdb.cn/item/650a901dc458853aef58e796.gif" alt="img" style="zoom:100%;" /></div>

<center>图 5 跨域通信仿真</center>

<div align=middle><img src="http://118.195.139.164:8000/spacesim_ims/main_page/6-动态路由.gif" alt="img" style="zoom:100%;" /></div>

<center>图 6 动态路由仿真</center>

<div align=middle><img src="http://118.195.139.164:8000/spacesim_ims/main_page/7-抗干扰.gif" alt="img" style="zoom:100%;" /></div>

<center>图 7 抗干扰特性仿真</center>

<div align=middle><img src="http://118.195.139.164:8000/spacesim_ims/main_page/8-星座设计与导航.gif" alt="img" style="zoom:100%;" /></div>

<center>图 8 星座设计与导航仿真</center>

<div align=middle><img src="http://118.195.139.164:8000/spacesim_ims/main_page/9-遥感成像仿真.gif" alt="img" style="zoom:100%;" /></div>

<center>图 9 遥感成像仿真</center>

<div align=middle><img src="http://118.195.139.164:8000/spacesim_ims/main_page/10-弹道导弹.gif" alt="img" style="zoom:100%;" /></div>

<center>图 10 弹道导弹仿真</center>

<div align=middle><img src="http://118.195.139.164:8000/spacesim_ims/main_page/11-天基预警.gif" alt="img" style="zoom:100%;" /></div>

<center>图 11 天基预警仿真</center>

# 五、SpaceSim软件基础功能案例列表

| 序号 | 案例名称                   | 案例代号                       |
| ---- | -------------------------- | ------------------------------ |
| 1.   | 高中低轨道仿真             | Demo_0101_Orbit_Basic          |
| 2.   | 地球同步静止轨道           | Demo_0102_Orbit_GEO            |
| 3.   | 两体模型与HPOP模型精度对比 | Demo_0103_Orbit_ModelCom       |
| 4.   | 太阳同步轨道设计及仿真     | Demo_0104_Orbit_SunSyn         |
| 5.   | 闪电轨道设计及仿真         | Demo_0105_Orbit_FrozenMolniya  |
| 6.   | 冻结轨道设计及仿真         | Demo_0106_Orbit_FrozenSeasat1  |
| 7.   | 冻结轨道近地点幅角对比     | Demo_0107_Orbit_FrozenOmegaCom |
| 8.   | 回归轨道设计及仿真         | Demo_0108_Orbit_Repeat         |
| 9.   | 单脉冲轨道机动仿真         | Demo_0201_Trans_Monopulse      |
| 10.  | 霍曼转移仿真               | Demo_0202_Trans_Hohmann        |
| 11.  | 双椭圆三脉冲变轨仿真       | Demo_0203_Trans_DoubleEllipse  |
| 12.  | 相位调整仿真               | Demo_0204_Trans_PhaseAdjust    |
| 13.  | 异面转移仿真               | Demo_0205_Trans_DiffPlane      |
| 14.  | 兰伯特转移仿真             | Demo_0206_Trans_Lambert        |
| 15.  | 姿态机动仿真               | Demo_0301_Atti_DirSunEarth     |
| 16.  | 不同轨道高度大气环境仿真   | Demo_0401_Envi_Atmo_DiffAlti   |
| 17.  | 不同轨道倾角大气环境仿真   | Demo_0402_Envi_Atmo_DiffAngle  |
| 18.  | 地磁场环境仿真             | Demo_0403_Envi_Magni           |
| 19.  | 辐射带仿真                 | Demo_0404_Envi_Radi            |
| 20.  | 空间碎片仿真               | Demo_0405_Envi_Debris          |
| 21.  | 碰撞预警仿真               | Demo_0406_Envi_CollisionTest   |
| 22.  | 导弹弹道仿真               | Demo_0501_Missile_GroundTarget |
| 23.  | 导弹快速交会仿真           | Demo_0502_Missile_SpaceTarget  |
| 24.  | 火箭运载仿真               | Demo_0503_Rocket_Launch        |
| 25.  | 天线指向覆盖仿真           | Demo_0601_ANT_Cover            |
| 26.  | 天线指向控制仿真           | Demo_0602_ANT_PointCtrl        |
| 27.  | 通信干扰仿真               | Demo_0603_ANT_CommDisturb      |
| 28.  | Walker星座搭建以及路由仿真 | Demo_0701_Route_Walker         |
| 29.  | Walker星座导航仿真         | Demo_0702_Navi_Walker          |
| 30.  | GPS导航仿真                | Demo_0703_Navi_GPS             |
| 31.  | Glonass导航仿真            | Demo_0704_Navi_Glonass         |
| 32.  | Galileo导航仿真            | Demo_0705_Navi_Galileo         |
| 33.  | 北斗导航仿真               | Demo_0706_Navi_Beidou          |
| 34.  | GPS与北斗联合导航仿真      | Demo_0707_Navi_GPSBeidou       |
| 35.  | 印度IRNSS导航仿真          | Demo_0708_Navi_IRNSS           |
| 36.  | 覆盖效能仿真               | Demo_0801_CoverEffi            |
| 37.  | 遥感卫星对地成像仿真       | Demo_0802_RS_ImageBasic        |
| 38.  | 遥感卫星成像控制仿真       | Demo_0803_RS_ImageCtrl         |
| 39.  | 侦察与跟踪仿真             | Demo_0804_RS_Inspect           |
| 40.  | 天基观测目标仿真           | Demo_0805_RS_SpaceObserve      |

 

# 六、SpaceSim软件获取及联系方式

航天器系统仿真软件SpaceSim 下载方式：

链接：https://pan.baidu.com/s/11Z4A2woKym-8pEiP0Kkctg

提取码：2023

 

软件官网：

https://spacesim.readthedocs.io/en/latest/

 

联系人：[刘天喜，13796055084，liutianxi@hit.edu.cn](mailto:刘天喜，13796055084，liutianxi@hit.edu.cn)

#  使用手册：

具体的案例，软件使用详细手册请参考[使用手册](page/SpaceSim_userguide_example_internet.md) 

#  END