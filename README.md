 <center>
     <h1>郭超</h1>
     <h3>18220052953 | Guochao_net@163.com | 深圳 | 26</h3>
 </center>

## **工作及教育经历**
***
**金蝶天燕云计算股份有限公司&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2019.07~至今&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;中间件产品部**
+ 荣誉和奖励：金蝶天燕十佳员工(优秀新人)、金蝶集团微创新奖(3%)、金蝶集团发明专利奖两项

**西安邮电大学&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2015.09~2019.07&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;网络工程专业-本科**
+ 荣誉和奖励：国家奖学金(专业第一)、国家励志奖学金(专业第二)、优秀班干部等
## **专业技能**
***
* 扎实的Go语言基础，熟悉Go语言底层设计原理，包括调度模型GPM、内存管理(堆、函数调用栈、GC)、类型系统(接口、类型断言、Reflect)、Channel、Mutex、Map及其它数据结构、Defer、Panic等。熟悉Gin、Gorm等web开发组件
* 熟悉计算机网络，熟悉OSI参考模型、IP、TCP、HTTP(HTTPS)等，了解DNS、ARP、NAT等
* 熟悉网络编程、IO多路复用
* 熟悉Redis核心处理流程，包括EventLoop事件循环机制(EventLoop->Epoll->Socket)、命令处理生命周期，了解底层数据类型和常用的数据结构
* 熟悉Mysql，了解索引、事务、日志系统
* 熟悉Linux，能编写Shell脚本，了解Linux下常用命令与工具。了解Git
* 熟悉常见的数据结构与算法，了解计算机组成原理、操作系统
* 了解Python语言、C语言
* 了解nginx、lvs、keepalived
* 了解Docker，了解Docker实现机制，了解Dockerfile，了解Kubernetes，了解gRPC
## **项目经历**
***
+ **金蝶天燕分布式缓存数据库&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2021.07~2022.09&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;后端设计及开发**  
&emsp;&emsp;金蝶天燕分布式缓存数据库是为了国产化信创产业的发展使用Go语言对标Redis5.0完全自研的工业级缓存软件。性能比肩Redis5.0并实现了功能上的全覆盖。  
**官网**：https://www.apusic.com/list-338.html  
**主要技术**：Go、EventLoop、Epoll、Socket  
**主要负责事项**：  
&emsp;&emsp;1. 参与核心处理流程开发，包括配置初始化、事件循环机制、命令处理过程等。  
&emsp;&emsp;2. 完成哨兵模块的开发，独立完成Benchmark模块的开发。  
**主要工作成果与难点攻关**：  
&emsp;&emsp;1. 深入分析了Redis5.0源码的核心处理流程，因为其涉及到很多操作系统、数据结构和网络编程相关知识所以这个过程需要开发人员具有较好的计算机体系基础知识作为支持。  
&emsp;&emsp;2. 深入探究了Go语言的底层调度模型GPM和内存管理及类型系统等原理，用于支持用Go复现C语言特性、保证产品稳定性、提高产品性能。
+ **金蝶天燕负载均衡器&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2020.08~2021.07&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;后端设计及开发**  
&emsp;&emsp;金蝶天燕负载均衡器是为了国产化信创产业的发展基于APISIX开发的一款流量网关产品。支持x86、arm架构主流国产Linux操作系统下负载均衡器的全自动化离线部署与管理，内置了自动化的高可用高并发集群部署功能，支持多种流量管理场景下插件的定制化开发。  
**官网**：https://www.apusic.com/list-282.html  
**主要技术**：Go、Shell、Lua、Gin、APISIX、Openresty、Nginx、ETCD、LVS、Keepalived等  
**主要负责事项**：  
&emsp;&emsp;1. 产品包多实例管控台的开发，管控台实现了对服务器的管理、产品包的部署启停及状态监控、多节点负载均衡器的流量监控。  
&emsp;&emsp;2. 高可用高并发集群部署方案的研究与自动化。  
&emsp;&emsp;3. 适配x86、arm架构主流国产Linux操作系统，编写离线部署与安装代码与脚本。  
**主要工作成果与难点攻关**：  
&emsp;&emsp;1. 在产品复杂度高且依赖较多基础组件如Openresty、ETCD等的情况下完成在众多异构Linux操作系统下的适配工作。并结合Go与Shell，完成多种复杂情况下的自动化打包及安装部署工作。  
&emsp;&emsp;2. 为方便用户管理大规模的服务器节点，独立完成了多实例管控台的开发工作。并独立完成了基于ETCD、LVS、KeepAlived的高并发高可用方案，且内嵌到安装包中，只需配置集群IP与VIP即可自动完成集群部署，极大的减少了实施人员的工作量。 
+ **金蝶天燕数据智脑&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2019.07~2020.08&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;后端设计及开发**  
&emsp;&emsp;数据智脑是一款支持大数据的数据可视化产品，可以将多源数据经过加载、分析、转换、计算等操作之后，结合丰富的图表组件以数据应用、门户网站、主题大屏等方式展示出来。   
**官网**：https://www.apusic.com/list-210.html  
**主要技术**：Python、Django、FastAPI、SQLAlchemy、Pandas、Spark、Celery、Websocket、Redis、Nginx、Docker和各种数据库  
**主要负责事项**：  
&emsp;&emsp;1. 独立预研并适配异构多源数据库以及数据库元数据管理与数据格式化。引入从SQL创建数据集，增加了数据集的灵活性。引入前后端通过websocket辅助通信逻辑，增加了由后端定时定点更新数据大屏的重要功能。  
&emsp;&emsp;2. 项目整体技术架构演进与优化，对不合理的层次划分重新规划，梳理业务逻辑优化核心功能。  
&emsp;&emsp;3. 引入spark大数据计算平台，独立完成计算层大数据处理逻辑。    
&emsp;&emsp;4. 独立完成将多源数据库数据以RESTful API形式发布为数据API，此功能类似于阿里DataWorks的数据服务模块。  
**工作成果与难点攻关**：  
&emsp;&emsp; 1. 适配了市面主流的国内外数据库作为数据源，还包括kylin、clickhouse等特殊计算平台。并通过元数据映射的方式，统一了不同数据库的处理过程，极大的加快了新数据库的适配过程。  
&emsp;&emsp;2. 将业务逻辑中数据源、数据集、数据模型在后端结构中解耦。数据源统一由数据访问层处理。数据集由不同数据库表按照各自方言抽取数据到本地的形式变更为通过元数据生成SQL语句保存的形式，增加了用户数据的安全性降低了后端的复杂性。数据模型由原来的直接对本地数据做处理变更为将SQL作为统一入口，转换为Dataframe后处理。
## **个人总结**
***
有一定的技术追求，为搭建从基础到上层的个人知识体系（包括但不限于计算机体系）能长期坚持自我驱动学习。思维活跃、缜密、逻辑性强，遇见问题可以辩证深入的思考、触类旁通。具有一定的团队协作能力、抗压能力。为人正直、善良、和蔼好相处，责任心较强。