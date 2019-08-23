# **Dashboard V3** 开发日志

## **[2019-08-23]**

1. LabView NXG中新使用了通过相对路径的方法去访问data.txt，解决了项目移动位置时每次都要修改NXG中“GetData”的绝对地址的问题。
2. 修复了nameList中第一位的TSE上线时，不显示卡片的Bug。
3. LabView NXG中新增了通过调用Windows API，每30s移动一次光标，防止Windows自动锁屏。
