# finetune_dataset_maker
介绍视频在https://www.bilibili.com/video/BV1mg4y1g718/

懒得配环境请使用这位的整合包https://www.bilibili.com/video/BV1Qg4y1g7Ky

ChatGLM一站式微调整合包https://www.bilibili.com/video/BV1P24y1L7Ge

pip安装最新版的streamlit和openai即可运行

支持以下ChatGLM微调项目的格式

https://github.com/hscspring/hcgf

https://github.com/mymusise/ChatGLM-Tuning

https://github.com/ssbuild/chatglm_finetuning

主要功能是读取用户写在txt的问题，并通过GPT生成回答，或者用户自行撰写回答，然后保存为微调需要的json文件

首先打开网页，我们可以选择要回答的问题，选定之后填写答案，也可以选择使用GPT的api来流式生成回答，确认并进入下一个问题

如果回答为空的话，就会删掉未保存的对应回答

保存全部回答，可以将回答序列化写入本地文件以便下次读取。

导出Json的话，会将所有已保存回答写到本地而未保存的回答就会忽略。

用代理的同学记得按照左边的端口号修改代码，不用代理请删掉这两行
![image](https://user-images.githubusercontent.com/38836674/230424529-977d454f-8faa-416f-b2be-ad2e24d2a9f7.png)

改这里切换输出json的格式
![image](https://user-images.githubusercontent.com/38836674/230841273-72e61f2e-450a-4979-94d6-efeaed16dca0.png)
