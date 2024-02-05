# 监狱建筑师 (PrisonArchitect)中文豪华版2024 模组
***
### 特别感谢 GrandSong ([Steam个人主页](https://steamcommunity.com/id/grandsong/)) 最初开发了此模组    [[Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=821415114)]
### 特别感谢 Yuanze31 ([Steam个人主页](https://steamcommunity.com/id/yuanze31/)) 二次开发了此模组    [[Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=2895128242)|[Github主页](https://github.com/yuanze31/All-in-One-Deluxe)]
## 感谢两位开发者对PA社区做出的巨大贡献！

### 本次模组是对[中文豪华版]基于<原始模组>与<二次开发模组>
### 进行的修复与更新。
##当前版本：V1.1.0 | 更新日期：2024.02.06

*感谢原作者 @GrandSong 对此次更新的肯定。*

*已获得二次开发作者 @Yuanze31 许可。*

*如果有任何需要完善的地方、希望更改或添加的功能。*

*欢迎大家反馈与讨论。*

***
### 关于 模组详情 请查看置顶<原始模组>与<二次开发模组>页面
### 关于 本次更新内容 请查看本模组页面
### ➡️[中文豪华版2024]-Vigtigste [[Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=3151283978)]
***
# ❗重要：修复了在大型游戏中，
## ❗严重影响运算性能、2~5秒一次的严重卡顿、内存泄漏等严重Bug！
***
# 更新日志：
## 一、界面
1. 修复了在报告的 “接收囚犯” 界面中，“囚犯到达时间”、“移除囚犯接收限制”、“囚犯替换” 三个按钮无法显示的 Bug
2. [V1.0.6] 脏餐盘 修复： 贴图错误
3. [V1.0.7] 从代码中隐藏了星标，保留星标贴图
4. [V1.0.7] 添加了模组功能 "会计工作间" 的图标
5. [V1.0.7] 部分图标重新绘制：空房间、毒品搜查、闭路电视监控系统视线、栅栏、直升机相关等
6. [V1.0.9] 以 <RestylingUI (Continued)> 为基础重新绘制了原版与 DLC 图标，并以颜色区分功能。
(红色 - 囚犯专用，橙色 - 狱中劳役，黄色 - 囚犯活动，蓝色 - 员工专用，绿色 - 交通运输)

## 二、房间
1. 林场 修复： 修复了狱中劳役失效的 Bug
2. 庭院 修复： 修复了错误代码导致的 Bug，并调整了冲突数值。面积评分标准：(25+1/50+2) > (50+1/100+2)
3. 牢房 更改： 更新并优化了评分需求
4. 教室 增加： 加入了对豪华办公桌的替代支持
5. 其他微调

## 三、方案
1. 集体健身 更改： 席位 30>20。增加替代物品：哑铃，沙袋，训练木桩，跑步机
（原设计需要 30 个举重床太影响布局，所以添加了对更多物品替代支持)
(并且席位相对于原版方案也显得过多，所以将席位减少以更符合原版）
2. 参考 <LargePrisonMod> 后，对游戏原方案进行调整
稍微减少了方案费用、时间长度、参加次数，部分课程稍微增加了参与席位 (如：行为疗法)

## 四、人物
1. 典狱长 更改： 血量 5>20
（为了提高在执行模组方案 “近距离接触” 时，发生暴动后典狱长的生存能力，所以将血量稍微提高）
2. 参考 <LargePrisonMod> 后，对游戏原人员数值进行调整
    - 警卫 更改： 视野 12>18，移速 0.5>1.0
    - 武装守卫 更改： 血量 15>30，视野 15>24，移速 0.5>0.7，删除： 最大人数限制
    - 训犬员 更改： 移速 0.5>0.8，视野 12>20
    - 其他微调

## 五、紧急服务
1. 消防人员 更改： 召唤数量 3>5
2. 护理人员 更改： 召唤数量 3>5
3. 防爆警察 更改： 价格 100>300，单次召唤人数 4>6
4. 部队 更改： 召唤数量 3>5，单次召唤人数 4>6
5. 其他微调
6. 1. [V1.0.5] 供给车 增加： 紧急服务费用 100。修复图标缺失的问题。
(模组方案 “近距离接触” 在大规模监狱中会产生较多的奖金堆积，所以加入了 < CallableTrucks > 模组的供给车紧急服务功能)
7. [V1.0.5] 灵车 增加：紧急服务费用 100。(大规模监狱的暴动会产生大量尸体堆积，所以加入了灵车紧急服务)

## 六、物品
1. 医药箱 更改：价格 200>1000。医药箱内放置了戒断药物，能够使周围的囚犯少量满足酒精需求，极少满足毒品需求
2. 灯 更改 ：允许克隆，建造时间缩短
3. 金属探测器 更改： 位置调整回物品菜单
4. 饮料贩卖机 删除： 脚本功能
5. 风扇 增加： 可少量满足囚犯的舒适需求
6. 可回收垃圾桶 增加： 与垃圾桶一样可少量满足环境需求
7. 植物 增加： 植物不再只是装饰品，可极少满足囚犯的环境需求
8. 单人沙发、双人沙发 添加： 加入休息分类中
9. 参考 <LargePrisonMod> 后，调整了物品堆叠数量
10. 加入了 <Ozone'sFixes&QolAll-In-One> 中的一些功能：
    - 办公桌 添加： 允许囚犯使用，能够满足文化需求
    - 宠物鸟 更改： 范围扩大一格
    - 矮书架 修复： 书籍无法被放置于矮书架的 Bug
11. 其他微调
12. [V1.0.4] 奖金 修复：修复了奖金售价与显示不符的错误。调整了贴图大小以便区分
13. [V1.0.9] 车牌 修复：修复了车牌与空车牌出售相关的 Bug (感谢 @军刃血梦 提交的反馈)
14. [V1.1.0] 修复了所有可售出货物价格低于预期的问题
    
## 七、翻译
1. 添加缺失的汉化
2. 简化大量繁体
3. 微调部分文本
4. 修改了待办事项中文本的错误、繁琐、繁体等，如：
    -X 个囚犯将于上午 8 点抵达 > X 个囚犯将要抵达
    - 不再接收新的犯人 > 暂停接收新囚犯
    - 死刑犯宽大处理可能性 > 死刑犯上诉成功率
    - 我们拥有 A 间空闲的 B 牢房。> 空闲 A 间 B 牢房
5. [V1.1.0] 为所有可售出货物的名字后添加了售价备注

***
## 再次感谢两位开发者对PA社区做出的巨大贡献！
### 特别感谢 GrandSong ([Steam个人主页](https://steamcommunity.com/id/grandsong/)) 最初开发了此模组    [[Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=821415114)]
### 特别感谢 Yuanze31 ([Steam个人主页](https://steamcommunity.com/id/yuanze31/)) 二次开发了此模组    [[Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=2895128242)|[Github主页](https://github.com/yuanze31/All-in-One-Deluxe)]
***
### 本次修复使用或参考了以下模组的内容，感谢这些作者的辛勤付出！
#### LargePrisonMod/大型监狱模组    [Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=359636985)
#### Ozone'sFixes&QolAll-In-One/Ozone的修复和Qol一体化    [Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=2978340955)
#### CallableTrucks/应急卡车    [Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=1632394574)
#### RestylingUI(Continued)/重新设计用户界面(续)    [Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=3009547076)
***
## 我正在使用的模组推荐：
#### Prison Population Grants/监狱人口补助金    [Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=227085867)
#### Murgh DevTools (Continued)/Murgh 开发工具(续)    [Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=3019052572)
#### No More Water!/无需水源    [Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=2514307311)
#### No More Power!/无需电力    [Steam模组页面](https://steamcommunity.com/sharedfiles/filedetails/?id=2514307414)


