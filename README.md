# 学生成绩管理系统 python101

## 项目概述

学生成绩管理系统是基于Python+Flask+MySQL的Web应用，旨在提供便捷的成绩管理和查询功能。系统支持不同角色的用户，包括管理员、教师和学生，进行成绩的录入、查询、修改和删除操作。

## 技术栈

- 后端：Python
- Web框架：Flask
- 数据库：MySQL

## 功能模块

### 用户角色

- 管理员
- 教师
- 学生

### 主要功能

- **系统交互**
- **登录**：无需注册，用户名和密码预设或可修改
  - 管理员：用户名`admin`，密码固定
  - 教师：用户名为教师编号，密码默认为编号，可修改
  - 学生：用户名为学生编号，密码默认为学生编号，可修改
- **修改密码**
- **成绩查询**
  - 学生：基本信息，各门课程成绩
  - 教师：基本信息，所授课程基本信息，学生选课信息，成绩及统计结果
- **成绩录入、修改、删除**
- **统计功能**：统计各分数段学生的成绩分布，并绘制直方图和饼图

## 系统角色

- **管理员**：负责管理学生、教师、课程基本信息
- **教师**：负责所授课程的成绩管理
- **学生**：查询个人成绩

## 运行环境

- Python环境
- Flask框架
- MySQL数据库

## 目录结构

```
/项目目录
    /static
    /templates
    /app
        __init__.py
        models.py
        views.py
    run.py
    requirements.txt
```

## 核心亮点

- 无需注册，简化用户管理
- 多角色权限分明，操作便捷
- 直观的成绩统计图表，方便分析

---

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img12.360buyimg.com/ddimg/jfs/t1/336992/6/14115/10536/68d2cb8bF1d08414f/c1c84a7a8d9ff484.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/331739/33/16644/79873/68d2cb8bF22d8b401/cc1e4a69fdca2ab0.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/348347/35/6818/51237/68d2cb8cF4f6015da/ec87e2052c017c55.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/337078/39/14143/73728/68d2cb8cF5151ca12/d187d5f5a5e4f06b.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/349747/21/6727/23967/68d2cb8cFaf0e05ec/c565caf2becfa6e6.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/344915/23/6690/42381/68d2cb8dF9e6eef5a/504ee89b22fd96c2.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/338735/15/14039/21191/68d2cb8dF86664fbd/5d9f00147bec7722.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/349329/20/6881/17727/68d2cb8eF6bc5fe85/14771e953f2d3590.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/241972/29/29792/79873/68d2cb8eF25aef8f9/80ad437438823c87.jpg)
