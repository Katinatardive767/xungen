<h1 align="center">🏛️ 寻根 Xungen</h1>

<p align="center">
  <strong>3000 年前，你在商朝混哪个圈子？</strong>
</p>

<p align="center">
  <em>Trace Your Roots — Shang Dynasty Identity Engine</em>
</p>

<p align="center">
  🇨🇳 中文 · <a href="README.en.md">🇺🇸 English</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude_Code-black?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude Code">
  <img src="https://img.shields.io/badge/Codex_CLI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="Codex CLI">
  <img src="https://img.shields.io/badge/Cursor-000?style=for-the-badge&logo=cursor&logoColor=white" alt="Cursor">
  <img src="https://img.shields.io/badge/Kiro-232F3E?style=for-the-badge&logo=amazon&logoColor=white" alt="Kiro">
  <img src="https://img.shields.io/badge/OpenClaw-FF6B35?style=for-the-badge" alt="OpenClaw">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT">
  <img src="https://img.shields.io/badge/🌐_2_Languages-blue?style=flat-square" alt="Languages">
  <img src="https://img.shields.io/badge/朝代-商朝_1600--1046_BCE-brown?style=flat-square" alt="Shang Dynasty">
  <img src="https://img.shields.io/github/stars/sumleo/xungen?style=flat-square" alt="Stars">
</p>

---

> *你的 DNA 动了吗？*

## 🤔 你知道你的姓从哪来吗？

现代人的姓氏，很多都源于 3000 年前的**图腾、族名、封地、或职官**。

你姓**马**？你的祖先可能是商朝的马正，给商王养马的。
你姓**卜**？你的祖先可能是商朝的占卜师，天天烤乌龟壳读裂纹。
你是**河南安阳**人？恭喜，你是商朝帝都的原住民，纯正 Old Money。
你是**陕西**人？嗯…你的祖先是灭掉商朝的那帮人。尴尬。

**寻根**是一个 AI Agent Skill，输入你的姓氏或家乡，立刻生成一份《商朝身世鉴定书》。

## ⚡ 效果演示

```
> /xungen 孔 山东曲阜

╔══════════════════════════════════════════╗
║      📜 商 朝 身 世 鉴 定 书 📜         ║
╠══════════════════════════════════════════╣
║                                          ║
║  鉴定对象：孔氏                          ║
║  鉴定依据：姓氏"孔" + 家乡"山东曲阜"    ║
║  可信等级：🏛️ 有据可查                   ║
║                                          ║
║  🏛️ 氏族归属：商王族·子姓分支            ║
║  📍 封地所在：宋国（今河南商丘）          ║
║  👤 祖先身份：宋国公族·微子启后裔         ║
║  🐾 图腾信仰：玄鸟（燕子）               ║
║                                          ║
║  ⚔️ 商朝大事件：                         ║
║  纣王被灭后，其兄微子启被周武王封于宋，   ║
║  以延续商祀。孔氏正是宋国公族后裔，       ║
║  孔子本人就是商汤的第 32 代嫡传后人！     ║
║                                          ║
║  🎭 你的商朝人设：                       ║
║  你是商朝王族的正统后裔。虽然后来混成了   ║
║  一个教书的，但你的血统比绝大多数诸侯都   ║
║  高贵。你是那种"落难王子后来当了老师，    ║
║  结果老师比王子出名"的典型案例。          ║
║                                          ║
║  💎 Old Money 指数：★★★★★               ║
║  王族嫡系。你是商朝最顶级的 Old Money。   ║
║                                          ║
╚══════════════════════════════════════════╝
```

## 🔍 匹配逻辑

寻根不是瞎编。它有 4 层匹配机制，每一层都标注可信度：

```
Layer 1  姓氏直接追溯     "卜"→商代卜官后裔          🏛️ 有据可查
  ↓
Layer 2  地域关联         河南安阳→殷都核心区         🏛️ 有据可查
  ↓
Layer 3  间接关联         周代封国→商代原住民         🔮 合理推测
  ↓
Layer 4  创意关联         甲骨文字形分析+地理推测     🎲 趣味脑洞
```

**三种可信度标签**，绝不混淆：

| 标签 | 含义 | 举例 |
|------|------|------|
| 🏛️ **有据可查** | 有甲骨文、史书、考古证据 | 子姓→商王族、卜→卜官 |
| 🔮 **合理推测** | 基于合理历史推断 | 马→马正（养马官） |
| 🎲 **趣味脑洞** | 纯趣味关联，供娱乐 | 牛→商代畜牧业 |

## 📜 内置知识库

<details>
<summary><strong>核心姓氏-氏族映射（点击展开）</strong></summary>

| 现代姓 | 商朝关联 | 可信度 | 说明 |
|--------|---------|--------|------|
| 子 | 商王族 | 🏛️ | 商朝王室之姓 |
| 殷 | 殷地 | 🏛️ | 以都城殷（安阳）为氏 |
| 宋 | 宋国 | 🏛️ | 纣王之子微子启封国 |
| 商 | 商族 | 🏛️ | 直接以朝代为氏 |
| 汤 | 成汤 | 🏛️ | 开国之君之后 |
| 卜 | 卜官 | 🏛️ | 占卜官之后 |
| 史 | 太史 | 🏛️ | 史官之后 |
| 祝 | 祝官 | 🏛️ | 祭祀官之后 |
| 巫 | 巫师 | 🏛️ | 巫师阶层之后 |
| 孔 | 宋国公族 | 🏛️ | 孔子为商汤后裔 |
| 林 | 比干之后 | 🏛️ | 商朝忠臣比干之子 |
| 戴 | 宋戴公 | 🏛️ | 商后裔戴公之后 |
| 华 | 宋国华氏 | 🏛️ | 华父督之后 |
| 萧 | 萧国 | 🏛️ | 商后裔附庸国 |
| 马 | 马正 | 🔮 | 养马官之后 |
| 武 | 武丁 | 🔮 | 商王武丁之后 |
| 邓 | 邓国 | 🔮 | 商代方国 |
| 陶 | 陶工 | 🔮 | 陶器工匠之后 |
| 梅 | 梅伯 | 🔮 | 商代梅伯之后 |

</details>

<details>
<summary><strong>地域映射（点击展开）</strong></summary>

| 现代地区 | 商朝身份 | 鉴定结果 |
|---------|---------|---------|
| 河南安阳 | 殷都 | 天下中心！帝都人 |
| 河南郑州 | 亳都 | 开国之都，Old Money 中的 Old Money |
| 河南商丘 | 商族发源地 | 老家中的老家 |
| 山东 | 东方大本营 | 商族核心活动区 |
| 湖北 | 铜矿供应地 | 商朝的经济命脉 |
| 四川 | 三星堆 | 神秘的西南盟友 |
| 陕西 | ⚠️ 周族地盘 | 你祖先灭了商朝… |

</details>

## 🎭 社会阶层

| 阶层 | 商朝角色 | 现代翻译 | Old Money 指数 |
|------|---------|---------|:---:|
| 👑 王族 | 子姓王室 | 皇亲国戚 | ★★★★★ |
| 🏛️ 贵族 | 方国君主 | 世袭权贵 | ★★★★☆ |
| 🔮 巫卜 | 占卜师、祭司 | 国家智库+气象局 | ★★★★☆ |
| ⚔️ 武将 | 军事将领 | 国防部 | ★★★☆☆ |
| 📜 史官 | 记录官 | 新华社总编 | ★★★☆☆ |
| 🐴 马正 | 马匹管理 | 交通部长 | ★★★☆☆ |
| 🏺 工匠 | 青铜器/陶器 | 高级技术人才 | ★★☆☆☆ |
| 🌾 农人 | 种地 | 基层劳动者 | ★☆☆☆☆ |

## 🎮 玩法

### 基础玩法
输入姓氏或家乡 → 立刻获得鉴定书

### 进阶追问
- *"我的氏族图腾长什么样？"* → 图腾形象描述
- *"牧野之战时我的祖先站哪边？"* → 历史推演
- *"我和老王在商朝是什么关系？"* → 氏族关系分析
- *"给我写一封商朝家书"* → 半文言体祖先来信
- *"穿越回商朝我会怎样？"* → 穿越剧情生成

### 群聊模式 🔥
多人输入姓氏 → 生成《商朝社交关系图》：谁是贵族谁是平民，谁能联姻谁得打仗。

## 📦 安装

<details>
<summary><strong>Claude Code</strong></summary>

```bash
claude plugin marketplace add sumleo/xungen
claude plugin install xungen@xungen-skills
```

</details>

<details>
<summary><strong>Codex CLI</strong></summary>

```bash
mkdir -p ~/.codex/skills/xungen
curl -o ~/.codex/skills/xungen/SKILL.md \
  https://raw.githubusercontent.com/sumleo/xungen/main/codex/xungen/SKILL.md
```

</details>

<details>
<summary><strong>Cursor</strong></summary>

```bash
mkdir -p .cursor/rules
curl -o .cursor/rules/xungen.mdc \
  https://raw.githubusercontent.com/sumleo/xungen/main/cursor/rules/xungen.mdc
```

</details>

<details>
<summary><strong>Kiro</strong></summary>

```bash
mkdir -p .kiro/steering
curl -o .kiro/steering/xungen.md \
  https://raw.githubusercontent.com/sumleo/xungen/main/kiro/steering/xungen.md
```

</details>

<details>
<summary><strong>OpenClaw</strong></summary>

```bash
clawhub install xungen
```

</details>

## 🌐 语言支持

| 语言 | Claude Code | Codex CLI | Cursor | Kiro | OpenClaw |
|------|:-----------:|:---------:|:------:|:----:|:--------:|
| 🇨🇳 中文 *(默认)* | `xungen` | `xungen` | `xungen.mdc` | `xungen.md` | `xungen` |
| 🇺🇸 English | `xungen-en` | `xungen-en` | `xungen-en.mdc` | `xungen-en.md` | `xungen-en` |

## 🤝 技能组合

| 组合 | 效果 |
|------|------|
| 🏛️ 寻根 + 🔥 [Roast](https://github.com/sumleo/roast) | 先烤问你对家族的认知盲区，再给鉴定书 |
| 🏛️ 寻根 + 💪 [PUA](https://github.com/tanweai/pua) | AI 不服气你的姓比它高贵，拼命给你找更多历史细节 |

## ⚠️ 声明

- 这是**文化趣味工具**，不是学术论文，不是种族鉴定
- 所有考据基于公开历史文献，标注了可信度等级
- 绝不伪造甲骨文或考古证据
- 每个姓氏都值得尊重，没有高低之分（但 Old Money 指数纯属娱乐）
- 如果你姓"周"…我们聊聊 😏

## 📜 致谢

感谢商朝的占卜师们。没有你们在乌龟壳上刻的那些字，我们啥也查不到。

甲骨文是人类最早的大数据。你们是初代数据工程师。

---

<p align="center">
  <strong>你的 DNA 动了吗？</strong>
</p>

<p align="center">
  <sub>Built with 🏛️ by <a href="https://github.com/sumleo">Yi Liu</a></sub>
</p>
