# **Dashboard V3** 开发文档

## **1 概述**

### **1.1 Dashboard V2:**

![效果图](DashboardV2.png)
**Dashboard V2**在**4K**分辨率下运行（效果图如上）。

### **1.2 Dashboard V3:**

**Dashboard V3**将针对**Dashboard V2**进行多方面升级，包括程序自动化、后期可维护、新增通知功能等。

## **2 预计升级内容**

### **2.1 程序自动化**

1. LabView NXG中添加间隔时间调用Windows API，防止Windows自动锁屏。
2. LabView NXG中添加指定时间自启动Python爬虫的功能。
3. Python爬虫中添加实时状态输出功能，LabView中添加相应循环，用于处理Python爬虫的实时状态信息，根据需求重启Python爬虫，或Permalink失效报警等。

### **2.2 新增功能**

1. LabView NXG中添加通知栏，用于播报各类实时信息（如：2.1.3中链接失效报警，available人数较低报警）。
2. 探索新的可提供的数据。（具体和IT讨论后得出）
   1. Cisco数据库可每30s提供当前等待中客户人数。
3. 根据3种状态（available，talking，away）进行重排序。

### **2.3 后期可维护**

1. Python爬虫代码注释完善。
   1. 使用OOP对Python部分功能进行封装。
2. LabView NXG代码注释完善。
3. 提供修改namelist相关操作的操作文档。

### **2.4 其他**

1. 利用Microsoft Wireless Display Adapter实现无线投屏（分辨率将降至1080p）。

## **3 DashboardV3 Web版规划**

### **3.1 概述**

1. 利用LabView NXG Web Module进行开发。
