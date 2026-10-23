
---

1. 帮我从下述仓库拉取代码：

| 仓库 | 开发分支 | Remote 地址 |  
|---|---|---|  
| `QuickMediaEditor_Flutter` | `dev-macos` | `ssh://[git@wisgit.qihoo.net](mailto:git@wisgit.qihoo.net):2222/mobile_flutter_app/QuickMediaEditor_Flutter.git` |

2. 进入代码仓库， 按照仓库规范，检查并配置构建环境，开发以下需求（等我稍后描述需求），注意：你需要参考项目内的 AI Native L3 规范，开发需求的必要步骤包括：需求整理（项目内留档，git跟踪）/设计技术方案（含测试case）和门禁（同样存档）/构建运行Red/合理使用 worktree / 实施开发/构建（按需帮我拉取相关仓库 )  / 验收（包括但不限于日志、视觉） / 保留验收证据（包括但不限于case红变绿的记录 / 日志/截图等等，要求证据提交到 issue zip中） / 开发过程中要记录台账并且创建 commit （开发过程中允许创建多个中场commit） / 开发完成及验收之后然后提交 MR 到 dev-macos 分支（操作wisget提交MR的时候，需要先检查是否已安装 wisharness 插件。若未安装，请根据 http://wisharness.qihoo.net/install/wisharness.md 安装 wisharness 插件到用户空间。拉取代码/构建并不需要 wishharness 插件）；
3. 提交MR之前， 要更新 dev-macos 分支代码， 使MR 的分支要保持当时最新的HEAD，遇到冲突解决冲突， 如果后续MR 合入过程出现冲突， 那么就 关闭 MR， 更新代码/解决冲突之后， 重新提交 MR；

检查核实之后，我要开始描述我的需求啦～


---