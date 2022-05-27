# awesome-buaa

收集整理优秀的工具，免去造轮子的痛苦

如果有想要补充的新条目，或者删去过时条目，欢迎提交Issue或者提交PullRequest！

每个工具都使用了【XXXX】来标注使用的语言，其中【SELENIUM】指使用了selenium包的python程序，而【PYTHON】指不使用selenium的程序。两者的区别是，标有【PYTHON】的程序更加花费编程者的心血，通常占用更低，效率更高，适配性更广。

### 网关登录

- [GitHub - buaahub/BeihangLogin](https://github.com/buaahub/BeihangLogin)【BASH】由buaahub提供的bash实现的脚本
  
  - [GitHub - SincereXIA/buaa-login: 北航 BUAA-WIFI 登录脚本 for OpenWrt](https://github.com/SincereXIA/buaa-login)

- [深澜认证协议分析,python模拟登录_huxiaofan1223-CSDN博客](https://blog.csdn.net/qq_41797946/article/details/89417722) 下面的脚本均为基于此博文以Python实现的脚本
  
  - [GitHub - buaalzm/buaaGatewayAutoLogin: 北航校园网网关自动登录](https://github.com/buaalzm/buaaGatewayAutoLogin)【PYTHON】
  
  - [GitHub - HawkQ/buaa-gw](https://github.com/HawkQ/buaa-gw)【PYTHON】
  
  - [GitHub - FuryMartin/BUAA_WIFI](https://github.com/FuryMartin/BUAA_WIFI) 【PYTHON】有对树莓派和win平台的教程

- [GitHub - Dr-Bluemond/srun: 北京航空航天大学校园网命令行登录工具，多系统支持](https://github.com/Dr-Bluemond/srun) 【GO】支持多平台原生运行，无需安装依赖，具有登录、登出、查询用量的功能

- [GitHub - lqh9856/BUAALogin: 北航校园网自动登录](https://github.com/lqh9856/BUAALogin)【PYTHON】额外提供了systemd的配置文件和教程，适用于Linux系统

- [GitHub - KuiyuanFu/PythonBuaaGWAutoLogin](https://github.com/KuiyuanFu/PythonBuaaGWAutoLogin) 【SELENIUM】

### 教务系统

#### 选课脚本

- [GitHub - Errno1024/BUAA-Course-Grab: BUAA Course Grab is intended to be a tool set for BUAA undergraduates to automatically grab or drop courses.](https://github.com/Errno1024/BUAA-Course-Grab) 【PYTHON】集成博雅课程和教务选课系统功能，提供丰富的功能和完整的使用文档

- [GitHub - Cauchy1412/BUAAGetCourse: 用来蹲北航教务给课程扩容的名额，解放双手双眼](https://github.com/Cauchy1412/BUAAGetCourse) 【PYTHON】具有使用说明注释和文档

#### 一键评教

- [GitHub - bearbattle/buaa-teacher-evaluation: 北航教务一键评教。](https://github.com/bearbattle/buaa-teacher-evaluation)【PYTHON】

- [GitHub - APassbyDreg/BUAA_JW_Utils: 北航教务辅助脚本工具集](https://github.com/APassbyDreg/BUAA_JW_Utils)【SELENIUM】

#### 其他工具

- https://github.com/wzk1015/BUAA-getscore 【PYTHON】每分钟刷新本学期GPA，若发生变化（即有课程）则一分钟内自动发送邮件至邮箱。

- [GitHub - roife/BUAAIcsGen: Automatically generate *.ics files for classes](https://github.com/roife/BUAAIcsGen) 【PYTHON】一个从教务自动爬取课表，并转换成 ICS 文件的小工具，可以导入到系统日历中。

- [GitHub - roife/BUAACalendarHelper: A tiny iOS app for fetching classes from BUAA. (course assignment for BUAA-Swift)](https://github.com/roife/BUAACalendarHelper) 【SWIFT】iOS版教务课表查询、导入到系统日历

- https://github.com/yinwoods/Fuck-BUAA-JiaoWu-Anyway 【PYTHON】

- [GitHub - SE2020-TopUnderstanding/BUAA-Campus-Tools-Backend: 北航教务小助手-后端（Python Web、爬虫）](https://github.com/SE2020-TopUnderstanding/BUAA-Campus-Tools-Backend) 【DJANGO】软工项目，提供许多针对教务网站的工具

### 博雅系统

- [GitHub - Dr-Bluemond/BuaaBykcCrawler: 北航博雅课程Python爬虫接口](https://github.com/Dr-Bluemond/BuaaBykcCrawler)【PYTHON】

- [GitHub - Errno1024/BUAA-Course-Grab: BUAA Course Grab is intended to be a tool set for BUAA undergraduates to automatically grab or drop courses.](https://github.com/Errno1024/BUAA-Course-Grab) 【PYTHON】集成博雅课程和教务选课系统功能，提供丰富的功能和完整的使用文档

- ~[GitHub - Chenrt-ggx/BUAABYKCCrawler-: query bykc preview info as well as selection info for buaaers](https://github.com/Chenrt-ggx/BUAABYKCCrawler-)【PYTHON】~

- [GitHub - Eadral/buaa-bykc](https://github.com/Eadral/buaa-bykc)【SELENIUM】

- [GitHub - wendingp/boya-hunter: 北航博雅自动刷课](https://github.com/wendingp/boya-hunter)【SELENIUM】

### TD查询

- ~[GitHub - Chenrt-ggx/BUAATDCrawler: query td times for buaaers](https://github.com/Chenrt-ggx/BUAATDCrawler)【PYTHON】~

### ihome

- https://github.com/buaahub/ihome-crawler 【PYTHON】TG频道ihome forwarder内核脚本

- https://github.com/shiyake/php-ihome  【PHP】ihome网站源码

### 每日打卡

- [GitHub - zackertypical/buaa_daily_check](https://github.com/zackertypical/buaa_daily_check) 【JAVASCRIPT】运行于iOS设备上的全自动定时打卡脚本，有详细的教程。

- [GitHub - SnapdragonLee/BUAA_AutoCheck: 北航健康打卡自动脚本](https://github.com/SnapdragonLee/BUAA_AutoCheck) 【JAVASCRIPT】【PYTHON】另一个运行于iOS设备上的打卡脚本，还有一个Python脚本。

- [GitHub - windiboy/BUAAAutoUpdate: 北京航空航天大学自动报平安脚本](https://github.com/windiboy/BUAAAutoUpdate)【PYTHON】

- [GitHub - mottled233/buaa_daily_report: 北航每日健康打卡自动化脚本，我不做人了！](https://github.com/mottled233/buaa_daily_report)【SELENIUM】

### 电表查询

- [GitHub - Apodead/BuaaAmmeterBot: 北航电表查询 Telegram Bot](https://github.com/Apodead/BuaaAmmeterBot)【PYTHON】

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

### 六系工具

- [GitHub - karin0/jumpserver-proxy: 在本地愉快写 BUAA OS Lab，并直接在本地使用 git 提交。](https://github.com/karin0/jumpserver-proxy)【GO】面向”操作系统课程设计“的工具，穿透堡垒机直接访问git仓库

- [GitHub - dhy2000/CG-Submit](https://github.com/dhy2000/CG-Submit)【PYTHON】希冀 (CourseGrading) 平台作业文件提交工具，适用于六系编译技术实验与信息大类数据结构

- [GitHub - dhy2000/TimeInput: 实时交互输入辅助工具](https://github.com/dhy2000/TimeInput) 【JAVA】面向对象课程多线程单元实用工具，将带时间戳的输入按以时间戳规定的时间输出。

### 八系工具

- [GitHub - HoBeedzc/CreditCount: 八系一般专业课学分核算工具，助你顺利毕业。](https://github.com/HoBeedzc/CreditCount) 【JAVASCRIPT】八系一般专业课学分核算工具。可以直接访问网页版 [学分核算](https://cc.hobeedzc.cn) 

- [GitHub - grandchicken/1708SEM_ISIM: 八系信管专业课程攻略](https://github.com/grandchicken/1708SEM_ISIM) 【RICHTEXT】八系信管专业课程资料整理，持续更新ing...

### 课程中心相关

暂无

### 图书馆相关

暂无

### 核酸检测排队情况
- [BUAA核酸检测排队实时查询](https://jinshuju.net/f/C8F4x3)
