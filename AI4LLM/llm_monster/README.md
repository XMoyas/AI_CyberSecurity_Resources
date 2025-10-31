此目录记录与大模型相有关得学习资料，侧重通用llm知识点，不一定是网络安全领域

## 课程&预训练
- 大模型技能学习
  - 免费大模型课程 : [mlabonne/llm-course](https://github.com/mlabonne/llm-course)
  - 2023春季李宏毅机器学习课程-生成式AI : [bilibil](https://www.bilibili.com/video/BV1NX4y1r7nP/?spm_id_from=333.999.0.0) [国立台湾大学](https://speech.ee.ntu.edu.tw/~hylee/index.php)
  - 2025 台湾大学-李宏毅2025春季Agent课程：[台湾大学](https://speech.ee.ntu.edu.tw/~hylee/ml/2025-spring.php)
  - 大模型算法工程师相关知识及面试题： [Github](https://github.com/wdndev/llm_interview_note/tree/main) [Github-yvanyao](https://yycsu.github.io/)
  - huggingface learn: [NLP Course](https://huggingface.co/learn)
  - 深度学习系统笔记：[dl_note](https://github.com/HarleysZhang/dl_note/tree/main)
- 预训练
  - OLMo:真正意义上的开源，包括训练代码、训练数据、评估代码等：[AI2-OLMo](https://mp.weixin.qq.com/s/uB6jxCWDTJhtFsh9Bc_DYQ) [训练代码](https://github.com/allenai/OLMo) [训练数据&工具](https://github.com/allenai/dolma) [评估](https://github.com/allenai/OLMo-Eval) [微调](https://github.com/allenai/open-instruct) [paper](https://arxiv.org/abs/2402.00838) [博客](https://blog.allenai.org/olmo-open-language-model-87ccfc95f580)

- SFT
  - unsloth微调实践代码：[unsloth微调llama3全过程](https://www.cnblogs.com/shanren/p/18251730)、[A Step-by-Step Coding Guide to Efficiently Fine-Tune Qwen3-14B Using Unsloth AI on Google Colab with Mixed Datasets and LoRA Optimization](https://www.marktechpost.com/2025/05/20/a-step-by-step-coding-guide-to-efficiently-fine-tune-qwen3-14b-using-unsloth-ai-on-google-colab-with-mixed-datasets-and-lora-optimization/)

- 智能体Agent
  - 了解Agent
    - 台湾大学-李宏毅2025春季Agent课程：[台湾大学](https://speech.ee.ntu.edu.tw/~hylee/ml/2025-spring.php)
    - 工作流Workflow vs 智能体Agent: [公众号](https://mp.weixin.qq.com/s/--oOMlbeqE98kE_yjksGmw?color_scheme=light)  [公众号2-更详细讲解](https://mp.weixin.qq.com/s/qyCLff0WG15bEQvjodF-GQ?color_scheme=light)
    - 一步步教你如何构建一个通用的大模型智能体：[公众号](https://mp.weixin.qq.com/s/fjVu-sDaOwz3yj3F_YiU9Q?color_scheme=light)  
  - Agent简单实现
    - 基于qwen2.5 7b的智能体示例: [虹粉世家-公众号](https://mp.weixin.qq.com/s/jaG_RhoyEafufmaD7W0Y1g?color_scheme=light)
    - 基于LangGraph的多智能体系统：[赛博零号-公众号](https://mp.weixin.qq.com/s/SDnaHu3_HYPHMU12Wb3naw?color_scheme=light)
  - MCP协议
    - 本地Qwen3-4B模型也能跑通MCP——MCP代码实战：[王博LLM-公众号](https://mp.weixin.qq.com/s/8rizKj9BZwIylEZ2Gt2_MQ?color_scheme=light)
    - 多文档RAG引擎的 MCP Server（支持PPT智能解析与问答）：[Github](https://github.com/pingcy/app_chatppt)
- RAG
  - RAG实践练习
    - RAG入门者理解核心组件和流程的本地化智能问答项目: [ 本地化智能问答系统](https://github.com/weiwill88/Local_Pdf_Chat_RAG/tree/main)
  - 融合GraphRAG、LightRAG和DeepSeach实现私域RAG：[graph-rag-agent](https://github.com/1517005260/graph-rag-agent)
  - 源码讲解：Deepseacher、ChainOfRAG动态子查询优化RAG流程: [cs的陋室-公众号](https://mp.weixin.qq.com/s/mU74l6oTLPhHTpz91nKDig?color_scheme=light) [deep-search](https://github.com/zilliztech/deep-searcher)
  - 利用langchain、langgraph、RAGAS打造生产级复杂RAG系统 [Github](https://github.com/FareedKhan-dev/complex-RAG-guide/blob/main/README.md)

- DeepSearch
  - 阿里通义千问Tongyi-Deepreseach模型及React实现：[ModelScope](https://modelscope.cn/models/iic/Tongyi-DeepResearch-30B-A3B) [Github](https://github.com/pingcy/TongyiDeepResearch-LangGraph/tree/main) [基于LangGraph实现的React实现](https://github.com/pingcy/TongyiDeepResearch-LangGraph/tree/main)    
- 文档智能
    - 【表格RAG-2024】TAP4LLM:Table Provider on Sampling, Augmenting, and PackingSemi-structured Data for Large Language Model Reasoning [Paper](https://arxiv.org/pdf/2312.09039)

## 资料汇总
- 模型微调：
  - LLM微调技术调研：[公众号链接](https://mp.weixin.qq.com/s/Z0o6sMeHKaKevKJOdDE1sA)
  - LoRA及其变体概述：LoRA, DoRA, AdaLoRA, Delta-LoRA：[公众号链接](https://mp.weixin.qq.com/s/-_JqRklaRI9bD_6QQGKrjg)
- 强化学习：
  - 人类偏好优化算法哪家强？跟着高手一文学懂DPO、IPO和KTO：[公众号链接](https://mp.weixin.qq.com/s/BcWqUN7SSi8q4Tsr7bFmTQ)
  - 最透彻的大模型PPO原理和源码解读：[公众号链接](https://mp.weixin.qq.com/s/F70l-22guVeTukupqQmiFg)

- Prompt:
  - 微软和麻省理工权威发布：Prompt格式显著影响LLM性能，JSON比Markdown准确性高42% [公众号链接](https://mp.weixin.qq.com/s/Do3v_pX8IEaAe7EA1o7ycg)  
  

## 优质LLM公众号推荐
- 包包算法笔记
- 老刘说NLP
