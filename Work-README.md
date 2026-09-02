<!--
 * @Descripttion: 周计划
 * @version: 1.0.0
 * @Author: Kenny
 * @Date: 2025-04-30 15:42:29
 * @LastEditors: ~
 * @LastEditTime: 2026-09-02 09:28:52
-->
# 计划

## 通用型工具包：三控件（具体见模块化开发标准）

```bash
（合作项目 bus_TA/AW/AC/SC/TRN,*Dealer,✔mini-program-uniapp,seerAdmin,Datacenter,IMChatTencent）
◆ styles:*toolStyle、common、index-dashboard-module (variables）
- 使用流程
+ 添加variables
  $fz -> $f_
+ vue.config配置alias，prependData
◆ utils:*index(help)
## help:
+ mock(index.js  mockData.js移入mock文件index)
+ requestWebUI
+ utils
+ index.js
◆ mixins:*tableMixin【tableMixinDome_Upload】,Upload,apiTemplate

【update】TA【改动交大尤其中部，如有新项目，类似旧项目优先旧项目，再去迭代新项目，否则用此最新】
## DialogWarningReminder: 异常提示
## 其他
+ 后台系统mock数据逻辑处理：tableMixin处理
* 路线管理mock逻辑处理
## mini-program-uniapp
◆ styles: 遮罩
## SmartScreen：通用型CDN工具类方法调研
```

## 周计划

```bash
+ App
* 15200002414/1*6
+ 患者：
* 13149218678/1-6（*文歌）
* 15200000000/1*6（布控-IM徐伟）✔
* 13359254117/1*6(王洁-IM侯浩军)
+ 医生：
* 17398675387/1-6（郝敏）
* 15200000222/1*6（王辉）
* 15200000011/1-6（王英文）
* 15200000119/1*6(李长安-中医） call✖ 账户问题
* 15200009170/1*6（曹秀梅9170-中医） ✔
1.0 云信 IMChat
2.0 开发master_AW：AI智能穿戴健康中心
- https://www.cnblogs.com/hiayap/p/17264463.html
* scroll_close：防止事件被禁止被注释，但是存在点击会触发滚动
3.0 开发master_TA：出租车类
* 循环依赖：检查是否存在模块间循环引用,导致无法使用以下方式
export const getCustomTimes = (param) => {
  return param;
};
3.1 解决导入无法使用问题(master_TA2.1.1)
4.0 开发master_EnOC：国际化社区bugge处理
5.0 模块开发：
- 通过工具让夜神模拟器的app的接口访问模拟的数据？
5.1 AppHealth：less的集成
5.2 小程序开发：思尔模块小程序：商城（20251203-20260209）
- 做经销商健康管理模块于20260615暂停
5.2.1 框架处理
✅ 工具
✔  微信开发者：编辑 → 清除
✅ 分包处理
✔  解决vendor.js占用过大问题
5.2.2 代码实现：setup
5.2.2.1 商城模块开发
+ 确认订单：活动须知弹框?
+ 支付模块开发与联调：仅支持小程序，其他预留支付
5.2.2.2 消息模块
5.2.2.3 首页模块开发：轮播/健康服务/健康互动/我的指标/健康管理/便民生活
+ 健康服务模块开发：健康指标
5.2.2.4 个人资料
+ 个人资料模块开发：上传截图?选择城市?保存？
5.2.2.5 我的设备
+ ucharts在真机模式只能点击线条显示信息，且不准确ING
+ 微信版本兼容处理： 首页兼容处理u
5.2.3 团队管理
✔  git每日提交与合并同步
6.0 Dealer 三控件更新
7.0 经销商：添加健康管理模块 （20260615 ~ ）
+ 简易报告✔/健康预估✔/血糖分析✔/睡眠监测✔/认知分析+✔/9.15健康与亚健康✔/血压分析✔/饮食分析ing/运动分析/趣味评估
+ https://dev.seer-health.com/app/v3/SmartScreen/#/login 访问异常
- 处理页面滚动问题

8.0 其他项目


⭐ 状态说明
- ING: 属于进行中，未合并到master
- DONE: 完成状态，已经合并到master
- DONEMOCK: 完成状态，仅是模拟数据
- PAUSE: 暂停状态
- RESEARCH: 研究
```

## 预期计划

```bash
0.0 更新同步（styles、mixins、utils三控件）
+ tableMixin兼容Vue3.0
* this.$message
* 调用querySearchList
1.0 经销商系统 dealer
1.1 经销商系统界面维护与修复处理
1.2 经销商系统框架维护与技术支持
1.2.1 main utils:无法定义待处理
1.2.2 迭代：
1.2.2.1 售后管理/维修工单列表迭代：按钮显示的逻辑
2. 医生模块
2.1 seerAdmin 数据管理中心 
2.2 医生审核列表-新增上传图片异常
2.3 合并三控件
3.0 大屏BI智能系统
3.1 数据库配置
4.0 大屏三控件集成
4.1 requestWebUI的工厂化使用
5.0 magic-api
5.1 函数，定时器的应用
5.2 解决数据存储问题： cardClaimRecord 代金券基数
```

## 其他计划

```bash
# AI
- 运行：OpenCode
# 云界面：替代亚马逊
# D:\软件\Office
# md目录更新化
# 备份全局：.gitconfig
# GeneralTool:通用型工具更新
- 原则：通用型与项目按需更新
# 前端+Python全栈+AI Agent对话，大模型，数据可视化（ECharts/D3），前端安全（XSS/CSRF）
- 前端使用 claude code，OpenAI Codex，cursor
- agent skill/d2c ssd
# 打造PC端项目
# 学习创建Java接口：增删改查
# 利用微前端
```
