 <center>
     <h1>郭超</h1>
     <h3>18220052953 | Guochao_net@163.com | 深圳 | 26</h3>
 </center>

>## **工作及教育经历**
***
**金蝶天燕云计算服份有限公司&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2019.07~至今&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;中间件产品部**
+ 荣誉和奖励：金蝶天燕十佳员工(优秀新人)、金蝶集团微创新奖(3%)、金蝶集团发明专利奖两项

**西安邮电大学&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2015.09~2019.07&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;网络工程专业-本科**
+ 荣誉和奖励：国家奖学金(专业第一)、国家励志奖学金(专业第二)、优秀班干部等
>## **专业技能**
***
* 扎实的Go语言基础，熟悉Go语言底层设计原理，包括调度模型GPM、内存管理(堆、函数调用栈、GC)、类型系统(接口、类型断言、Reflect)、Channel、Mutex、Map及其他数据结构、Defer等，熟悉Gin等web开发组件
* 熟悉计算机网络，熟悉OSI参考模型、IP、TCP、HTTP(HTTPS)等，了解DNS、ARP、NAT等
* 熟悉网络编程、IO多路复用
* 熟悉Mysql，了解索引、事务、日志系统
* 熟悉Redis，熟悉事件循环机制、哨兵底层原理，熟悉基本数据结构
* 熟悉Linux，能编写Shell脚本，了解Linux下常用命令与工具，了解Git
* 熟悉常见的数据结构与算法，了解计算机组成原理、操作系统
* 了解Python语言、C语言
* 了解nginx、lvs、keepalived
* 了解Docker，了解Docker实现机制，了解Dockerfile，了解Kubernetes，了解gRPC
>## **项目经历**
***
 &emsp;&emsp;多个项目有多个阶段，所以时间上有重叠
+ **金蝶天燕内存数据缓存&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2021.07~2022.09&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;后端设计及开发**
    * 具体功能 
    * 运用了那些技术，技术难点是
    * 效果如何
    * demo演示地址，github地址 
+ **金蝶天燕负载均衡器多实例管控台&emsp;&emsp;&emsp;2022.05~2022.07&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;后端独立设计及开发**
+ **金蝶天燕负载均衡器&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2021.01~2022.03&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;后端设计及开发**

+ **金蝶天燕数据服务&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2020.09~2020.12&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;后端独立设计及开发**  
&emsp;&emsp;数据服务可以将多源数据库数据通过处理后以RESTful API形式发布为数据API。功能类似于阿里DataWorks的数据服务模块。可以通过向导或SQL的形式创建API，支持SQL where语句中常见的各种操作符以及排序分页等功能。  
**主要技术**：Python、FastAPI、SQLAlchemy、PostgreSQL  
**主要负责事项**：此项目后端部分为独立开发，完成了从技术选型预研到需求分析与后端架构设计到功能实现整个过程 
+ **金蝶天燕数据智脑&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2019.07~2020.08&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;后端设计及开发**  
&emsp;&emsp;数据智脑是一款支持大数据的数据可视化产品，可以将多源数据经过加载、分析、转换、计算等操作之后，结合丰富的图表组件以数据应用、门户网站、主题大屏等方式展示出来。  
**主要技术**：Python、Django、SQLAlchemy、Pandas、Spark、Celery、Websocket、MySQL、Redis、Nginx、Docker等  
**主要负责事项**：  
&emsp;&emsp;1. 适配异构多源数据库以及数据库元数据管理与数据格式化。引入从SQL语句创建数据集，增加了数据集的灵活性。引入前后端通过websocket辅助通信逻辑，增加了由后端定时定点更新数据大屏的重要功能。  
&emsp;&emsp;2. 项目整体技术架构演进与优化，对不合理的层次划分重新规划，梳理业务逻辑优化核心功能  
&emsp;&emsp;3. 引入spark大数据计算平台，完成计算层大数据处理逻辑  
**工作成果与难点攻关**：  
&emsp;&emsp; 1. 适配了市面主流的国内外数据库作为数据源，还包括kylin、clickhouse等特殊计算平台。并通过元数据映射的方式，统一了不同数据库的处理过程，极大的加快了新数据库的适配过程。  
&emsp;&emsp;2. 将业务逻辑中数据源、数据集、数据模型在后端结构中解耦。数据源统一由数据访问层处理。数据集由不同数据库表按照各自方言抽取数据到本地的形式变更为通过元数据生成SQL语句保存的形式，增加了用户数据的安全性降低了后端的复杂性。数据模型由原来的直接对本地数据做处理变更为将SQL作为统一入口，转换为dataframe后处理。
>## **个人总结**
***
有一定的技术追求，为搭建从基础到上层的个人知识体系（包括但不限于计算机体系）能长期坚持自我驱动学习。思维活跃、缜密、逻辑性强，遇见问题可以辩证深入的思考、触类旁通。具有一定的团队协作能力、抗压能力。为人正直、善良、和蔼好相处，责任心较强。