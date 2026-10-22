# 框架候选池（未筛选）

扫描：PDF 1–242逐页文本（含前言、发布会、摘要、附注、感谢及末页），分批读取；有截断批次已补读缺段。以下均记录作者所提方法，不声称有效。主代理已视觉核查九图；下列图示缺口已据此更新。task_ids 为阶段0任务对照。

```yaml
[
  {
    "id": "f01",
    "title": "优缺点双表重新看见伴侣",
    "type": "procedure",
    "source_chapter": "PDF文件页序 37（1起算）",
    "source_quote": "写下初遇时,你在伴侣身上发现的所有优点,相处至今新发现的优点,也加上去。",
    "summary": "作者提出：分列优点与当前缺点，以每项正负十分对照，提醒自己是否忘记优点。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T01"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "列初遇及后来发现的优点",
      "另列目前看见的缺点",
      "每项优点+10、缺点-10并合看双表"
    ],
    "missing_conditions": "等权分数没有关系去留的判定效力；重大伤害不能由优点抵消。"
  },
  {
    "id": "f02",
    "title": "期望—情绪需求—放手循环",
    "type": "procedure",
    "source_chapter": "PDF文件页序 55–57（1起算）",
    "source_quote": "希望伴侣改变或做些什么是一种期望,而不是你自身的需求。",
    "summary": "作者提出：不满意时追问想要伴侣给什么，将行为要求转成关注、价值等情绪需求，再检视是否愿意不把满足它当作伴侣职责。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T02"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "问此刻想从伴侣身上得到什么",
      "若答案是做或不做某事，再问直至识别情绪需求",
      "问是否愿意放下这项期望",
      "察看自己是否更轻松、感到爱交流；未放下或浮出下一层期望则重复"
    ],
    "missing_conditions": "原书以直觉和主观轻松作核验，未区分合理约定与情绪索求；放手不代表取消守约责任。"
  },
  {
    "id": "f03",
    "title": "四类偏差行为观察模型",
    "type": "framework",
    "source_chapter": "PDF文件页序 64–65、127（1起算）",
    "source_quote": "她指出了四种主要的偏差行为:",
    "summary": "作者提出：借用尼尔森模型，将引起注意、权力斗争、报复、自我放逐看成需求不满后的应对路径。",
    "tags": [
      "relationship",
      "self-reflection",
      "framework"
    ],
    "task_ids": [
      "T03",
      "T06"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "记录当前行为",
      "与四种行为及其目的比较",
      "检视是否在用控制对方避免失望"
    ],
    "missing_conditions": "这是作者的解释模型，不能据单次行为推断动机或诊断。"
  },
  {
    "id": "f04",
    "title": "旧痛与限制信念形成链",
    "type": "mental-model",
    "source_chapter": "PDF文件页序 70–76、81–85（1起算）",
    "source_quote": "单一的痛苦事件只是种子,但之后类似的经验,便会让自我局限的信念茁壮成长。",
    "summary": "作者提出：把事件、儿童诠释、重复想法、限制信念、当前触发相连，解释关系冲突为何超过眼前议题。",
    "tags": [
      "relationship",
      "self-reflection",
      "mental-model"
    ],
    "task_ids": [
      "T04",
      "T05",
      "T08"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "识别眼前导火线及感受",
      "回看自己确实记得的相似经验",
      "区分当时发生的事与对自己的诠释",
      "检视诠释如何成为持续信念"
    ],
    "missing_conditions": "书中旧痛优先因果论未证实；不能诱导回忆或认为所有当前伤害都源于童年。"
  },
  {
    "id": "f05",
    "title": "愤怒三种表达的自查",
    "type": "framework",
    "source_chapter": "PDF文件页序 86–90（1起算）",
    "source_quote": "在权力斗争中,愤怒有三种表达方式:攻击、情绪抽离,或被动攻击。",
    "summary": "作者提出：用三种形式观察自己如何远离痛苦或使对方内疚，转向对自己感受负责。",
    "tags": [
      "relationship",
      "self-reflection",
      "framework"
    ],
    "task_ids": [
      "T03",
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "记录自己的具体言行",
      "辨认明显攻击、沉默疏远、暗中讽刺等形式",
      "问这种方式在回避什么痛苦",
      "选择面对感觉而不攻击伴侣"
    ],
    "missing_conditions": "沉默、眼泪不能单独证明操控；书中的全部攻击出于自卫不可当事实。"
  },
  {
    "id": "f06",
    "title": "放下单一视角的红蓝帽模型",
    "type": "framework",
    "source_chapter": "PDF文件页序 96–97（1起算）",
    "source_quote": "放下自己的立场,从对方的角度来看一看",
    "summary": "作者提出：双方描述不同未必是谁说谎，可换位并综合所见。",
    "tags": [
      "relationship",
      "self-reflection",
      "framework"
    ],
    "task_ids": [
      "T04"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "陈述自己实际看到的部分",
      "了解对方角度可看见什么",
      "综合两个视角修正描述"
    ],
    "missing_conditions": "需区分视角差异与可核查事实、欺骗；不是所有冲突都双方各对一半。"
  },
  {
    "id": "f07",
    "title": "正反方协作迭代方案",
    "type": "procedure",
    "source_chapter": "PDF文件页序 98–100、132–133（1起算）",
    "source_quote": "反方会发现问题,并把它提出来讨论,正方则会在聆听之后,想出解决的方法。",
    "summary": "作者提出：将发现风险与发现可能性分成互补功能，通过批评方案及修改迭代。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T04"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "一方提出问题",
      "另一方倾听并提出解决办法",
      "指出方案问题",
      "修正方案并重复至较佳方案"
    ],
    "missing_conditions": "图一已经主代理视觉核查；不可把两方变成人格标签，书中健康非病态关系限定见PDF100。"
  },
  {
    "id": "f08",
    "title": "有效沟通八问完整流程",
    "type": "procedure",
    "source_chapter": "PDF文件页序 109–117、128（1起算）",
    "source_quote": "有没有什么误会要先澄清的?",
    "summary": "作者提出：先确定和谐意向和澄清误会，再表达情绪、探索熟悉感与由来，选择回应情绪及更深感觉。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T04",
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "我想要什么",
      "有没有误会先澄清",
      "表达哪些绝对真实的情绪",
      "我或伴侣的情绪是否似曾相识",
      "情绪怎么来的",
      "我该怎么回应情绪",
      "情绪背后有哪些感觉",
      "能否用爱回应感觉"
    ],
    "missing_conditions": "不要求按公式死背；未提供客观完成标准；所有问题均有完美双赢解不是保证；不得把当前事实问题略过。"
  },
  {
    "id": "f09",
    "title": "不知道自己感觉时借倾听识别",
    "type": "procedure",
    "source_chapter": "PDF文件页序 113–114、132（1起算）",
    "source_quote": "如果无法察觉,就要求对方多说一点,直到你能了解为止。",
    "summary": "作者提出：在没察觉自己情绪时，仔细听对方描述，再回想自己有无类似体验。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T04",
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "听对方说自己的感觉",
      "不明白则请求多说一点",
      "回想自己实际有过的相似感觉",
      "据此理解彼此"
    ],
    "missing_conditions": "不能预设两人拥有同样情绪；对方描述不充分时保留未知。"
  },
  {
    "id": "f10",
    "title": "沟通复发与无效时检查意向",
    "type": "procedure",
    "source_chapter": "PDF文件页序 118–120、134（1起算）",
    "source_quote": "是不是有什\n么是我更想要的?",
    "summary": "作者提出：接受冲突可能再来；反复无效时回看是不是争正确、避痛、报复、怕亲近优先于沟通。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T04"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "为第二波或第三波冲突保留准备",
      "检查原先沟通意向",
      "辨认是否更想争正确、报复、避痛或避亲近",
      "重新选择沟通并纠正上次错误"
    ],
    "missing_conditions": "不能用意向不诚指责所有失败；可能存在对方不合作、现实约束。"
  },
  {
    "id": "f11",
    "title": "报复武器识别与放下",
    "type": "procedure",
    "source_chapter": "PDF文件页序 123–124（1起算）",
    "source_quote": "问问对方哪些话或行为会让他∕\n她真正受到伤害",
    "summary": "作者提出：检视自己是否因对方痛苦而高兴，公开自己用于伤人的言行并承诺注意负责。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T03",
      "T04"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "找出让自己因对方受伤而快意的言行",
      "辨认用来报复的武器",
      "让伴侣知道并询问什么行为伤害对方",
      "保证更注意、负责并停止使用武器"
    ],
    "missing_conditions": "不能依据自己受伤便断定对方有报复意图；披露弱点在不安全关系中有风险。"
  },
  {
    "id": "f12",
    "title": "向感觉呼吸",
    "type": "procedure",
    "source_chapter": "PDF文件页序 128–129（1起算）",
    "source_quote": "一旦你找到了感觉情绪的身体部位,就把你的呼吸导向那个部位。",
    "summary": "作者提出：觉察情绪对应的身体位置，想象向那里均匀深呼吸并接受感觉。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "找情绪对应的身体部位",
      "均匀连续呼吸并把注意导向该处",
      "接受感觉并留意改变"
    ],
    "missing_conditions": "作者时间保证与身体对应不作为医学事实；深呼吸适用和停止条件未给。"
  },
  {
    "id": "f13",
    "title": "吹气球意象释放",
    "type": "procedure",
    "source_chapter": "PDF文件页序 129（1起算）",
    "source_quote": "想象每次你在呼气时都把气吹进一个气球。",
    "summary": "作者提出：把不快随呼气放入可扩张的想象气球，平静时放飞、戳破。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "舒适坐好并闭眼",
      "呼气时把不快吹进想象气球",
      "感到平静时想象气球飞走并破裂"
    ],
    "missing_conditions": "只是一种意象练习，不证明负面能量实际散去。"
  },
  {
    "id": "f14",
    "title": "能量中心上移意象",
    "type": "procedure",
    "source_chapter": "PDF文件页序 129（1起算）",
    "source_quote": "让感觉在每个能量中心至少停留三十秒,然后再上移。",
    "summary": "作者提出：借心灵朋友支持，将痛苦依序移过想象能量中心，最后与灵魂之星融合。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "定位感觉并想起真心关怀的人或动物",
      "想象感觉移至最近能量中心",
      "每处至少停三十秒后上移",
      "移至头顶灵魂之星并想象光倾泻",
      "感谢心灵朋友"
    ],
    "missing_conditions": "以脉轮感应为前提的灵性练习，不能当解剖或疗效事实；缺乏停止条件。"
  },
  {
    "id": "f15",
    "title": "容器扩张与关怀光意象",
    "type": "procedure",
    "source_chapter": "PDF文件页序 129（1起算）",
    "source_quote": "想象你的身体是一个容器。",
    "summary": "作者提出：原书署名克里希那穆提的方法：以可扩张容器容纳痛苦，并想象内心关怀照耀它。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "想象身体为容器",
      "让痛苦充满并扩张容器以容纳",
      "体验感觉同时想象内心温暖照耀",
      "开放接受结果"
    ],
    "missing_conditions": "原署名未外部核实；意象不等于治疗机制。"
  },
  {
    "id": "f16",
    "title": "艺术表达感觉",
    "type": "procedure",
    "source_chapter": "PDF文件页序 130（1起算）",
    "source_quote": "不断地雕塑,直到满意地表达出你的感受为止。",
    "summary": "作者提出：用想象绘画或雕塑将感受转为颜色、形状，直到觉得表达充分。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "专注当下感受",
      "选择想象绘画或雕塑",
      "以颜色图形或材料形态表达",
      "至满意表达为止"
    ],
    "missing_conditions": "原书保证改变感受，未提供失败与停止条件。"
  },
  {
    "id": "f17",
    "title": "肢体表达与快乐身体融合意象",
    "type": "procedure",
    "source_chapter": "PDF文件页序 130（1起算）",
    "source_quote": "让身体来表达你的感觉。",
    "summary": "作者提出：先以姿势表达当前痛苦，再想象快乐身体靠近融合，观察身体结果。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "依感觉移动身体",
      "维持能表达感觉的姿势",
      "想象快乐身体在旁并慢慢融合",
      "让身体表达融合结果"
    ],
    "missing_conditions": "未提供身体活动限制、疼痛和情绪升级停止条件。"
  },
  {
    "id": "f18",
    "title": "以活动承载情绪觉察",
    "type": "procedure",
    "source_chapter": "PDF文件页序 130（1起算）",
    "source_quote": "在感到平静的时候,你就可以停止散步。",
    "summary": "作者提出：散步或日常活动中持续觉察和承认感觉，让活动与感觉对应。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "决定充分感受",
      "散步或洗碗吸尘等活动",
      "保持活动和感觉对应并不压抑",
      "平静时停止"
    ],
    "missing_conditions": "作者以非爱不真理解释感受须留作者观点；活动安全和停止标准不足。"
  },
  {
    "id": "f19",
    "title": "感觉颜色声音逐层探索",
    "type": "procedure",
    "source_chapter": "PDF文件页序 130（1起算）",
    "source_quote": "听听看你的感觉发出什么样的声音。",
    "summary": "作者提出：注意感觉的颜色声音，集中于其中心，继续观察每层新感受。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "觉察当前感觉的颜色或声音",
      "注意其中心",
      "留意转变后的新感觉",
      "继续观察直至平静"
    ],
    "missing_conditions": "作者自身深层绝望经历不能证明适合独自深度体验；不能保证最终平静。"
  },
  {
    "id": "f20",
    "title": "听听感觉想说什么",
    "type": "procedure",
    "source_chapter": "PDF文件页序 130–131（1起算）",
    "source_quote": "如果你不知道,就想一想如果你知道的\n话,感觉会说些什么。",
    "summary": "作者提出：通过拟人化自问，把含混感觉转成语言；不知道时提出试探性的猜测。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "聆听心中感受",
      "问感觉想说什么",
      "不知道时作明确的试探猜测",
      "表达并留意是否贴合感觉"
    ],
    "missing_conditions": "猜测是当下体验表达，不是事实、记忆或对方动机证据。"
  },
  {
    "id": "f21",
    "title": "释放重负而非否认",
    "type": "procedure",
    "source_chapter": "PDF文件页序 131（1起算）",
    "source_quote": "“ 释放 ” 是让爱来处理你心头的重负。",
    "summary": "作者提出：有信仰时想象将问题交给神，同时承认痛苦存在。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "承认痛苦问题存在",
      "愿意将重负交付神或爱",
      "留意是否获得解脱而非假装没事"
    ],
    "missing_conditions": "依赖个人信仰，原书缺乏行动义务和回访条件。"
  },
  {
    "id": "f22",
    "title": "真诚感谢重启沟通",
    "type": "procedure",
    "source_chapter": "PDF文件页序 131、134（1起算）",
    "source_quote": "你可以从一句简单的话开始",
    "summary": "作者提出：阻滞时寻找真实的感谢、对方重要性并表达，尝试恢复分享。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T01",
      "T04"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "注意沟通阻滞",
      "找真实能感谢的地方",
      "用一句发自真心的话表达",
      "留意彼此能否重新分享感觉"
    ],
    "missing_conditions": "不能以套话控制对方；没有值得感谢之处不应强造，原书缺此分支。"
  },
  {
    "id": "f23",
    "title": "分享被压抑感觉",
    "type": "procedure",
    "source_chapter": "PDF文件页序 131、134（1起算）",
    "source_quote": "你必须分清楚哪些感觉是\n可以分享的,哪些不可以",
    "summary": "作者提出：选择不会火上加油的被压抑恐惧、秘密或情绪逐渐分享，维持重要感觉的焦点。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T04",
      "T05"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "辨认被压抑感情",
      "分辨能否分享",
      "分享感觉及相关经历但不被故事带走",
      "留意平和程度"
    ],
    "missing_conditions": "原书未给哪些不宜分享的明确判据；必须补充同意、隐私与安全限定而标注编排。"
  },
  {
    "id": "f24",
    "title": "诚心认错道歉转折",
    "type": "procedure",
    "source_chapter": "PDF文件页序 132–133、137（1起算）",
    "source_quote": "有时候,沟通中最快捷的方式就是诚心道歉。",
    "summary": "作者提出：承认自己确实犯下的错误，放下防卫并允许宽恕。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T04"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "问自己是否愿意认错",
      "确认自己实际错误",
      "诚心道歉而非辩驳",
      "原谅自己的错误"
    ],
    "missing_conditions": "不替他人行为认错，不能以终止争执作为真假标准。"
  },
  {
    "id": "f25",
    "title": "给沉默者空间的邀请",
    "type": "procedure",
    "source_chapter": "PDF文件页序 133（1起算）",
    "source_quote": "如果想要谈\n谈的话,她随时都有空",
    "summary": "作者提出：表达愿意听，然后给予没有要求必须开口的个人空间。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T04"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "说明对方想谈时自己有空",
      "给很多个人空间",
      "不把开口说话作为期待回报"
    ],
    "missing_conditions": "原书无期限及持续回避义务的处理，不保证一人能解决争执。"
  },
  {
    "id": "f26",
    "title": "戏剧三角角色循环与框架外提问",
    "type": "framework",
    "source_chapter": "PDF文件页序 151–162、211–212（1起算）",
    "source_quote": "要解决问题,必须先跳脱问题的框架。",
    "summary": "作者提出：作者改编卡普曼三角，用受害、迫害、拯救的角色变换识别停滞，再以新问题探索可选回应。",
    "tags": [
      "relationship",
      "self-reflection",
      "framework"
    ],
    "task_ids": [
      "T06"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "观察自己抱怨无助、责怪或代替解决的位置",
      "追踪自己和他人如何切换位置",
      "检视旧答案是否把自己困在框架内",
      "问什么事实、什么感觉、什么行动或创意选择能带来新可能"
    ],
    "missing_conditions": "图六已经主代理视觉核查；原书无辜受害者自相矛盾等断言不可照搬；求助医疗不是病理角色。"
  },
  {
    "id": "f27",
    "title": "责任态度阶梯",
    "type": "framework",
    "source_chapter": "PDF文件页序 159–160（1起算）",
    "source_quote": "“ 责任 ” 这个词的含义也从罪恶和羞耻变\n成回应和自由。",
    "summary": "作者提出：以十种自述由怪罪他人走向我能处理和选择，作者最终上升至自己创造事件的灵性解释。",
    "tags": [
      "relationship",
      "self-reflection",
      "framework"
    ],
    "task_ids": [
      "T06",
      "T14"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "对照十种烂摊子自述",
      "注意当下如何解释责任",
      "向能处理和选择的表述移动"
    ],
    "missing_conditions": "没有量表依据；后段我创造事件不可用于真实受害归责，可能只能留参考。"
  },
  {
    "id": "f28",
    "title": "两难之外开放选择",
    "type": "procedure",
    "source_chapter": "PDF文件页序 163–167、212（1起算）",
    "source_quote": "愿意接受两个选择中的任何一个,或是两个都不选。",
    "summary": "作者提出：两边都有损失时先不排拒任何一个，也容许都不选、组合或第三选项，考虑每个人利益。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T07",
      "T14"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "辨认两边不肯失去的东西及恐惧",
      "愿意接受任一或都不选",
      "探索结合两者及其他可能",
      "按尽量考虑每个人利益选择下一步"
    ],
    "missing_conditions": "书中只有当事人心知道最佳解不可核验；需保留现实成本和信息缺口，不保证人人获益。"
  },
  {
    "id": "f29",
    "title": "家庭自动应对模式识别与改选",
    "type": "procedure",
    "source_chapter": "PDF文件页序 168–174、212（1起算）",
    "source_quote": "我也会模仿许多的 “ 孟氏行为 ”",
    "summary": "作者提出：识别惯性冷战、讽刺、逗趣等是否模仿家人，尝试有创意且重视伴侣的新回应。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T08"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "看自己有无不经思考的反应",
      "比较确实观察到的家庭模式",
      "注意归属、背叛感与代价",
      "选择有创意回应或更重视伴侣的表达"
    ],
    "missing_conditions": "不能由无创意推出家庭死忠；遗传疾病和DNA推论未经证明。"
  },
  {
    "id": "f30",
    "title": "牺牲心态辨认与退出",
    "type": "procedure",
    "source_chapter": "PDF文件页序 175–182、212–213（1起算）",
    "source_quote": "说 “ 不 ” 就\n会有罪恶感,说 “ 好 ” 又不觉得快乐",
    "summary": "作者提出：从答应和拒绝时的感觉发现内疚驱动付出，觉察内在折磨者与坏人评价，平静感受而不走极端反抗。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T09"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "观察答应不快乐、拒绝有罪恶感的任务",
      "检查付出能否接受、是否只为赎罪",
      "觉察折磨者和坏人评价以及情绪空虚",
      "不批判不防卫地体验",
      "选择真正愿意且包括自己利益的付出"
    ],
    "missing_conditions": "情绪不是判定实际责任的唯一证据；未提供合理责任分配或现实强迫分支；图PDF179及212的对应链条已按原文文字保留。"
  },
  {
    "id": "f31",
    "title": "牺牲—放纵钟摆自查",
    "type": "framework",
    "source_chapter": "PDF文件页序 183–185、217注34（1起算）",
    "source_quote": "牺牲者与放纵者的关系,也可以由一个人来唱独角戏。",
    "summary": "作者提出：观察过度牺牲与补偿性放纵是否来回摆动，区分回应伴侣行为与弥补对方行为的义务。",
    "tags": [
      "relationship",
      "self-reflection",
      "framework"
    ],
    "task_ids": [
      "T09"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "观察自己如何牺牲及补偿性放纵",
      "检视把自己认作维持和平或弥补成瘾者的唯一职责",
      "觉察心态并转向真心给予及接受"
    ],
    "missing_conditions": "图七已经主代理视觉核查；不能声称一方停止牺牲另一方必停止放纵；不能把成瘾归责伴侣。"
  },
  {
    "id": "f32",
    "title": "依附束缚图像与重画",
    "type": "procedure",
    "source_chapter": "PDF文件页序 187–189、213（1起算）",
    "source_quote": "再画一张图来描述破除了\n依附情结之后,你和伴侣之间会呈现怎样的情形。",
    "summary": "作者提出：画或想象被束缚图像，觉察恐惧与迎合，然后重画能体现自由选择的关系。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T10"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "识别为了不被抛弃而舍弃的自我特质",
      "画出与亲人或伴侣的束缚",
      "观察熟悉感觉、表达摆脱不实关系意向",
      "画解绑过程及之后关系",
      "不祥和或有冲突则记笔记并重画"
    ],
    "missing_conditions": "图像不是实际因果证据；原书只以祥和核验，不能以此判断必须留下或实际变化已发生。"
  },
  {
    "id": "f33",
    "title": "阴影人物五步反思",
    "type": "procedure",
    "source_chapter": "PDF文件页序 192–194、213（1起算）",
    "source_quote": "你要注意的不是行为,而是内在的特\n质。",
    "summary": "作者提出：从受不了的特质探索背后感觉信念，在自身寻找对应并接纳，再寻找欣赏之处，循环观察。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T11"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "列受不了的特质，若只有行为则问可能信念感觉",
      "在自身寻找相似感觉信念",
      "注意接纳时不自在",
      "说欣赏对方哪些地方",
      "重复至感觉较亲近"
    ],
    "missing_conditions": "不能预设对方动机或自己必有相同特质；不自在不是有效性证据；不等于行为伤害不存在。"
  },
  {
    "id": "f34",
    "title": "性困扰转向情感友谊分享",
    "type": "procedure",
    "source_chapter": "PDF文件页序 196–197、213（1起算）",
    "source_quote": "你有多想和这\n个重要的人建立亲密的情感交流?",
    "summary": "作者提出：作者把焦点由身体表现转为友谊信任，邀请讨论恐惧感觉和秘密。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T10",
      "T14"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "问自己有多想建立情感交流",
      "把对方当朋友伙伴",
      "在信任友谊中分享恐惧、感觉等"
    ],
    "missing_conditions": "作者将性问题归罪恶感缺充分证据；原书缺同意、身体病因、隐私和支持条件，不能编译为性障碍治疗。"
  },
  {
    "id": "f35",
    "title": "承认竞争的三问与支持",
    "type": "procedure",
    "source_chapter": "PDF文件页序 198–200、213（1起算）",
    "source_quote": "你就必须支持伴侣发展自己的长处。",
    "summary": "作者提出：检视想证明自己更特别的暗中竞争，用三个值得问题支持承认竞争并转向支持对方。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T12"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "检视争谁更受爱、更对、更优秀",
      "承认自己的竞争心态",
      "问伴侣、独特的自己、真理是否各值得冒羞耻罪恶感之险",
      "转而支持伴侣长处"
    ],
    "missing_conditions": "原书未细化具体支持行动；不能把合理个人发展都视为竞争。"
  },
  {
    "id": "f36",
    "title": "选择生命的动机检视",
    "type": "framework",
    "source_chapter": "PDF文件页序 201–202、213、218（1起算）",
    "source_quote": "在面对一个状况时,不管你做什么选择,都应该以\n选择生命为动机",
    "summary": "作者提出：作者以选择生命与恐惧分别解释僵局回应，要求面对痛苦并选择爱。",
    "tags": [
      "relationship",
      "self-reflection",
      "framework"
    ],
    "task_ids": [
      "T13",
      "T14"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "注意僵局及逃离痛苦冲动",
      "区分作者所说爱与恐惧的动机",
      "重申选择生命、真理并体验感受"
    ],
    "missing_conditions": "涉及自杀危机但没有危机处理程序，不能编译为急性风险干预；不能把保护性离开称死亡选择。"
  },
  {
    "id": "f37",
    "title": "聆听怀疑把关者并转为明辨",
    "type": "procedure",
    "source_chapter": "PDF文件页序 203–210、214（1起算）",
    "source_quote": "不要和这个 “ 把关者 ” 战斗",
    "summary": "作者提出：将重大转折的自我否定视为把关者，不争斗而聆听、体验恐惧、再以提问明察事情。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T13",
      "T14"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "识别过去失败是否被投射为未来必失败",
      "听怀疑说什么而不战斗",
      "观察恐惧痛苦",
      "重申真实目标并以单纯提问检视事件"
    ],
    "missing_conditions": "所有怀疑都是自我怀疑不成立为通则；原书未区分合理风险证据，不能抛弃统计或现实信息。"
  },
  {
    "id": "f38",
    "title": "假设已经相爱的想象行动实验",
    "type": "procedure",
    "source_chapter": "PDF文件页序 222–224（1起算）",
    "source_quote": "假设我和妻子现在不是在争吵,\n而是感情很融洽的话,情形会是什么样的?",
    "summary": "作者提出：以量子隧道为比喻，问已经相爱时会做什么、感到什么、如何看待对方，尝试一个相应付出。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T01",
      "T04",
      "T14"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "想象此刻感情融洽的情形",
      "问会做什么并尝试具体行动",
      "问会有什么感觉",
      "问会如何看待伴侣",
      "为感受到的温暖留空间并观察"
    ],
    "missing_conditions": "量子隧道只是作者比喻；不能保证一方改变同时改变对方，不能以付出回避具体问题。"
  },
  {
    "id": "f39",
    "title": "允许与无私明辨选择行动或退出",
    "type": "procedure",
    "source_chapter": "PDF文件页序 230–236（1起算）",
    "source_quote": "我并不是在暗示你:个人的目标、观点、感\n觉或欲望都是不重要的。",
    "summary": "作者提出：从为做而做及证明有用退一步，识别驱动决定的力量，把个人目标与重要价值及彼此利益对齐，可留下或分开。",
    "tags": [
      "relationship",
      "self-reflection",
      "procedure"
    ],
    "task_ids": [
      "T14"
    ],
    "inputs": [
      "当前关系事件、自己的感觉或待作选择"
    ],
    "outputs": [
      "对应步骤形成的反思、表达或下一步；不保证对方改变"
    ],
    "steps": [
      "检视是否强迫忙碌以证明有用",
      "辨认个人需求冲动和较重要价值",
      "问何种行动或不行动对彼此有益",
      "真诚表达选择而非找借口",
      "允许选择包含离开"
    ],
    "missing_conditions": "图八九已经主代理视觉核查；心知道不是客观标准；不得照搬作者知女友内心也想分手的读心推断。"
  }
]
```
