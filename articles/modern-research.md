# 现代研究实践导读：从判断证据到共同工作

[返回首页](../README.md) · [经典文章导读](classic-essays.md) · [研究练习模板](../guides/research-practice.md)

这 6 篇（或部）文本补充经典导读中的实践空缺，按问题而非年代排列。它们包括研究回顾、方法声明和工作指南，证据类型各不相同，不应把一份经验指南当作经过普遍验证的定律。

“核心观点”概括原文；“今天怎样使用”与“局限与提醒”包含整理者的应用建议和评价。书目与来源核对日期：2026-10-14。外链可能因机构访问条件、反爬限制或站点迁移而暂时无法打开，可用 DOI、完整标题和机构入口继续查找。

## 目录

1. [屠呦呦：从线索到可检验的发现](#tu)
2. [Wasserstein & Lazar：怎样解释 p 值](#statistics)
3. [Nosek 等：区分预先计划与事后探索](#preregistration)
4. [Wilson 等：让计算过程可以重跑](#computing)
5. [Wilkinson 等：让数据可发现、可理解、可复用](#fair)
6. [Bennett、Gadlin & Marchand：让团队能够共同工作](#team-science)

---

<a id="tu"></a>

## 1. 屠呦呦 — *Artemisinin—A Gift from Traditional Chinese Medicine to the World (Nobel Lecture)*

- **中文参考名**：《青蒿素——中医药给世界的一份礼物》
- **年代与出处**：2015 年诺贝尔演讲；期刊版发表于 2016 年，*Angewandte Chemie International Edition*，55(35)，10210–10226。
- **主题**：文献线索、方法调整、反复验证与集体研究。
- **原文入口**：[诺贝尔奖官网演讲 PDF](https://www.nobelprize.org/uploads/2018/06/tu-lecture.pdf) · [期刊 DOI](https://doi.org/10.1002/anie.201601967) · [PubMed 书目](https://pubmed.ncbi.nlm.nih.gov/27488942/)
- **补充来源**：[作者在诺贝尔奖官网的自述](https://www.nobelprize.org/prizes/medicine/2015/tu/biographical/)。

### 核心观点

这是一篇发现过程的回顾。屠呦呦讲述了团队如何从文献和筛选结果中寻找线索，在效果不稳定时重新检查提取方法，并通过分离、鉴定和后续研究推进青蒿素的发现。历史记载提供了可追问的方向，研究结果仍需由实验逐步建立。

### 今天怎样使用

- 为一个文献线索分别写下来源、待检验解释和所需证据。
- 遇到结果不稳定时，先检查材料、处理条件与测量过程，再决定是否放弃解释。
- 在研究记录中保留方法改变的理由，并记录不同合作者的贡献。

### 局限与提醒

成功者回顾不能呈现所有失败路径，也不能凭一个成功案例确认整类传统疗法。这里讨论发现方法；历史上的自试或临床研究做法不能直接成为今天的操作依据。

**版权提示**：本仓库仅提供原创导读和官方、期刊入口，不转载演讲或译文。

---

<a id="statistics"></a>

## 2. Ronald L. Wasserstein & Nicole A. Lazar — *The ASA's Statement on p-Values: Context, Process, and Purpose*

- **中文参考名**：《美国统计协会关于 p 值的声明：背景、过程与目的》
- **年代与出处**：2016，*The American Statistician*，70(2)，129–133。
- **主题**：统计显著性、证据解释与完整报告。
- **原文入口**：[期刊 DOI](https://doi.org/10.1080/00031305.2016.1154108) · [Berkeley 教师主页保存的论文 PDF](https://www.stat.berkeley.edu/~aldous/Real_World/ASA_statement.pdf)
- **机构说明**：[ASA 发布的六项原则及声明说明](https://www.amstat.org/asa/files/pdfs/p-valuestatement.pdf)。

### 核心观点

p 值反映数据与指定统计模型的相容程度，不能直接解释为假设为真的概率，也不衡量效应大小或实际重要性。作者强调，研究判断需要结合设计、背景、效应估计和透明报告，不能由是否跨过某个阈值单独决定。

### 今天怎样使用

- 报告效应估计、单位、不确定性及模型假设，解释差异在研究语境中意味着什么。
- 交代检验了多少问题、如何处理多重比较，以及哪些分析为探索性分析。
- 对“不显著”的结果讨论估计精度与兼容的效应范围，避免直接宣称“没有作用”。

### 局限与提醒

这份声明没有要求一律弃用 p 值，也没有提供适用于所有项目的替代分析方案。换成置信区间或贝叶斯方法后，测量偏差、选择性报告和模型失配仍需处理。

**版权提示**：本仓库仅链接论文与机构声明，不复制全文。

---

<a id="preregistration"></a>

## 3. Brian A. Nosek、Charles R. Ebersole、Alexander C. DeHaven & David T. Mellor — *The preregistration revolution*

- **中文参考名**：《预注册革命》
- **年代与出处**：2018，*Proceedings of the National Academy of Sciences*，115(11)，2600–2606。
- **主题**：预测、事后解释、分析自由度与可追溯的计划。
- **原文入口**：[期刊 DOI](https://doi.org/10.1073/pnas.1708274114) · [PMC 全文](https://pmc.ncbi.nlm.nih.gov/articles/PMC5856500/)。

### 核心观点

生成解释和检验预测都能推动研究，但二者提供的证据不同。作者主张，在知晓有关结果之前登记研究和分析计划，使读者能够辨别哪些检验事先确定、哪些发现来自探索，并检查结果是否被选择性呈现。

### 今天怎样使用

- 写清问题、主要指标、样本量或停止规则、排除标准和分析方法；登记时间及此前已接触的数据也应透明。
- 保留初始计划，逐项记录偏离内容、时间、理由和对结论的影响。
- 为意外发现保留探索空间，随后寻找新的数据或独立检验。

### 局限与提醒

预注册不能自动修复弱设计或保证结论正确。只写一句预测与明确分析选择不是同一件事；可对照阅读 [Alison Ledgerwood 的评论](https://doi.org/10.1073/pnas.1812592115)。已有数据分析要披露既有知识，迭代性研究也需要与方法相适应的记录方式。

**版权提示**：PMC 收录页面标注 PNAS 许可；可免费阅读不等于可以任意再分发。本仓库仅提供导读与链接。

---

<a id="computing"></a>

## 4. Greg Wilson、Jennifer Bryan、Karen Cranston、Justin Kitzes、Lex Nederbragt & Tracy K. Teal — *Good enough practices in scientific computing*

- **中文参考名**：《科学计算中够用的良好实践》
- **年代与出处**：2017，*PLOS Computational Biology*，13(6)，e1005510。
- **主题**：数据整理、项目组织、脚本、版本记录与协作。
- **原文入口**：[PLOS 全文](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510) · [DOI](https://doi.org/10.1371/journal.pcbi.1005510)。

### 核心观点

作者面向科研计算初学者，提出可以逐步采用的工作习惯：保留原始数据、记录处理步骤、组织项目文件、明确依赖，并让修改过程可以追踪。目标是让未来的自己和合作者能够理解研究是怎样完成的。

### 今天怎样使用

- 分开保存原始材料与派生结果，用脚本或操作记录连接二者。
- 写一份说明输入、依赖、执行步骤和预期输出的 README，附最小示例。
- 让同伴按说明重跑一项关键结果，把缺失步骤补回记录。

### 局限与提醒

文章针对个人和小团队的入门工作流；大型软件、敏感数据和特殊计算环境需要更多安排。程序能运行、相同数据能重算，以及结论能经受独立研究检验，是不同层次的要求。

**版权提示**：原文由 Wilson 等署名，以 Creative Commons Attribution 4.0 International（CC BY 4.0）发布，见 PLOS 版权栏及其[许可链接](https://creativecommons.org/licenses/by/4.0/)。本仓库提供原创导读，不镜像正文。

---

<a id="fair"></a>

## 5. Mark D. Wilkinson 等 — *The FAIR Guiding Principles for scientific data management and stewardship*

- **中文参考名**：《科学数据管理与管护的 FAIR 指导原则》
- **年代与出处**：2016，*Scientific Data*，3，160018；完整作者名单见原文。
- **主题**：可发现、可访问、可互操作、可复用的数据和元数据。
- **原文入口**：[Scientific Data 全文与作者名单](https://www.nature.com/articles/sdata201618) · [DOI](https://doi.org/10.1038/sdata.2016.18) · [PMC 全文](https://pmc.ncbi.nlm.nih.gov/articles/PMC4792175/)。

### 核心观点

数据的价值取决于人和机器能否找到它、理解它、按明确条件访问并再次使用。FAIR 原则强调持久标识、充分的元数据、共同词汇、来源记录和清楚的使用条件；把文件上传到网页只是其中一小部分。

### 今天怎样使用

- 给数据配上变量字典、单位、缺失值含义、采集方法和版本信息。
- 说明获得数据的程序、使用许可及限制，并关联产生结果的代码或流程。
- 请不熟悉项目的同伴查找一个变量，说明它能否与其他数据比较。

### 局限与提醒

FAIR 允许必要的认证与授权，不要求所有数据无条件公开。达到这些原则也不自动证明数据准确或研究有效；敏感材料的访问条件仍须遵守相应约束。

**版权提示**：Wilkinson 等原文以 Creative Commons Attribution 4.0 International（CC BY 4.0）发布，见期刊版权栏及[许可文本](https://creativecommons.org/licenses/by/4.0/)。第三方材料以各自标注为准；本仓库仅提供原创导读。

---

<a id="team-science"></a>

## 6. L. Michelle Bennett、Howard Gadlin & Christophe Marchand — *Collaboration and Team Science: A Field Guide*

- **中文参考名**：《合作与团队科学：实践指南》
- **年代与出处**：初版 2010；本条导读对应 2018 年第二版，美国国立卫生研究院（NIH）／美国国家癌症研究所（NCI）。上列作者为第二版作者。
- **主题**：共同目标、信任、心理安全、贡献认可与冲突处理。
- **原文入口**：[NCI 第二版 PDF](https://www.cancer.gov/about-nci/organization/crs/research-initiatives/team-science-field-guide/collaboration-team-science-guide.pdf) · [GovInfo 版本记录](https://www.govinfo.gov/app/details/GOVPUB-HE20_3150-PURL-gpo114532)。

### 核心观点

合作需要共同目标、明确预期和能够讨论分歧的工作环境。指南结合团队经验讨论信任、沟通、领导、培养和贡献认可，提醒研究者在合作开始时就处理容易被默认为“大家都知道”的问题。

### 今天怎样使用

- 项目开始时约定责任、沟通方式、材料访问和贡献记录，并定期更新。
- 组会除了报告结果，也讨论不确定性、失败和需要谁帮助。
- 为科学分歧与人员冲突分别约定处理途径，给初级成员安全表达的机会。

### 局限与提醒

指南主要来自特定科研组织的经验，实践效果受资源、权力关系和文化影响。沟通技巧不能替代机构处理不当行为的程序；署名也须结合实际贡献和目标出版物的要求。

**版权提示**：链接指向机构公开版本。本仓库不转载指南或表格，也不对全部第三方材料作公版判断。

## 如何与经典篇一起读

- [Feynman](classic-essays.md#feynman)提出诚实报告的要求；ASA 与预注册文章帮助检查具体的分析和报告选择。
- [Whitesides](classic-essays.md#whitesides)关注论证结构；Wilson 与 FAIR 帮助保留别人检查论证所需的材料。
- [Cajal](classic-essays.md#cajal)、[Hamming](classic-essays.md#hamming)强调个人训练；团队科学指南补充合作条件和组织责任。
- [Chamberlin](classic-essays.md#chamberlin)、[Platt](classic-essays.md#platt)提供检验解释的思路；屠呦呦的回顾提供一个方法不断调整的具体案例。

读后可选择一个[研究练习模板](../guides/research-practice.md)，用真实项目检查这些建议的适用边界。
