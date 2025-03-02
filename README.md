# Online-Judge-System
基于SpringCloud微服务+MQ+Docker的编程题目评测系统
整个系统的后端分为：
用户服务：提供用户登录、用户的增删改查等管理功能
题目服务：提供题目的增删改查管理、题目提交功能
判题服务：提供判题功能，调用代码沙箱并比对判题结果
代码沙箱：提供编译执行代码、返回结果的功能
公共模块：提供公共代码，比如数据模型、全局请求响应封装、全局异常处理、工具类等
网关服务：提供统一的 API 转发、聚合文档、全局跨域解决等功能

业务的核心流程：
![image](https://github.com/user-attachments/assets/f6d92e72-eda8-40d6-90c4-44902fd66ecf)
序列图：
![image](https://github.com/user-attachments/assets/91cf2e39-dd18-432c-a84c-a6805a1f988b)

