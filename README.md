# [查看工单](https://gitcafe.com/2015_SHU_PV_BlueTeam/Tickets/tickets)  
***

## 成员一览： 
- [wolfogre](https://gitcafe.com/wolfogre)/宋建鑫
- [dayang](https://gitcafe.com/dayang)/杨永华
- [zhouwangyiteng](https://gitcafe.com/zhouwangyiteng)/周王翼腾
- [Teemo](https://gitcafe.com/Teemo)/王宇拓
- [Mrwang](https://gitcafe.com/Mrwang)/王舒
- [zhaokuo](https://gitcafe.com/zhaokuo)/方朝增
- [Nicole_lele](https://gitcafe.com/Nicole_lele)/刘懿霆
- [guoxiny](https://gitcafe.com/guoxiny)/郭心怡

## 任务概述（光伏电站优化设计软件20150724.pdf）

### 1.软件功能模块
- ①地理位置选择模块：根据地理位置选定，从数据库（离线或在线）中获取地理位置及对应的历史气象资料。
- ②设备选型与配置模块：从内置主流设备信息的数据库中，根据设计进行设备选型或配置。
- ③优化设计与评估模块：从系统配置角度进行效率的评估来判断优化程度，并推荐优化设计配置。
- ④建造费用评估模块：在生成的设计方案基础上，提供成本建造费用和投资收益的评估模块。
- ⑤设计方案生成模块：根据系统优化设计及投资收益测算结果，打印生成系统设计方案。

### 2.模块具体功能需求

### ①地理位置选择与气象数据获取
- a. 选择地理位置：区域-国家-城市（包括全国各省主要城市）
- b. 查询数据库（离线或在线），获取所设定地理位置的历史太阳辐照度气象数据，给出组件安装倾斜角和方位角设定下的年日照辐射量，以及推荐优化角度设置。
- c. 选取典型日分时发电曲线模型。

### ②设备选型与配置
- a. 选择组件的厂商和组件信息，可从组件信息数据库中获取组件的详细参数信息，且具备自定义功能；
- b. 设置光伏电站的组件数量或总功率；
- c. 选择逆变器的厂商及型号信息，可从逆变器信息数据库中获取逆变器的参数信息，且具备自定义功能；
- d. 根据选型，给出推荐的串并联组件数量的设计结果；
- e. 组件选型和逆变器的匹配核对，并给出优化组件与逆变器最优搭配设计；
- f. 设置输入、输出端所使用线缆材料及施工长度的基本信息，给出线缆的载流情况与损耗分析结果；
- g. 根据需要也可设置升压变压器的参数信息，给出变压器的损耗分析结果。

### ③优化设计与评估
- a. 根据上述选择或配置的信息，进行所选型配置方案下系统效率的计算分析结果；
- b. 软件自带优化设计评估功能，即从系统效率优化的角度给出推荐的配置方案。

### ④电站收益评估
- a. 根据所设计或推荐的配置方案，设定成本建造费用，生成投资成本情况表；
- b. 具备财务分析功能，可设定电站的售电分时电价、政府补贴等信息；
- c. 可计算电站的投资收益，生成评估结果，包括回收期，IRR等指标；
- d. 在选择的典型日分时发电曲线模型基础上，计算电站收益应对应发电量与电价的逐时计算值。

### ⑤设计方案生成与保存
- a. 根据系统优化设计及投资收益的测算结果，可打印生成系统的设计方案；
- b. 工程设计方案可进行项目的新建、保存、导入和导出。



