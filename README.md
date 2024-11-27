# ChatLLM-tB
Using ChatLLM from twinBASIC

![image](https://github.com/user-attachments/assets/8e39532a-769a-44fa-ba70-2979d85db5e6)

This is a simple app based on https://github.com/JohnClaw/chatllm.vb that showed a simple way to use libchatllm: https://github.com/foldl/chatllm.cpp. See those repos for more models, more information, etc.

Your exe/saved project must be in the same path as libchatlmm.dll, ggml.dll, and a model, the one I used for testing is:

QWen-2.5 1.5B - https://modelscope.cn/api/v1/models/judd2024/chatllm_quantized_qwen2.5/repo?Revision=master&FilePath=qwen2.5-1.5b.bin

NOTE: 1.5GB download.

To use, enter the filename of the model and click Start model, then the other buttons become available if it's successful, or it lets you know an error occured.

**Currently only supports 64bit**

The code itself supports 32bit but you'd need a 32bit build of the DLLs, which are only distributed precompiled in 64bit. 
