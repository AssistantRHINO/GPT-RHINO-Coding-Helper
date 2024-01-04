## 使用说明

RHINO Coding Helper 旨在助您提高在 Github 上的开发工作的效率与质量。该GPT使用了开源项目https://github.com/OpenRHINO/code-chat-helper

您可以试着问我如下问题：

1. OpenRHINO/RHINO-Operator 项目，结合 api/v1alpha2/rhinojob_types.go 解释 internal/controller/rhinojob_controller.go 中 Reconcile 函数的作用。
2. LI-Mingyu/cloud-vm-init 项目 enable-docker-compose 分支中的 ubuntu-18.04.sh 文件与主线相比做了哪些改动？
3. 审查PR：https://github.com/OpenRHINO/code-chat-helper/pull/39 
4. 对于修复 LI-Mingyu/cloud-vm-init 项目的第 29 号 issue 你有什么想法？可能涉及的源码文件是 ubuntu-18.04.sh 
5. 提一个 "Hello world!" comment 到 AssistantRHINO/GPT-RHINO-Coding-Helper 的 issue #1
   
若需用于非开源项目（托管在 Github 上的 private 项目），请先将 [AssistantRHINO](https://github.com/AssistantRHINO) 添加为您项目的成员。

通常情况下，如果您让我审查某个 Pull Request ，我会自动获取被修改的代码文件的全文，将其和修改部分一起进行审查，并且我会自动获取 PR 中提及的 issue 的具体描述（如果有）。如果我没有这么做，您可以提醒我去查看某个文件或者 issue ，这将帮助我生成更有价值的 review comment。

如果有任何问题，欢迎提交 issue 到 https://github.com/AssistantRHINO/GPT-RHINO-Coding-Helper/issues
包括但不限于：
1. 如果提供的 code review comment 过于琐碎没有价值，或者过于关注文档和注释的书写。
2. 如果没有正确获取 github 上的 PR 、 issue 或 文件。
3. 如果向 PR 或 issue 提交 comment 时出错。
4. 其他任何你认为可以改进的地方。

也欢迎加微信号： microwise 进行交流。
