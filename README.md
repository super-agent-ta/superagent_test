# superagent_test

dsh-superagent 验证仓库。修改请走 Pull Request。

## 项目说明

superagent_test 是用于验证 dsh-superagent 能力的示例仓库。仓库保持精简，包含一个问候文件与基础文档，用来确认 Agent 能够正确读取、修改仓库内容并通过 Pull Request 提交变更。

## 使用方法

1. 克隆仓库并进入目录：

   ```bash
   git clone https://github.com/super-agent-ta/superagent_test.git
   cd superagent_test
   ```

2. 查看问候语：

   ```bash
   cat hello.txt
   ```

3. 按需修改文件，提交后推送分支，并通过 Pull Request 合并到 `main`。

## 贡献指南

- 所有修改请通过 Pull Request 提交，不要直接推送到 `main` 分支。
- 提交信息请清晰说明改动内容，一个提交只做一件事。
- 提交前请自行验证改动，并在 Pull Request 描述中写明验证方式。
- 涉及用户可见变更时，请同步更新 [CHANGELOG.md](CHANGELOG.md)。
