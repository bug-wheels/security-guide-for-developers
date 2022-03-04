# 实用性 WEB 开发人员安全须知

面向互联网人员梳理的安全指南，旨在梳理风险点并提供一些方案。



## 参考和收集工作

本文档在以 `FallibleInc/security-guide-for-developers` 的项目为主要模板，在此基础之上加入了一下其他项目的文档和工作经验，下面列出参考文档

- [GitHub: FallibleInc/security-guide-for-developers ](https://github.com/FallibleInc/security-guide-for-developers)
- [GitHub: Tencent/secguide](https://github.com/Tencent/secguide)



## 理念

基于 `No Code, No Bug ` 理念，我们希望可以少出 bug 多去玩。



## 目标读者

涉及公开项目的开发从业人员，包括开发、测试等



## 目录

1. [互联网公司漏洞统计](vulnerabilities-stats-zh.md)
2. [人员安全问题](person.md)
2. 设计方案问题
3. 数据校验和过滤: 绝不信任用户输入
   1. 校验和过滤用户输入
   2. 过滤输出
   3. 跨站脚本攻击（XSS）
   4. 注入攻击
   5. 用户上传
   6. 用户篡改输入



## 实践

代码安全指引可用于以下场景：

- 开发人员日常参考
- 编写安全系统扫描策略
- 安全组件开发
- 漏洞修复指引



## 贡献

凑合看看吧，我也不是安全从业人员。



## 授权许可

[CC BY 4.0](https://creativecommons.org/licenses/by-sa/4.0/)