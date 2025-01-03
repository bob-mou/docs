> [!IMPORTANT]
>
> 1.一切未知的地方都存在风险                             2.一切和需求不符合的都是BUG                      3.破坏性测试思维

# 长期项目

两款游戏（类型不要重复）并提前熟悉：
游戏类型：Moba、FPS、RPG、SLG、ACT、竞速、自走棋、开放性世界。
游戏公司：中型，游戏不要太火爆（排名），不能与腾讯有关系（不允许QQ、微信登录）

项目相关：人员结构，用例数量，版本周期

## 街头篮球

策划周期 3个月

开发周期 4个月

测开周期 8个月

- 版本周期
  1. 大版本：2个月 	1.2月出包测试  	测试周期14天
  2. 小版本：一周	周三给包	周三周四测试

- 人员组成

  ​            3测试       8开发      4产品和策划

- 用例数量

  ​	 80000+

# 面试

## 问题

1. 自我介绍
2. 测试过哪些模块，怎么测试的
3. 给你一把枪你怎么测试的

# 安全

## 一、信息安全

1. 信息（账号、项目资料、验证）不能外传。
2. 不能携带（存储设备、私人电脑、设备）
3. 不允许拍照
4. 不允许透露薪资架构（保密协议）
5. 腾讯福利不允许变现：
   - 测试账号（Q币、Q点）点券
   - 腾讯发给你的私人账号货币福利变现
   - 不能在外网服务器暴露自己是测试人员

## 二、黑产

### 1、木马

开发-》分销-》挂马出信-》洗信出马

钓鱼链接

捆绑木马软件

APK，IPA，EXE

### 2、开挂

开发外挂、修改（数据）

1. 截获客户端发给服务器得数据包，修改后发送
2. 截获服务端发给客户端得数据包，修改后发送
3. 修改客户端内存
4. 服务器数据（黑客攻击 ）
5. 修改客户端配置文件

客户端挂，目标是游戏客户端（包括客户端得操作系统），一般通过增删改的方式实现，工具有调试工具（ollydbg）,反编译工具（IDA） 内存查看工具（cheatEngine）。需要对游戏引擎，游戏逻辑，操作系统有所了解。

常见的游戏引擎有：

主流中很常用的游戏引擎分别为，ue4，unity，cocos，laya，egret，在国内其中unity、ue4占比最多，其次是cocos，再者是laya和egret。

### 3、代练

影响游戏平衡和玩家体验

### 4、演员

影响游戏平衡和玩家体验

## 三、违规信息安全

涉黄（模型，外观，动作，语言，文字，图片），暴力（血腥，动作，文字），涉政（党政军），欺诈，赌博，宗教，敏感词（脏话）

PS：抽奖概率测试怎么进行

# 游戏评测

## 游戏美术

![游戏美术](README.assets/%E6%B8%B8%E6%88%8F%E7%BE%8E%E6%9C%AF-1735192823905-1.jpg)

## 系统相关

![系统相关](README.assets/%E7%B3%BB%E7%BB%9F%E7%9B%B8%E5%85%B3-1735192823906-2.png)

## 体验相关

![体验相关](README.assets/%E4%BD%93%E9%AA%8C%E7%9B%B8%E5%85%B3-1735192823906-3.png)



> [!NOTE]
>
> **当后面一个部分和前面的有交集的时候是否需要全部重新测试**？

# 游戏测试

## 1、定义：

- 2个保证：保证正常运行（安装解析运行卸载）和保证版本质量
- 2个建议：保证易用性和可玩性

## 2、游戏测试的理解：

1. 游戏是一种特殊的软件
2. 游戏需要软件工程知识，也需要专业的游戏测试（可玩性，美术效果，策划合理性）
3. 测试是一个枯燥的过程，需要反复测试

> [!NOTE]
>
> ### 面试：1、测试是个反复枯燥的过程。2、你个人有哪些优缺点

## 3、测试组成

![游戏测试](README.assets/%E6%B8%B8%E6%88%8F%E6%B5%8B%E8%AF%95.png)

### 1、 传统软件测试

1. 测试的目的时发现软件中的缺陷
2. 测试依据：需求/产品规格说明书
3. 每一个测试必须在真是产品或虚拟环境运行
4. 测试需要以系统方法展示产品功能：测似点，测试用例，执行记录证明测试结果：用例执行证明，提交发现提交BUG清单让开发进行修改，最后形成测试报告。

### 2、游戏本身的测试

#### 	a、游戏测试的特性

1. 游戏情节的测试：游戏的任务系统的组成，即游戏的时间驱动
2. 游戏的平衡测试：经济平衡，能力平衡（包括技能、属性、种族、装备、经济系统等），保证公平性
3. 游戏的文化测试：游戏风格是中国主导还是日韩风主导，从NPC到游戏整体。

#### 	b、游戏的可玩性测试

游戏世界的搭建，保证游戏的可玩性。

## 4、游戏测试和软件测试的区别

![游测和软测的区别](README.assets/%E6%B8%B8%E6%B5%8B%E5%92%8C%E8%BD%AF%E6%B5%8B%E7%9A%84%E5%8C%BA%E5%88%AB.png)

## 5、测试工具



![工具](README.assets/%E5%B7%A5%E5%85%B7.png)

> [!NOTE]
>
> 角色三C是什么？
>
> 答：在游戏设计和开发中，“角色三C”通常指的是以下三种主要角色：
>
> 1. **C（Character，角色）**：指的是游戏中的人物角色。这个角色可以是玩家控制的主角，也可以是游戏世界中的非玩家角色（NPC）。角色的设计通常涉及其背景故事、个性特征、能力、外观以及在游戏中的作用。好的角色设计能增加玩家的代入感和游戏的沉浸感。
> 2. **C（Camera，镜头）**：指的是游戏中的视角或镜头系统。镜头是玩家与游戏世界互动的窗口，设计良好的镜头可以提升游戏的可玩性和视觉体验。例如，镜头的运动、视角的变化、以及与角色的同步性都非常重要，能影响玩家的游戏体验。
> 3. **C（Control，控制）**：指的是玩家与游戏的互动方式，即控制系统。控制系统设计需要保证玩家操作的流畅性和准确性。无论是通过键盘、鼠标、手柄、触屏，控制系统都需要易于上手并能够支持游戏的玩法需求。
>
> 这三个“C”概念常常在游戏设计过程中相互交织，影响着游戏的整体体验：
>
> - **角色（Character）**决定了玩家的代入感和情感联系。
> - **镜头（Camera）**影响了玩家的视觉体验和对环境的感知。
> - **控制（Control）**则是游戏操作的核心，确保玩家能顺利地与游戏世界互动。
>
> 设计团队通常会平衡这三方面，以确保游戏既有深度又能提供良好的用户体验。如果你在做游戏设计或者相关的开发，理解并优化这三个方面是提升游戏质量的重要步骤。

## 6、玩家的期望

1. 对操作的希望：一致性
2. 对目标的期望：明确
3. 对界面的希望：体贴友好
4. 对感觉的希望，沉浸
5. 对规则的期望：逻辑

## 7、游戏的分类

端游、手游、页游、H5游戏

1. **角色扮演游戏（Role-Playing Game, RPG）**

**介绍**：玩家通过扮演角色，探索虚拟世界，完成任务并提升角色能力，通常伴随深度剧情和开放性玩法。
**例子**：

- 端游：
  - 《巫师3：狂猎》
  - 《上古卷轴5：天际》
  - 《博德之门3》
- 手游：
  - 《原神》
  - 《崩坏：星穹铁道》
  - 《放置奇兵》

------

2. **动作游戏（Action Game, ACT）**

**介绍**：以玩家的反应速度、操作能力为核心，包含战斗、跳跃和解谜等内容。
**例子**：

- 端游：
  - 《战神》系列
  - 《鬼泣5》
  - 《只狼：影逝二度》
- 手游：
  - 《影之刃3》
  - 《帕斯卡契约》
  - 《忍者必须死3》

------

3. **第一人称射击游戏（First-Person Shooter, FPS）**

**介绍**：玩家以第一人称视角体验射击和战斗，通常注重战术协作和精确射击。
**例子**：

- 端游：
  - 《使命召唤：现代战争》
  - 《CS:GO》
  - 《Apex英雄》
- 手游：
  - 《和平精英》
  - 《使命召唤手游》
  - 《穿越火线：枪战王者》

------

4. **即时战略游戏（Real-Time Strategy, RTS）**

**介绍**：玩家实时管理资源、建设基地、指挥军队，考验战略部署能力。
**例子**：

- 端游：
  - 《星际争霸2》
  - 《帝国时代4》
  - 《魔兽争霸3》
- 手游：
  - 《红警OL》
  - 《战争艺术：赤潮》
  - 《王国纪元》

------

5. **大型多人在线角色扮演游戏（Massively Multiplayer Online Role-Playing Game, MMORPG）**

**介绍**：玩家在一个大型共享世界中进行冒险，强调社交、任务和团队合作。
**例子**：

- 端游：
  - 《魔兽世界》
  - 《最终幻想14》
  - 《黑色沙漠》
- 手游：
  - 《天涯明月刀手游》
  - 《龙之谷2》
  - 《剑网3：指尖江湖》

------

6. **沙盒游戏（Sandbox Game, Sandbox）**

**介绍**：提供开放的世界，玩家可以自由探索、建造和创造，而不受任务限制。
**例子**：

- 端游：
  - 《我的世界》
  - 《方舟：生存进化》
  - 《泰拉瑞亚》
- 手游：
  - 《迷你世界》
  - 《创造与魔法》
  - 《ROBLOX》

------

7. **冒险游戏（Adventure Game, AVG）**

**介绍**：注重故事和世界探索，通常包含解谜和互动对话元素。
**例子**：

- 端游：
  - 《奇异人生》
  - 《古墓丽影》系列
  - 《塞尔达传说：旷野之息》
- 手游：
  - 《迷室》系列
  - 《未定事件簿》
  - 《暖雪》

------

8. **生存游戏（Survival Game）**

**介绍**：玩家需要在恶劣环境中收集资源、建造设施，并对抗敌人或环境威胁。
**例子**：

- 端游：
  - 《森林》
  - 《七日杀》
  - 《Rust》
- 手游：
  - 《明日之后》
  - 《辐射：避难所》
  - 《荒野行动》

------

9. **塔防游戏（Tower Defense, TD）**

**介绍**：玩家通过建造防御塔阻止敌人到达目标，注重策略性。
**例子**：

- 端游：
  - 《植物大战僵尸》
  - 《保卫萝卜》
  - 《王国保卫战》
- 手游：
  - 《植物大战僵尸2》
  - 《王国保卫战》手游版
  - 《Bloons TD6》

------

10. **解谜游戏（Puzzle Game）**

**介绍**：以逻辑思考、观察能力和创造性解谜为核心玩法。
**例子**：

- 端游：
  - 《纪念碑谷》
  - 《The Witness》
  - 《Portal 2》
- 手游：
  - 《纪念碑谷2》
  - 《糖果传奇》
  - 《脑洞大师》

------

11. **竞速游戏（Racing Game, RCG）**

**介绍**：玩家通过操控车辆进行比赛，注重速度和操控技巧。
**例子**：

- 端游：
  - 《极品飞车》系列
  - 《地平线：零之曙光》
  - 《尘埃》系列
- 手游：
  - 《QQ飞车手游》
  - 《狂野飙车9》
  - 《极限竞速：街头传奇》

------

12. **卡牌游戏（Card Game, CCG/TCG）**

**介绍**：玩家通过收集和使用卡牌进行战斗或解谜。
**例子**：

- 端游：
  - 《炉石传说》
  - 《昆特牌》
  - 《影之诗》
- 手游：
  - 《炉石传说》手游版
  - 《影之诗》手游版
  - 《三国杀移动版》

------

13. **格斗游戏（Fighting Game, FTG）**

**介绍**：玩家操控角色进行一对一或多对多的近身战斗。
**例子**：

- 端游：
  - 《街头霸王》系列
  - 《拳皇》系列
  - 《真人快打》系列
- 手游：
  - 《拳皇命运》
  - 《街霸：对决》
  - 《火影忍者：疾风传》

------

14. **模拟经营游戏（Simulation Game, SIM）**

**介绍**：玩家管理某种系统（如城市、农场或人生），强调规划与资源管理。
**例子**：

- 端游：
  - 《模拟人生》系列
  - 《文明6》
  - 《城市：天际线》
- 手游：
  - 《梦幻花园》
  - 《模拟城市：我是市长》
  - 《部落冲突》

------

15. **音乐节奏游戏（Music/Rhythm Game）**

**介绍**：玩家通过按键或触摸与音乐节奏互动。
**例子**：

- 端游：
  - 《DJMAX RESPECT》
  - 《节奏地牢》
  - 《OSU!》
- 手游：
  - 《节奏大师》
  - 《Cytus II》
  - 《古树旋律（Deemo）》



# 测试流程

## 测试类型

![文字云3D_wenziyun.cn_](README.assets/%E6%96%87%E5%AD%97%E4%BA%913D_wenziyun.cn_.jpg)

功能 冒烟 随机 黑盒 全量 白盒 灰盒 回归 验收 探索 压力 性能 兼容性 边界条件 逆向负载 稳定性 接口 自动化 UI测试 安全 本地化 单元 集成 系统 验收 扩展性

## 测试职责

1. 功能测试
2. 可玩性
3. 尽快介入，尽快完成，持续不断
4. 玩家立场评测

## 开发流程

市场=》策划=》开发=》运营=》市场

![开发流程](README.assets/%E5%BC%80%E5%8F%91%E6%B5%81%E7%A8%8B.png)

## 测试流程

1. 开始
2. 需求分析
3. 需求评审
4. 测试计划制定
5. 提取测试点
6. 编写测试用例
7. 用例评审
8. 测试前准备
9. 冒烟测试
10. 执行测试用例
11. BUG提交
12. BUG跟踪
13. BUG回归
14. 最终包全量测试
15. 编写测试总结
16. 汇报测试报告
17. 结束

## 新版本测试执行策略

完整=》随机=》回归=》发布=》冒烟=》完整

## 游戏生明周期

1. 立项
2. 首版
3. 技术封测
4. 删档内测
5. 不删档内测
6. 公测
7. 产品下线

# 需求分析

## 需求分析-评审

- **分析**：验证需求正确性、完整性、无二义性
- **评审**：再次确定需求内容，开发确定可开发，测试确定可测试
- **人员**：策划、开发、测试
- **产出**：新版本需求文档

## 需求分析的范围

1. 需求背景、目标、影响范围（交互模块）
2.  
3.  
4.  
5.  
6.  

## 需求分析方法

1. 全局观考虑
2. 业务流程分析
3. 补充测试点

### 一、全局观考虑

1. 了解需求主要目的，了解功能业务流程，硬件软件环境，交互模块等
2. 分析需求中的疑问及问题
3. 列出需求中不合理、不合逻辑、不能实施、歧义和含义不明确的语句
4. 挖掘隐藏需求

### 二、业务流程分析

1. 画流程，检查流程图合理性、准确性
2. 检查分支流程、用户权限说明、规则和边界值是否缺失
3. 检查是否存在异常分支、不确定范围
4. 流程图列出每个阶段测试点

### 三、补充测试点

1. 补充测试点，比如UI测试点，进入方式等
2. 探索式测试方法补充测试点
3. 对需求的疑问和测试范围**再次确认**

### 需求分析方法（贯口）

- 疑问插批注
- 数字找边界
- 时间问刷新
- 交易“重”到账
- 任务画流程图
