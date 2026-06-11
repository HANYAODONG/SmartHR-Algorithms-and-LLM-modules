# SmartHR-Algorithms-and-LLM-modules
算法与大模型组仓库

成员：
韩耀栋
甘可欣
纪雨涵
卫昊朗
叶骑瑞

项目文档链接：

https://mcn5rt8fhaeo.feishu.cn/wiki/T6yewNDTZifHPikFEkKcHKXsnMf
# Job-Skill KG Algorithm

本仓库用于第十五届“挑战杯”揭榜挂帅项目 XH-202621 中算法与大模型应用组的代码管理。

## 项目目标

构建岗位与能力图谱相关的算法模块，包括：

1. 招聘文本与简历文本解析
2. 岗位技能抽取
3. 简历技能抽取
4. 人岗匹配评分
5. 新兴岗位发现
6. 技能差距分析
7. 图谱约束的大模型解释生成

## 核心模块

### 1. Skill Extraction

从招聘 JD 和简历文本中抽取技能、岗位名称、工作年限、学历要求、项目经验等信息。

### 2. Job Matching

基于岗位技能权重、简历技能集合、项目经验和岗位要求计算匹配分数。

### 3. Emerging Job Discovery

基于岗位词频增长率、技能组合新颖度、企业扩散度和薪资趋势识别新兴岗位。

### 4. Graph-RAG Explanation

从 Neo4j 图谱查询结构化证据，再调用大模型生成可解释的人岗匹配报告。
