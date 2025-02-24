# awesome-buaa

[TOC]

收集整理优秀的工具，免去造轮子的痛苦

如果有想要补充的新条目，或者删去过时条目，欢迎提交Issue或者提交PullRequest！

每个工具都使用了【XXXX】来标注使用的语言，其中【SELENIUM】指使用了selenium包的python程序，而【PYTHON】指不使用selenium的程序。两者的区别是，标有【PYTHON】的程序通常使用requests包访问网络，通常效率更高，系统兼容性更好。

某些脚本可能违反了学校相关规定。Use at your own risk!

### 网关登录

- [Github - BeihangLoginWithDockerCheck](https://github.com/ywz978020607/pySrun4k_BeihangLogin)【PYTHON】支持python登陆&docker一键部署+自动监控重连

- [GitHub - buaahub/BeihangLogin](https://github.com/buaahub/BeihangLogin)【BASH】由buaahub提供的bash实现的脚本
  
  - [GitHub - SincereXIA/buaa-login: 北航 BUAA-WIFI 登录脚本 for OpenWrt](https://github.com/SincereXIA/buaa-login)

- [深澜认证协议分析,python模拟登录_huxiaofan1223-CSDN博客](https://blog.csdn.net/qq_41797946/article/details/89417722) 下面的脚本均为基于此博文以Python实现的脚本
  
  - 【注意：该脚本试图收集用户名和密码】 ~~[GitHub - buaalzm/buaaGatewayAutoLogin: 北航校园网网关自动登录](https://github.com/buaalzm/buaaGatewayAutoLogin)【PYTHON】~~ 
  
  - [GitHub - HawkQ/buaa-gw](https://github.com/HawkQ/buaa-gw)【PYTHON】
  
  - [GitHub - FuryMartin/BUAA_WIFI](https://github.com/FuryMartin/BUAA_WIFI) 【PYTHON】有对树莓派和win平台的教程

- [GitHub - Dr-Bluemond/srun: 北京航空航天大学校园网命令行登录工具，多系统支持](https://github.com/Dr-Bluemond/srun) 【GO】支持多平台原生运行，无需安装依赖，具有登录、登出、查询用量的功能

-  [GitHub - lynzrand/beihang-login](https://github.com/lynzrand/beihang-login)【RUST】支持登入登出

- [GitHub - soyons/BUAALogin: 北航校园网自动登录](https://github.com/soyons/BUAALogin)【PYTHON】额外提供了systemd的配置文件和教程，适用于Linux系统

- [GitHub - Izumiko/buaalogin: 使用Nim语言编写的北航校园网客户端](https://github.com/Izumiko/buaalogin)【NIM】

### 教务系统

#### 选课脚本

- [GitHub - Colorfulshadow/buaa_course_enrollment: 旨在自动化北京航空航天大学（BUAA）的课程选课过程。](https://github.com/Colorfulshadow/buaa_course_enrollment)【PYTHON】选课、抢课，有说明注视以及使用文档

- [GitHub - Errno1024/BUAA-Course-Grab: BUAA Course Grab is intended to be a tool set for BUAA undergraduates to automatically grab or drop courses.](https://github.com/Errno1024/BUAA-Course-Grab) 【PYTHON】集成博雅课程和教务选课系统功能，提供丰富的功能和完整的使用文档

#### 一键评教

- ~~[GitHub - bearbattle/buaa-teacher-evaluation: 北航教务一键评教。](https://github.com/bearbattle/buaa-teacher-evaluation)【PYTHON】~~

- ~~[GitHub - APassbyDreg/BUAA_JW_Utils: 北航教务辅助脚本工具集](https://github.com/APassbyDreg/BUAA_JW_Utils)【SELENIUM】~~

- [GitHub - el-ev/BUAA-Teacher-Evaluation：北航教务一键评教](https://github.com/el-ev/BUAA-Teacher-Evaluation)【PYTHON】

- [GitHub - ZenAlexa/BUAA_TeachingEvaluation_2024Winter：BUAA一键多方式综合评教](https://github.com/ZenAlexa/BUAA_TeachingEvaluation_2024Winter)【PYTHON】

#### 查询成绩

- [GitHub - wzk1015/BUAA-getscore](https://github.com/wzk1015/BUAA-getscore) 【PYTHON】每分钟刷新本学期GPA，若发生变化（即有课程）则一分钟内自动发送邮件至邮箱。

- [GitHub - hjc-owo/BUAA_Get_Score: 北航自动查分脚本](https://github.com/hjc-owo/BUAA_Get_Score)【PYTHON】北航自动查分脚本

- [GitHub - PhantomPower82/buaa-get-score: BUAA 自动查分](https://github.com/PhantomPower82/buaa-get-score)【PYTHON】BUAA 自动查分

#### 其他工具

- [GitHub - roife/BUAAIcsGen: Automatically generate *.ics files for classes](https://github.com/roife/BUAAIcsGen) 【PYTHON】一个从教务自动爬取课表，并转换成 ICS 文件的小工具，可以导入到系统日历中。

- [GitHub - roife/BUAACalendarHelper: A tiny iOS app for fetching classes from BUAA. (course assignment for BUAA-Swift)](https://github.com/roife/BUAACalendarHelper) 【SWIFT】iOS版教务课表查询、导入到系统日历

- [GitHub - Bhipee/BeiHangPostgraduateTimetable: 北航研究生课程表导出ics文件脚本，方便导入日历](https://github.com/Bhipee/BeiHangPostgraduateTimetable)【PYTHON】

- https://github.com/yinwoods/Fuck-BUAA-JiaoWu-Anyway 【PYTHON】关于教务的脚本若干

- [GitHub - SE2020-TopUnderstanding/BUAA-Campus-Tools-Backend: 北航教务小助手-后端（Python Web、爬虫）](https://github.com/SE2020-TopUnderstanding/BUAA-Campus-Tools-Backend) 【DJANGO】软工项目，提供许多针对教务网站的工具

### VPN工具

北航客户端VPN使用深信服EasyConnect，可能会在电脑中启动一个被称作“EasyMonitor”的进程，或有收集个人隐私的嫌疑。可以使用以下软件替代。

- [GitHub - lyc8503/EasierConnect](https://github.com/lyc8503/EasierConnect) 【GO】一个命令行版本，不直接代理网络，只开放sock5端口，可以用clash等设置规则只让需要vpn的流量经过。
- [GitHub - docker-easyconnect/docker-easyconnect](https://github.com/docker-easyconnect/docker-easyconnect) 【DOCKER】将EasyConnect封装在docker中。
- 提案：将d.buaa.edu.cn封装为http proxy。因为d.buaa.edu.cn虽然仅支持http与https但是相较于EasyConnect它对目标地址没有限制，可以以校内ip访问所有校内外资源。[1](https://github.com/ESWZY/webvpn-dlut),[2](https://github.com/lcandy2/webvpn-converter),[3](https://github.com/spencerwooo/bit-webvpn-converter)

### 博雅系统

- [GitHub - Dr-Bluemond/BykcTelegramBot](https://github.com/Dr-Bluemond/BykcTelegramBot)  【PYTHON】北航博雅课程在TelegramBot平台上实现的小助手。

- ~~[GitHub - Errno1024/BUAA-Course-Grab: BUAA Course Grab is intended to be a tool set for BUAA undergraduates to automatically grab or drop courses.](https://github.com/Errno1024/BUAA-Course-Grab) 【PYTHON】集成博雅课程和教务选课系统功能，提供丰富的功能和完整的使用文档~~

- ~~[GitHub - Eadral/buaa-bykc](https://github.com/Eadral/buaa-bykc)【SELENIUM】~~

- ~~[GitHub - wendingp/boya-hunter: 北航博雅自动刷课](https://github.com/wendingp/boya-hunter)【SELENIUM】~~

### ihome

- https://github.com/buaahub/ihome-crawler 【PYTHON】TG频道ihome forwarder内核脚本

- https://github.com/shiyake/php-ihome  【PHP】旧版ihome网站源码

### 电表查询

- [GitHub - Apodead/BuaaAmmeterBot: 北航电表查询 Telegram Bot](https://github.com/Apodead/BuaaAmmeterBot)【PYTHON】
- [GitHub - LaciliaExe/BUAA-ECC: BUAA electricity charge checker on Android / 北航电费查询器（安卓平台）](https://github.com/LaciliaExe/BUAA-ECC)【PYTHON&KVLANG】

### 基物实验

- [基物实验小程序](https://www.wzk.plus/project/phyexp/) 基物实验操作指南、注意事项、评价等
- [Gitee - PhisicsExperiment/PhysicsExperiment: 基物实验通用程序](https://gitee.com/PhisicsExperiment/PhysicsExperiment) 【PYTHON】自动处理实验数据生成实验报告
- [GitHub - violencemofrog/BUAA_Physical_Experiment: fucking buaa physical experiment](https://github.com/violencemofrog/BUAA_Physical_Experiment) 【PDF】基物实验报告
- [GitHub - Horatio2001/BUAA-PhysicsExp: 北航基础物理实验报告2019版](https://github.com/Horatio2001/BUAA-PhysicsExp) 【PDF】基物实验报告
- [GitHub - wtdcode/BUAAPhyhelper: Some helpful scripts for the physics experiments at BUAA.](https://github.com/wtdcode/BUAAPhyhelper) 【MATLAB-PYTHON】辅助工具
- [GitHub - wwlyeye/PhysicalExperimentSelector: 北航 基础物理实验 基物实验 抢课脚本](https://github.com/wwlyeye/PhysicalExperimentSelector)【PYTHON】
- [GitHub - qgjyf2001/queryJiwu: 北航基物实验选课脚本](https://github.com/qgjyf2001/queryJiwu)【PYTHON】

### 航空航天概论

- [GitHub - Caniformia/HangGai: HangGai for BUAA, built with SwiftUI.](https://github.com/Caniformia/HangGai) 【SWIFT】iOS版航概刷题软件
- 微信小程序搜索“航概练习题库”

### 北航网盘

- [GitHub - xdedss/dist_bhpan: 北航网盘命令行工具](https://github.com/xdedss/dist_bhpan) 【PYTHON】

### 三系工具

- [GitHub - AccSrd/BUAA_Course_Automation: 北京航空航天大学自动化专业课程资料 BUAA Course Material of Major in Automation](https://github.com/AccSrd/BUAA_Course_Automation)【RICHTEXT】

### 六系工具

- [GitHub - TheBloodthirster/BUAA_Course_Sharing: 北京航空航天大学(北航)课程作业资料共享计划](https://github.com/TheBloodthirster/BUAA_Course_Sharing) 【RICHTEXT】

- [GitHub - karin0/jumpserver-proxy: 在本地愉快写 BUAA OS Lab，并直接在本地使用 git 提交。](https://github.com/karin0/jumpserver-proxy)【GO】面向”操作系统课程设计“的工具，穿透堡垒机直接访问git仓库

- [GitHub - dhy2000/CG-Submit](https://github.com/dhy2000/CG-Submit)【PYTHON】希冀 (CourseGrading) 平台作业文件提交工具，适用于六系编译技术实验与信息大类数据结构

- [GitHub - dhy2000/TimeInput: 实时交互输入辅助工具](https://github.com/dhy2000/TimeInput) 【JAVA】面向对象课程多线程单元实用工具，将带时间戳的输入按以时间戳规定的时间输出。

- [GitHub - TrickEye/can_I_Graduate: 我能毕业嘛](https://github.com/TrickEye/can_I_Graduate) 【JAVASCRIPT】2020级毕业学分计算（[网页版](https://trickeye.github.io/can_I_Graduate/)）

### 八系工具

- [GitHub - HoBeedzc/CreditCount: 八系一般专业课学分核算工具，助你顺利毕业。](https://github.com/HoBeedzc/CreditCount) 【JAVASCRIPT】八系一般专业课学分核算工具。可以直接访问网页版 [学分核算](https://cc.hobeedzc.cn) 

- [GitHub - grandchicken/1708SEM_ISIM: 八系信管专业课程攻略](https://github.com/grandchicken/1708SEM_ISIM) 【RICHTEXT】八系信管专业课程资料整理，持续更新ing...
