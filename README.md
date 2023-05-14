# LLM_architectural _bot
目前打算做的就是通过chatglm实现一个建筑类对合规把控的一个私有模型。目前收集到政府相关建筑类的一些建筑规则文档。对文档解析做成chatglm ptuning（或者lora，还是倾向ptuning）
需要的数据，训练glm框架完成私有llm模型。
因为时间来不及，，目前只收集了数据和一些制作参考文档。

### 基础数据
raw_data_of_constructon_rules.docx

### 训练数据参考
https://www.bilibili.com/video/BV1jN411w7o1/?spm_id_from=333.1007.top_right_bar_window_default_collection.content.click&vd_source=1a432a45372ea0a0d1ec88a20d9cef2c
https://www.bilibili.com/video/BV1eL41127uC/?spm_id_from=333.999.0.0&vd_source=1a432a45372ea0a0d1ec88a20d9cef2c
https://openi.pcl.ac.cn/Learning-Develop-Union/LangChain-ChatGLM-Webui

### 工业化思路参考
https://mp.weixin.qq.com/s/YKR3Bt-Ii4M0MLJApWwyDQ
https://arxiv.org/pdf/2304.06975v1.pdf
https://github.com/scir-hi/huatuo-llama-med-chinese

### 模型原地址
【LLaMa】https://ai.facebook.com/blog/large-language-model-llama-meta-ai/
【ChatGLM】https://github.com/THUDM/ChatGLM-6B/tree/main
