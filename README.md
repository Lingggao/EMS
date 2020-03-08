# 员工管理系统 (Employee Management System / EMS)

> 学校 - HNIST (湖南理工学院)  
> 作者 - Ling Gao (高楷修)  
> 许可证 - MIT License (麻省理工学院许可证)

<a href="https://996.icu"><img src="https://img.shields.io/badge/link-996.icu-red.svg" alt="996.icu"></a>
[![HitCount](http://hits.dwyl.com/lingggao/EMS.svg)](http://hits.dwyl.com/lingggao/EMS)

### 这个是我在大学二年级时使用 C++ 写的一个控制台员工管理系统 (Employee management system)。虽然现在它看起来非常的简陋，但是在当时，我是花费了很多的时间与精力来认真完成的这个作品，这个作品可以代表我在大学二年级时的最高编程水平。

## 主要功能与特性
### 其实根本没有什么功能，但是为了让这个程序看起来很厉害，还是写了很多东西 :satisfied:

- 程序结束时数据不会丢失
  - 所有的员工信息都存放在程序所在路径下的 Employee 文件中
  - 所有的账户密码信息都加密后存放在 AccPas 文件中
  - ~~表面加密，密码其实很容易破解~~
- 注册账户
  - 注册账户时需要输入由企业发放的注册码 (可以避免非企业员工注册账户)
  - 密码必须为 8 位以上，否则不允许注册
  - 可以判断某个账户是否已经被注册
- 登录账户
  - 注册账户后第一次登录时需要补全个人详细信息
- 快速的注销账户与退出程序
- 虽然不算好看，但是也不是很丑的界面设计 (控制台程序，理解万岁)
- 企业普通员工可以使用的功能
  - 查看个人资料
  - 修改个人资料
  - 浏览本部门员工
  - 查看工资信息
  - 修改账户密码
 - 企业高级管理人员可以使用的功能
  - 普通员工可以使用的所有功能
  - 浏览企业所有员工
  - 单独查询某个员工的详细信息
    - 通过姓名查询
    - 通过工号查询
  - 调整员工的晋升与降级
  - 任免优秀员工
  - 解雇员工
  
