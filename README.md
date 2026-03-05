### 更新日志 - 03/05
- 增加 **Tavily WebSearch** 功能。
- 支持在同一台服务器运行多个 Nanobot 实例：
  - 使用命令：
    ```bash
    nanobot gateway --name test
    ```
  - 每个实例使用独立的 `.nanobot/<name>_config.json` 文件。
  - 通过 `config.json` 中的 `workspace` 配置不同路径，实现多实例互相隔离。
