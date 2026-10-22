# relationship-bridge（亲密关系：通往灵魂的桥梁）

A [cangjie-skill](https://github.com/kangarooking/cangjie-skill) distillation of **《亲密关系：通往灵魂的桥梁》(Relationship Bridge to the Soul)** by Harold Graham.

> 19 张能力卡，把一本关于亲密关系的书拆成可以按需加载、随停随用的反思工具。只在自愿的日常反思、沟通草稿与小行动范围内工作——不做危机干预，不替人读心，不裁决关系去留。

## What's in this repo

```
.
├── SKILL.md                      # 入口：触发条件 + 核心原则 + 能力路由表
├── BUILD_MANIFEST.json           # 构建元数据（run ID、文件哈希、bundle SHA）
├── references/                   # 能力卡 + 支撑参考（按需加载）
│   ├── capabilities/             # 19 张能力卡
│   │   ├── expectation-needs.md          期望 vs 内在需要
│   │   ├── conflict-behaviors.md         冷嘲热讽 / 控制 / 报复自查
│   │   ├── eight-question-dialogue.md    八问对话
│   │   ├── feeling-expression.md         意象表达感受
│   │   ├── drama-triangle.md             戏剧三角
│   │   ├── beyond-two-options.md         走出"只有两个选择"
│   │   ├── family-response-patterns.md   家庭回应模式
│   │   ├── willing-giving.md             自愿付出 vs 牺牲
│   │   ├── attachment-images.md          依附意象
│   │   ├── shadow-self-reflection.md     影子投射自省
│   │   ├── partner-double-list.md        优缺点双表
│   │   ├── partner-competition.md        伴侣竞争
│   │   ├── sincere-appreciation.md       真诚欣赏
│   │   ├── loving-action-experiment.md   善意小行动实验
│   │   ├── perspective-cooperation.md    轮流修正提案
│   │   ├── specific-apology.md           具体行为道歉
│   │   ├── space-to-talk.md              不逼迫的谈话邀请
│   │   ├── self-doubt-inquiry.md         自我怀疑质询
│   │   └── values-and-choice.md          动机与价值澄清
│   ├── capability-index.md       # 完整意图与关键词索引
│   ├── cheatsheet.md             # 决策规则速查
│   ├── glossary.md               # 术语表
│   └── overview.md               # 全书概览
├── resources/                    # 案例、反例、测试与溯源
│   ├── cases.md                  # 情境案例库
│   ├── counter-examples.md       # 反例（边界与失效条件）
│   ├── source-notes.md           # 溯源说明
│   ├── test-prompts.json         # 测试用例
│   └── test-results.md           # 测试结果
└── workspace/                    # 完整蒸馏工作区（provenance）
    ├── .cangjie/                 # Capability Bundle（单一事实来源）
    │   ├── card-manifest.json
    │   ├── review-decisions.json
    │   ├── source-quote-audit.json
    │   └── evals/ runs/ snapshots/
    ├── BOOK_OVERVIEW.md          # Stage 0：全书理解
    ├── DIGEST.md                 # 面向人的蒸馏长文
    ├── verified.md               # Stage 1.5：三重核验结果
    ├── 日常能力清单.md             # 能力总览
    ├── 使用说明.md                 # 使用说明
    ├── candidates/               # Stage 1：原始候选
    ├── rejected/                 # 未晋升的候选单元
    └── coverage-audit.md / promotion-review.md / needs-review.md
```

## Install

已经安装 [cangjie-skill](https://github.com/kangarooking/cangjie-skill) 的话：

```bash
cangjie install https://github.com/helenchen0703-blip/relationship-bridge
```

或者手动把 `SKILL.md` + `references/` + `resources/` 复制进你的 skills 目录。

## 用法

模型会先读 `SKILL.md` 的能力路由表，**只加载与当前意图最相近的一张卡**，必要时组合最多两张。这样避免了把整本书塞进上下文。

触发词：`relationship`、`needs`、`conflict`、`guilt`、`dialogue`，以及"亲密关系""伴侣""吵架""内疚""沟通"等中文表达。

### 明确不适用的场景

- 存在暴力、威胁、胁迫 → 转向现实保护与相应支持
- 自伤/自杀危机、创伤治疗、性障碍或身体症状的诊断治疗
- 替伴侣读心，或要求系统裁决"分手/复合"的正确答案

## 设计原则

1. 把可观察事实、自己的感受、对方行为责任分开，不把所有问题解释成旧伤。
2. 完成标准是清楚的记录、表达或可执行下一步——**是否和好、对方是否改变，不由方法保证**。
3. 关系可以结束。不以宽恕、留下、感谢伤害或揽下责任作为成熟指标。
4. 意象是可选表达，不是实体，也不是疗效证据。

## License

MIT — see [LICENSE](LICENSE).

Skill 内容为对原书的二次蒸馏与再表达；原书版权归原作者所有。