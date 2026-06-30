<div align="center">

# 李龙杰

AI 算法与应用开发<br>
Agent / RAG / Graph RAG / NLP / 时序预测

[![Email](https://img.shields.io/badge/Email-longjieli0922%40gmail.com-0A66C2?style=flat-square)](mailto:longjieli0922@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-li--longjie-181717?style=flat-square&logo=github)](https://github.com/li-longjie)
[![Demo](https://img.shields.io/badge/Demo-AI_Watch_Dog-FF6699?style=flat-square&logo=bilibili)](https://www.bilibili.com/video/BV187EE6JEy5/)

</div>

## 关于我

关注大模型应用开发与算法工程落地，主要方向包括 Agent 编排、RAG / Graph RAG、知识图谱、NLP 信息抽取、模型服务化和 AI Infra。

相比单纯调用模型，我更关注如何把模型、检索、工具、记忆和业务流程组织成一个可用、可解释、可迭代的系统。

## 技术方向

- **Agent 应用开发**：意图识别、任务拆解、工具调用、多步推理、异常回退、流式响应、长短期记忆。
- **RAG / Graph RAG**：向量检索、Hybrid Search、metadata filter、rerank、Neo4j 图谱查询、证据链生成。
- **知识图谱与 NLP**：实体抽取、关系抽取、事件抽取、三元组抽取、事件链构建、结构化生成。
- **模型与工程部署**：PyTorch、Hugging Face、LoRA / PEFT、FastAPI、Flask、Docker、vLLM、SGLang。
- **AI Infra 与实验管理**：模型服务接入、算法接口封装、WandB / MLflow 实验追踪、训练评估流程。

## 代表项目

### AI Watch Dog：多模态活动日志 Agentic RAG 系统

[GitHub](https://github.com/li-longjie/AI_Watch_Dog) | [演示视频](https://www.bilibili.com/video/BV187EE6JEy5/)

面向个人活动日志的多模态 Agent 与 RAG 检索系统，整合视频画面、桌面活动、屏幕 OCR、窗口标题、浏览 URL、应用使用时长和语音输入，支持通过自然语言查询历史行为、生成活动总结并调用外部工具。

- 构建 Hybrid RAG 检索链路，融合关键词检索、向量召回、时间/应用/URL 等 metadata filter 与 rerank。
- 自研轻量级 Agent 编排，将意图识别、检索路由、工具选择、工具执行、答案生成和异常回退模块化。
- 接入 MCP / Tools 能力，并结合 Faster-Whisper + TTS 实现语音问答链路。

### 多源事件知识图谱与行为辨识推理系统

面向复杂事件分析场景，构建 Graph RAG 行为辨识服务，打通 ES 文本检索、Neo4j 图谱查询与时空特征计算，实现多源证据增强推理。

- 将文本中的实体、关系、事件结构化为三元组并写入 Neo4j，支撑历史事件追溯和关系路径查询。
- 结合文本证据、图谱路径、时间地点和轨迹特征，输出可解释的行为判断证据链。

### 事件链构建与重点目标动向跟踪智能分析系统

面向新闻与事件数据，构建事件抽取、增量归链、目标动向跟踪、事件预测和报告生成流程。

- 基于 Qdrant 与 Qwen Embedding 设计事件链增量归并链路，通过 TopK、阈值和时间窗口完成事件自动归类。
- 对未匹配事件构建 pending 池，结合向量聚类与时间跨度切分生成新事件链，并流式生成结构化分析报告。

### 水文时序预测与 Agent 智能分析系统

面向河湖水位预测与风险分析场景，将水位预测模型接入自然语言 Agent，支持用户查询水位趋势、风险等级、历史对比和预测依据。

- 训练实现多步水位预测模型，融合历史水位、历史协变量和已知未来协变量，降低噪声协变量带来的过拟合风险。
- 将预测、历史查询、协变量检索、风险阈值判断、图表生成和报告输出封装为 Tools / Skills，支持 Agent 动态编排调用。

## 常用技术栈

`Python` `PyTorch` `Hugging Face` `FastAPI` `Flask` `Docker` `LangChain` `LangGraph` `RAG` `Graph RAG` `MCP` `Qdrant` `ChromaDB` `Neo4j` `Elasticsearch` `PostGIS` `vLLM` `SGLang`
