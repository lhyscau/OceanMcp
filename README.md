## 天气MCP
1. 利用ollama的ollamaclient作为mcpclient，方便封装。
2. 在ollama上下载一个模型，用于推理以及生成工具调用函数，本仓库使用gemma3。
3. 配置好ollama模型后，使用下述命令即可启动多轮天气查询:
    ```python client.py```


**效果展示**

![本地图片](figure/weather.png)