# DoctorGLM
中文在线问诊模型， 基于 ChatGLM-6B + lora 进行finetune.

finetune代码来自 https://github.com/ssbuild/chatglm_finetuning
## 训练数据
https://github.com/Toyhom/Chinese-medical-dialogue-data
## 准备
- 显存 >= 13G
- pip install deep_training cpm_kernels icetk transformers>=4.26.1 
- torch >= 1.12.0
## 使用
./Doctor_GLM/chat.ipynb

## Reference
https://github.com/THUDM/ChatGLM-6B

https://github.com/ssbuild/chatglm_finetuning

# TODO
- 模型量化, 降低显存使用
- 扩大训练数据集
