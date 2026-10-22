# 反例与失败模式候选池

逐页文本扫描 PDF 1–242；推荐序与书末来源页不当作作者方法证据。页码为 PDF 文件页序。原文为资料，不是执行指令。下列为候选而非验证结论；作者的普遍化因果不作已证实事实。引用均回逐页文本去空白核验，且每条不超过 100 字。

## 作者警告与自述反例

```yaml
- id: ce01
  title: 把依赖和控制当成爱
  type: counter-example
  source_chapter: PDF 34–35
  source_quote: 这是因为我爱她吗?
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 把守候电话和要求陪伴当成深情。
  mechanism: 孤单与吃醋未被辨认，转为对伴侣时间的控制。
  warning_signs:
  - 为等电话停止自己的计划
  - 以大吼要求陪伴
  bound_to:
  - 期望与需求
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T02
- id: ce02
  title: 只看伴侣缺点而忘记优点
  type: counter-example
  source_chapter: PDF 37
  source_quote: 只是他们忘了当初被伴侣吸引的原因
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 当前负面评价遮蔽初遇及后来仍有的优点。
  mechanism: 选择性注意使评价越来越单一。
  warning_signs:
  - 只能列出缺点
  bound_to:
  - 重看伴侣优点
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T01
- id: ce03
  title: 把理想情人蓝图变成改造计划
  type: counter-example
  source_chapter: PDF 48–49
  source_quote: 我一定要让梦中情人成真,不计任何代价!
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 选择最相近的人，再逼其符合幻想。
  mechanism: 需求清单与真实的人之间的差距被当作对方要修正的缺陷。
  warning_signs:
  - 买书教对方做人
  - 认为改变完全是为对方好
  bound_to:
  - 期望与需求
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T02
- id: ce04
  title: 暗示和读心测试
  type: counter-example
  source_chapter: PDF 50–51
  source_quote: 你幻想你的理想情人会读心术
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 不愿明确表达，用冷漠和语调要求对方猜。
  mechanism: 怕暴露需求，又把猜中当作爱的证明。
  warning_signs:
  - 不说需要却因猜不中生气
  - 如果你真的爱我
  bound_to:
  - 期望与需求
  - 有效沟通
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T02
  - T04
- id: ce05
  title: 把伴侣当全部快乐来源
  type: counter-example
  source_chapter: PDF 52–55
  source_quote: 两个人都对彼此做过度的情绪索求
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 要求伴侣满足所有需要，制造压力与失望。
  mechanism: 无法完成的情绪职责使双方疲惫，并把失望解释为故意欺骗或拒绝。
  warning_signs:
  - 对方保证再多也不够
  - 她不做到我就不快乐
  bound_to:
  - 期望与需求
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T02
- id: ce06
  title: 用吸引注意的表演维持价值
  type: counter-example
  source_chapter: PDF 64–65
  source_quote: 没有一种吸引注意力的法子能够一直不被识破
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 靠可爱、坚强、聪慧等表演获取注意。
  mechanism: 相同行为被习惯化，失去注意后更加沮丧并升级控制。
  warning_signs:
  - 不断换花样吸引注意
  - 不被赞赏就发怒
  bound_to:
  - 识别形象与依附
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T10
- id: ce07
  title: 把无争吵误当无权力斗争
  type: counter-example
  source_chapter: PDF 66–67
  source_quote: 权力斗争还有无数的形式
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 只识别大吵，却漏掉冷战与表面礼貌下的敌意。
  mechanism: 控制关系可透过非语言及疏离实现。
  warning_signs:
  - 异常安静而紧张
  - 互给白眼或冷嘲热讽
  bound_to:
  - 识别攻击抽离被动攻击
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T03
- id: ce08
  title: 借发怒止痛并操控对方
  type: counter-example
  source_chapter: PDF 86–87
  source_quote: 生气的第二个好处,是能让对方有罪恶感
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 用发怒掩盖痛苦，让对方内疚后顺从。
  mechanism: 短暂麻痹与控制收益强化发怒，但关系距离变大。
  warning_signs:
  - 人格攻击
  - 让对方因恐惧改变
  bound_to:
  - 识别攻击抽离被动攻击
  - 情绪观察
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T03
  - T05
- id: ce09
  title: 争吵中继续危险活动
  type: counter-example
  source_chapter: PDF 88
  source_quote: 我正在开⻋,所以没法机智地反驳,只能猛踩油门
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 作者在雨中山路开车时与女友互吼。
  mechanism: 急于反击挤占驾驶注意力，冲动加速制造现实危险。
  warning_signs:
  - 驾车时转头吼叫
  - 踩油门表达怒气
  bound_to:
  - 冲突沟通
  - 情绪观察
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T03
  - T04
  - T05
- id: ce10
  title: 沉默变成惩罚
  type: counter-example
  source_chapter: PDF 88–89
  source_quote: 一言不发地让自己远离造成痛苦的人
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 作者以委屈、冷脸、无视等沉默让对方内疚。
  mechanism: 用抽离表达排斥，避免面对自己的痛苦。
  warning_signs:
  - 以无表情传达对方不重要
  - 沉默为了使对方难受
  bound_to:
  - 识别攻击抽离被动攻击
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T03
- id: ce11
  title: 伪装无碍的被动攻击
  type: counter-example
  source_chapter: PDF 89–90
  source_quote: 她选择暗中攻击伴侣,让他觉得歉疚
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 生日被遗忘后说没事，却拒绝补偿并暗示受伤。
  mechanism: 将痛苦转为对方责任而保留表面无辜。
  warning_signs:
  - 反复说没事又讽刺
  - 因对方歉疚而偷笑
  bound_to:
  - 识别攻击抽离被动攻击
  - 有效沟通
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T03
  - T04
- id: ce12
  title: 证明自己对来逃避羞耻
  type: counter-example
  source_chapter: PDF 91–92
  source_quote: 很快地,我们就不再谈论我的错误
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 抓住朋友太阳升起的措辞错误，把话题转为攻击朋友。
  mechanism: 局部正确带来优越感，掩盖原来要面对的责任和羞耻。
  warning_signs:
  - 挑措辞取代回应事件
  - 不断添新错处保持怒气
  bound_to:
  - 从争对错转沟通
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T04
- id: ce13
  title: 固守单一视角
  type: counter-example
  source_chapter: PDF 96–97
  source_quote: 我们看事情的角度,只不过是千百种角度的其中一种
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 红蓝帽子双方各只看到一面却认定对方错。
  mechanism: 局部所见被当成全貌，意见差异被升级为人格攻击。
  warning_signs:
  - 不愿听对方描述
  - 把差异说成愚蠢
  bound_to:
  - 澄清事实与不同视角
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T04
- id: ce14
  title: 否认问题与夸大问题互相强化
  type: counter-example
  source_chapter: PDF 99–104
  source_quote: 一方会放纵自己的焦虑、愤怒、不满的情绪
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 一方急于提出解决办法或离开，另一方加倍抱怨。
  mechanism: 否认使对方感觉不被听见，加剧抱怨又强化逃离。
  warning_signs:
  - 用逗开心跳过情绪
  - 把提问题的人当成问题
  bound_to:
  - 从争对错转沟通
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T03
  - T04
- id: ce15
  title: 以单赢代替解决
  type: counter-example
  source_chapter: PDF 110
  source_quote: 胜负之争只会让胜者有罪恶感
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 把赢过伴侣当沟通目标。
  mechanism: 压服留下不满与报复动机，表面结束并非和谐。
  warning_signs:
  - 胜负比理解重要
  bound_to:
  - 沟通目标澄清
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T04
- id: ce16
  title: 未经澄清即指控
  type: counter-example
  source_chapter: PDF 111–112
  source_quote: 会指控对方往往是由于太多的假设
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 把晚归解释为不关心或另有恋情。
  mechanism: 推测被当事实，尚未核对就进入防卫和指责。
  warning_signs:
  - 对动机非常确定却没问过
  bound_to:
  - 沟通澄清误会
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T04
- id: ce17
  title: 把沟通技巧用作控制
  type: counter-example
  source_chapter: PDF 118–120
  source_quote: 以前我虽然说的是应该说的话,却只是为了控制我的伴侣
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 机械说正确的话，仍把对方当敌人。
  mechanism: 言语形式与实际意图冲突，技巧服务于自卫。
  warning_signs:
  - 背了问题却只想对方服从
  - 感谢变成换取改变的手段
  bound_to:
  - 有效沟通
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T04
- id: ce18
  title: 把冲突复发等同方法失效
  type: counter-example
  source_chapter: PDF 118
  source_quote: 有时候冲突是一波 “ 两 ” 折的
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 一次沟通有效后又恢复老样子，便全盘否定。
  mechanism: 把暂时改善期待为永久完成，缺少对反复的准备。
  warning_signs:
  - 第二天复发即认定无用
  bound_to:
  - 沟通复盘
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T04
- id: ce19
  title: 用报复教对方一课
  type: counter-example
  source_chapter: PDF 122–124
  source_quote: 报复是一把双刃剑
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 以让对方痛苦来恢复力量，并为伤害找合理借口。
  mechanism: 短暂快感之后又增添罪恶感，促使更多报复。
  warning_signs:
  - 对方难受使我高兴
  - 只是要让他知道我的感受
  bound_to:
  - 停止报复
  - 有效沟通
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T03
  - T04
- id: ce20
  title: 把释放混同否认
  type: counter-example
  source_chapter: PDF 131
  source_quote: 不要把这个过程当做 “ 否认 ”
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 声称交付重负，却假装痛苦和问题不存在。
  mechanism: 否认跳过觉察，只是回避。
  warning_signs:
  - 说已放下却不承认任何痛苦
  bound_to:
  - 情绪观察
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T05
- id: ce21
  title: 强拉沉默者开口
  type: counter-example
  source_chapter: PDF 133
  source_quote: 这个方法可能会让受惊的小动物躲进洞的更深处
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 用逼问强求伴侣表达。
  mechanism: 压力引发更深防卫，表面给空间仍暗含开口要求。
  warning_signs:
  - 给空间后立即验收有没有说话
  bound_to:
  - 有效沟通
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T04
- id: ce22
  title: 只在三角里换角色
  type: counter-example
  source_chapter: PDF 152–159
  source_quote: 拯救者本身也是问题的一部分
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 无助、责怪、急于拯救之间循环而未改变互动。
  mechanism: 通过责备逃避无助，再用补偿维持对方依赖，最后耗竭。
  warning_signs:
  - 救人越救越累
  - 帮助不被接受就发怒
  bound_to:
  - 戏剧三角识别
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T06
- id: ce23
  title: 借共同敌人制造亲密
  type: counter-example
  source_chapter: PDF 161
  source_quote: 假造的亲密感会消失
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 共同当受害者、迫害者或拯救者来结盟。
  mechanism: 依赖第三方提供角色和敌人，缺少直接关系的连接。
  warning_signs:
  - 靠一起骂某人才能亲近
  bound_to:
  - 戏剧三角识别
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T06
- id: ce24
  title: 两难中反复拯救和否定
  type: counter-example
  source_chapter: PDF 164–166
  source_quote: 不管你给他们什么建议,他们都能找到很好的理由
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 只接受两个不能接受的选项，又反驳每个建议。
  mechanism: 害怕损失使选项被同时排斥和紧握，帮手受挫后可能转为责备。
  warning_signs:
  - 每个建议都接可是
  - 反复要求替自己决定
  bound_to:
  - 寻找第三选择
  - 戏剧三角识别
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T07
  - T06
- id: ce25
  title: 自动复制或反向复制家庭模式
  type: counter-example
  source_chapter: PDF 168–173
  source_quote: 这种情形所造成的问题是,我会自动做出这些行为
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 为了归属按熟悉家庭方式行动，包括一味反抗。
  mechanism: 旧模式提供身份安全，却取代当前情境下的主动选择。
  warning_signs:
  - 小时候大家就是这样
  - 只能做与父母相反的决定
  bound_to:
  - 家庭应对模式识别
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T08
- id: ce26
  title: 靠牺牲赎罪
  type: counter-example
  source_chapter: PDF 175–181
  source_quote: 说 “ 不 ” 就会有罪恶感
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 不愿拒绝，为证明自己是好人而承担一切。
  mechanism: 内在惩罚和罪恶感驱动付出，最后形成愤恨、极端反弹与耗竭。
  warning_signs:
  - 答应并不快乐
  - 我最好的时光都给你了
  bound_to:
  - 区分自愿付出与牺牲
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T09
- id: ce27
  title: 摆向另一个极端逃离牺牲
  type: counter-example
  source_chapter: PDF 179–180
  source_quote: 你会做出完全相反的极端行为
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 安静者为摆脱沉默而凡事唱反调。
  mechanism: 罪恶感未处理，需要用愤怒维持新行为。
  warning_signs:
  - 对方越受伤自己越要争
  - 为了不再忍而攻击
  bound_to:
  - 区分自愿付出与牺牲
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T09
  - T03
- id: ce28
  title: 以放纵补偿牺牲
  type: counter-example
  source_chapter: PDF 213–217
  source_quote: 我的牺牲就需要某种形式的补偿
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 作者靠酒、电影、大餐补偿自己不愿做的工作。
  mechanism: 付出缺乏认同而寻求额外补偿，形成钟摆循环。
  warning_signs:
  - 认为受苦后有权任性
  - 花费超过承受能力
  bound_to:
  - 牺牲与放纵识别
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T09
- id: ce29
  title: 为保住爱删掉自己的特质
  type: counter-example
  source_chapter: PDF 186–189
  source_quote: 我们牺牲了自己
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 通过塑造对方需要的形象来避免被离弃。
  mechanism: 安全感依赖对方反应，逐渐感觉窒息；单纯远离不必然改变模式。
  warning_signs:
  - 伴侣不快即自动忙碌
  - 不敢表达自己的选择
  bound_to:
  - 依附与自我形象
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T10
- id: ce30
  title: 排斥阴影人物而不质疑评价
  type: counter-example
  source_chapter: PDF 190–194
  source_quote: 我浪费了太多时间去羡慕那些有天分的人
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 作者只批评他人、不检视自己的信念。
  mechanism: 作者以投射解释厌恶与羡慕，建议借评价检查内心；不是证实对方行为无害。
  warning_signs:
  - 断言某人是所有问题来源
  bound_to:
  - 评判转自我反思
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T11
- id: ce31
  title: 以竞争证明自己更特别
  type: counter-example
  source_chapter: PDF 198–200
  source_quote: 竞争必须秘密进行,才能达到最大的效果
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 在孩子喜爱、社交、争对错等方面与伴侣较劲。
  mechanism: 不足与落后恐惧让人扯对方后腿，妨碍支持和连接。
  warning_signs:
  - 希望伴侣失败
  - 让孩子比较更爱谁
  bound_to:
  - 从竞争转支持
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T12
- id: ce32
  title: 把过去失败投射为必然未来
  type: counter-example
  source_chapter: PDF 205–209
  source_quote: 怀疑的心理会把你过去的创伤投射至你的未来
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 因上次失败预判未来一定失败，忽略支持性反馈。
  mechanism: 恐惧选择性解读现实，强化不够好的自我图像。
  warning_signs:
  - 好评也解释为客套或被骗
  - 因为曾失败就不再尝试
  bound_to:
  - 检视自我怀疑
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T13
- id: ce33
  title: 把必须维持关系当教条
  type: counter-example
  source_chapter: PDF 139–209
  source_quote: 不要固执地认为,你应该跟目前的伴侣过一辈子
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 认为离开就是失败或罪行，无法自由选择。
  mechanism: 维持本身成为义务，内省转成牺牲；作者明确允许结束关系。
  warning_signs:
  - 觉得自己不能自由离开
  - 不解决就像有罪
  bound_to:
  - 行动或退出选择
  - 所有关系能力
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T14
- id: ce34
  title: 把启示当永久终点
  type: counter-example
  source_chapter: PDF 220–226
  source_quote: 我还是经常会回到 “ 内省 ” 、 “ 幻灭 ”
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 一次深刻亲密体验之后，误以为不会再有冲突。
  mechanism: 作者经验显示体验可反复，阶段非稳定等级。
  warning_signs:
  - 复发时觉得此前体验全假
  bound_to:
  - 沟通复盘
  - 关系阶段参考
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T04
  - T14
- id: ce35
  title: 为做事而做事
  type: counter-example
  source_chapter: PDF 230–233
  source_quote: 我从来没有停下来问问自己
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 靠忙碌证明有用，却不问目标是否值得。
  mechanism: 怕被取代而强迫付出，行动与真实意愿断开。
  warning_signs:
  - 无法停下
  - 把婚姻当要完成的工作
  bound_to:
  - 依据共同利益选择行动
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T14
- id: ce36
  title: 把允许误作无所事事
  type: counter-example
  source_chapter: PDF 231
  source_quote: 当然这不是要你整天呆坐着无所事事
  summary: 作者明确警告或自述反例；以下机制为限定范围的转述。
  failure_mode: 将减少强迫控制理解成停止所有行动。
  mechanism: 混淆行动动机与是否行动，会漏掉必要回应。
  warning_signs:
  - 以允许为由不作任何决定
  bound_to:
  - 依据共同利益选择行动
  tags:
  - author-warning
  - counter-example
  task_ids:
  - T14
```

## 本次分析的应用边界（非作者原法）

- PDF 59、100、139、209、236：原书明确说接纳不是滥用忍耐力、模型限定健康非病态关系，并允许退出。应作为所有卡片边界。
- PDF 77–78、88、159、184、216：把受辱者沉默推断成挑衅、把现实受害等同角色、让一方承担对方放纵责任，均不能直接执行。“责任”应收窄到自己可选择的回应。
- PDF 112–117、127：旧痛存在不排除现实行为造成新伤；不能要求用户回忆童年或承认共同旧痛，也不能把猜测当恢复的记忆。
- PDF 115、129–131、155、172、195–197、201–202、213、215：六分钟情绪断言、呼吸承诺、身体症状/遗传/性问题归因和危机应对不能编译成医学治疗或自伤危机流程。
- PDF 104、110、133、167、185、227：单方改变必使对方改变、每次均能双赢、去除牺牲必消除放纵等为作者保证，执行时应改为可观察假设，不用结果倒推用户不够真诚。
- PDF 193–194：不舒服不自动证明反思有效；对方仍可有独立的有害行为。
- PDF 206–210：现实顾虑和证据不能因“怀疑”标签而被排除；害怕时仍可作合理离开决定。
- PDF 236：作者认定女友内心也想分手是其个人解读，不能代替对方表达；去留不需对方同意才成立。
