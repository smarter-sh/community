# Kubernetes 贡献者备忘单

这是一份参与 Kubernetes 协作时的常用资源清单，包含 Kubernetes 项目中常用的提示、技巧和最佳实践。这个「长话短说」或快速参考包含一些有用的信息，能让您有更好的 GitHub 贡献体验。

**目录**

- [有用的资源](#%E6%9C%89%E7%94%A8%E7%9A%84%E8%B5%84%E6%BA%90)
  - [入门](#%E5%85%A5%E9%97%A8)
  - [SIG 以及其它小组](#sig-%E4%BB%A5%E5%8F%8A%E5%85%B6%E5%AE%83%E5%B0%8F%E7%BB%84)
  - [社区](#%E7%A4%BE%E5%8C%BA)
  - [工作流程](#%E5%B7%A5%E4%BD%9C%E6%B5%81%E7%A8%8B)
  - [测试](#%E6%B5%8B%E8%AF%95)
  - [重要的 Email 地址](#%E9%87%8D%E8%A6%81%E7%9A%84-email-%E5%9C%B0%E5%9D%80)
  - [其它有用的链接](#%E5%85%B6%E5%AE%83%E6%9C%89%E7%94%A8%E7%9A%84%E9%93%BE%E6%8E%A5)
- [在 GitHub 上有效沟通](#%E5%9C%A8-github-%E4%B8%8A%E6%9C%89%E6%95%88%E6%B2%9F%E9%80%9A)
  - [如何友好对待彼此](#%E5%A6%82%E4%BD%95%E5%8F%8B%E5%A5%BD%E5%AF%B9%E5%BE%85%E5%BD%BC%E6%AD%A4)
    - [良好和不良沟通的例子](#%E8%89%AF%E5%A5%BD%E5%92%8C%E4%B8%8D%E8%89%AF%E6%B2%9F%E9%80%9A%E7%9A%84%E4%BE%8B%E5%AD%90)
- [提交贡献](#%E6%8F%90%E4%BA%A4%E8%B4%A1%E7%8C%AE)
  - [签署 CLA](#%E7%AD%BE%E7%BD%B2-cla)
  - [提交和回应 Issue](#%E6%8F%90%E4%BA%A4%E5%92%8C%E5%9B%9E%E5%BA%94-issue)
    - [提交 Issue](#%E6%8F%90%E4%BA%A4-issue)
    - [回应 Issue](#%E5%9B%9E%E5%BA%94-issue)
  - [提交 Pull Request](#%E6%8F%90%E4%BA%A4-pull-request)
    - [创建 Pull Request](#%E5%88%9B%E5%BB%BA-pull-request)
    - [PR 描述示例](#pr-%E6%8F%8F%E8%BF%B0%E7%A4%BA%E4%BE%8B)
    - [PR 故障排除](#pr-%E6%95%85%E9%9A%9C%E6%8E%92%E9%99%A4)
  - [标签](#%E6%A0%87%E7%AD%BE)
- [在本地工作](#%E5%9C%A8%E6%9C%AC%E5%9C%B0%E5%B7%A5%E4%BD%9C)
  - [分支策略](#%E5%88%86%E6%94%AF%E7%AD%96%E7%95%A5)
    - [添加上游](#%E6%B7%BB%E5%8A%A0%E4%B8%8A%E6%B8%B8)
    - [让您的工作保持同步](#%E8%AE%A9%E6%82%A8%E7%9A%84%E5%B7%A5%E4%BD%9C%E4%BF%9D%E6%8C%81%E5%90%8C%E6%AD%A5)
    - [压缩提交](#%E5%8E%8B%E7%BC%A9%E6%8F%90%E4%BA%A4)

---

## 有用的资源

### 入门

- [贡献者指南] - 如何开始参与 Kubernetes 协作的指南
- [开发者指南] - 直接向 Kubernetes 项目贡献代码的指南
- [安全和披露信息] - 报告漏洞的指南和安全发布过程

### SIG 以及其它小组

- [主要小组列表][sigs]

### 社区

- [日历] - 查看所有的 Kubernetes 社区事件（SIG 或 WG 会议、活动等）
- [kubernetes-dev] - Kubernetes 开发邮件列表
- [Kubernetes 论坛] - Kubernetes 官方论坛
- [Slack 频道] - Kubernetes 官方 Slack
- [Stack Overflow] - Kubernetes 用户提问的地方
- [YouTube 频道] - Kubernetes 社区的官方频道


### 工作流程

- [Prow] - Kubernetes CI/CD 系统
- [Tide] - 管理合并和测试的 Prow 插件 [Tide 仪表盘]
- [Bot 命令] - 用来和 Kubernetes 机器人互动的命令（例如 `/cc`、`/lgtm` 和 `/retest`）
- [GitHub 标签] - Kubernetes 整个项目中使用的标签列表
- [Kubernetes 代码搜索], 由 [@dims] 维护


### 测试

- [Prow] - Kubernetes CI/CD 系统
- [Test Grid] - 查看过往的测试以及相关信息
- [Triage 仪表盘] - 把相似的失败聚合在一起以便排除故障


### 重要的 Email 地址

- community@kubernetes.io - 关于社区的问题，给社区小组（贡献者体验 SIG）的某人写邮件
- conduct@kubernetes.io - 联系行为守则委员会，私密邮件列表
- steering@kubernetes.io - 给指导委员会写邮件，地址公开，存档公开
- steering-private@kubernetes.io - 如果有敏感问题，给指导委员会的私密地址写邮件
- social@cncf.io - 联系 CNCF 的社交团队；博客、推特以及其它社交平台


### 其它有用的链接

- [开发者统计] - 查看所有 CNCF 项目的开发者统计

---

## 在 GitHub 上有效沟通


### 如何友好对待彼此

第一步，您需要熟悉[行为守则]。


#### 良好和不良沟通的例子

当提交 issue 或寻求帮助时，请礼貌地提出您的请求：

🙂 「当我做 Y 事时，X 编译不通过，你们有什么建议吗？」

😞 「X 不起作用！请修好它！」

关闭 PR 时，请清楚和友好地解释为什么它不符合合并的要求：

🙂 「这个功能不能支持 X 使用场景，所以我将关闭这个 PR。在它提议的形式下，用工具 Y 实现会比较好。感谢您的工作。」

😞 「为什么这不符合 API 惯例？这应该在其他地方完成！」


---

## 提交贡献

### 签署 CLA

在您提交贡献之前，您必须[签署贡献者许可证协议（CLA）][cla]。_只有_ 您或者您的公司签署了 CLA，Kubernetes 项目才能接受您的贡献。

如果您在签署 CLA 时遇到任何问题，请参考 [CLA 故障排除指南]。


### 提交和回应 Issue

GitHub Issue 是追踪 bug 报告、改善请求，或者报告例如失败测试的其它问题的主要途径。它们**不**应该用来发布[用户支持请求]。对于那些问题，请查看[故障排除指南]，在[Stack Overflow] 报告，或者在 [Kubernetes 论坛] 跟进。

**参考：**

- [标签]
- [Prow 命令][命令]


#### 提交 Issue

- 尽量使用 issue 模版。使用正确的模版将有助于其它贡献者回应您的 issue。
  - 遵循任何在 issue 模版中描述的指示。
- 尽量详细描述您提交的 issue。
- 使用合适的[标签]。如果您不确定，[k8s-ci-robot][prow] 机器人（[Kubernetes CI 机器人][prow]）将会回复您的 issue 并为其添加需要的标签，让分派更高效。
- 在使用 [`/assign @<username>`][assign] 或 [`/cc @<username>`][cc] 时注意选择。想要您的 issue 得到高效处理，分配更多的人不如使用正确的标签。


#### 回应 Issue

- 在处理 issue 时，添加评论以便让其他人知道，避免重复的工作。
- 如果之后您解决了什么问题，在关闭该 issue 前，先评论以便让其他人知道。
- 添加其它 PR 或 issue 的引用（或者任何可能的资料），例如 _「ref: #1234」_。这对于联系其它地方处理过的相关工作很有帮助。


### 提交 Pull Request

Pull requests（PR）是提交代码、文档或其它形式的工作的主要途径，这些工作都保存在 git 仓库中。

**参考：**

- [标签]
- [Prow 命令][命令]
- [Pull request 处理]
- [GitHub 工作流程]


#### 创建 Pull Request

- 尽量遵循 pull request 模版的指示。这样对于回应您 PR 的人会有帮助。
- 如果是[琐碎问题修复]，例如失效链接、错别字或语法错误，请检查整个文档查找其它可能的错误。不要为了修复同一文档的小问题提交多个 PR。
- 关联任何与您 PR 有关的或者能被解决的 issue。
- 避免在一个提交中引入大量修改。相反地，将您的 PR 分解为多个合理的小提交。这样可以让评审您的 PR 变得更容易。
- 如果您觉得有什么需要更多解释，评论回复您的 PR。
- 有选择地使用 [`/assign @<username>`][assign] 命令，分配过多的评审者并不能让评审过程加快。
- 如果您的 PR 是 _「正在进行中的工作」_，在标题前添加 `[WIP]` 或者使用 [`/hold`][hold] 命令。这样可以防止该 PR 在 `[WIP]` 或 hold 被撤销前被合并。
- 如果您的 PR 没有得到评审，不要关闭后用同样的修改创建新 PR。在评论中使用 `@<github username>` 通知您的评审者。


#### PR 描述示例

```
Ref. #3064 #3097
All files owned by SIG testing were moved from `/devel` to the new folder `/devel/sig-testing`.

/sig contributor-experience
/cc @stakeholder1 @stakeholder2
/kind cleanup
/area developer-guide
/assign @approver1 @approver2 @approver3
```

这个 PR 里包含了：

- **第 1 行** - 提及其它有关的 issue 或 PR（#3064 #3097）。
- **第 2 行** - 对该 PR 做了什么事情的一个简短的描述。
- **第 4 行** - 使用 `/sig contributor-experience` [命令]分配 [SIG][sigs]。
- **第 5 行** - 使用 [`/cc`][cc] 命令指定可能对该 issue 或 PR 感兴趣的评审者。
- **第 6 行** - [`/kind cleanup`][kind] 命令将该 issue 或 PR 添加了一个[标签]将它归类为清理代码、流程或者技术债务。
- **第 7 行** - [`/area developer-guide`][kind] 命令将该 issue 或 PR 归类为与开发者指南有关。
- **第 8 行** - [`/assign`][assign] 命令为该 PR 分配了一名批准者。[k8s-ci-robot][prow] 会从 [OWNERS] 文件中的所有者列表中选择，推荐一名批准者。在评审结束后，他（她）将会使用 [`/approve`][approve] 为该 PR 添加标签。


#### PR 故障排除

在您的 PR 提交后，一系列测试将由 Kubernetes CI 平台 [Prow] 运行。如果任何测试失败，[k8s-ci-robot][prow] 将会回复该 PR，附上失败测试及其 log 的链接。

向您的 PR push 新的提交将会自动触发测试重新运行。

Kubernetes CI 平台偶尔会出现问题。即便您的贡献通过了所有本地测试，也会因为其它各种原因发生问题。您可以使用 `/retest` 命令触发重新运行测试。

关于特定测试的故障排除，请查看[测试指南]。


### 标签

Kubernetes 使用[标签]来分类和分派 issue 和 Pull Request。使用正确的标签将会帮助您的 issue 或 PR 得到更高效的分派。


**参考：**

- [标签]
- [Prow 命令][命令]

常用标签：

- [`/sig <sig name>`][kind] 分配一个 [SIG][SIGs] 来管理该 issue 或 PR
- [`/area <area name>`][kind] 关联该 issue 或 PR 到某一个 [area][标签]
- [`/kind <category>`][kind] 给该 issue 或 PR [分类][标签]

---

## 在本地工作

在提交 pull request 之前，您将需要在本地完成一些工作。如果您是 git 新手，可以从 [Atlassian git 教程]开始学习。或者，您也可以选择斯坦福包含多语言的 [Git 魔法]教程。

**参考：**

- [Atlassian git 教程]
- [Git 魔法]
- [GitHub 工作流程]
- [本地测试]
- [开发者指南]


### 分支策略

Kubernetes 项目使用 GitHub 标准的 _「Fork 然后 Pull」_ 的工作流程。在 git 术语中，您个人的 fork 被称为 _「`origin`」_，实际的项目 git 仓库被称为 _「`upstream`」_。为了保证您的个人分支（`origin`）与项目（`upstream`）保持更新，必须要在您的本地工作副本中进行设置。


#### 添加上游

添加一个远程分支 `upstream`，并将它设置中的 push 选项关闭。

```
# 用上游仓库的 URL 替换 <upstream git repo>
# 例如：
#  https://github.com/kubernetes/kubernetes.git
#  git@github.com/kubernetes/kubernetes.git

git remote add upstream <upstream git repo>
git remote set-url --push upstream no_push
```

您可以运行 `git remote -v` 列出设置过的远程分支来验证这一点。


#### 让您的工作保持同步

获取 `upstream` 的所有变更，然后将您本地的 `master` 分支在它基础上 _「rebase」_。这样您本地的仓库与 `upstream` 项目就能保持同步了。

```
git fetch upstream
git checkout master
git rebase upstream/master
```

至少做完这些，您就可以创建一个新分支，来添加功能或修复问题了。

```
git checkout -b myfeature
```

#### 压缩提交

[压缩提交] 的主要目的是创建一个清晰好读的 git 历史或者过往修改的 log。通常这会在 PR 修订的最后阶段进行。如果您不确定是否应该压缩提交，不妨先保留更多，然后交给其他贡献者来评审和批准您的 PR。



[贡献者指南]: /contributors/guide/README.md
[开发者指南]: /contributors/devel/README.md
[prow]: https://prow.k8s.io
[tide]: https://sigs.k8s.io/prow/site/content/en/docs/components/core/tide/pr-authors.md
[tide 仪表盘]: https://prow.k8s.io/tide
[Bot 命令]: https://go.k8s.io/bot-commands
[GitHub 标签]: https://go.k8s.io/github-labels
[Kubernetes 代码搜索]: https://cs.k8s.io/
[@dims]: https://github.com/dims
[日历]: https://calendar.google.com/calendar/embed?src=calendar%40kubernetes.io
[kubernetes-dev]: https://groups.google.com/forum/#!forum/kubernetes-dev
[Slack 频道]: http://slack.k8s.io/
[Stack Overflow]: https://stackoverflow.com/questions/tagged/kubernetes
[YouTube 频道]: https://www.youtube.com/c/KubernetesCommunity/
[triage 仪表盘]: https://go.k8s.io/triage
[test grid]: https://testgrid.k8s.io
[开发者统计]: https://k8s.devstats.cncf.io
[行为守则]: /code-of-conduct.md
[用户支持请求]: /contributors/guide/issue-triage.md#determine-if-its-a-support-request
[故障排除指南]: https://kubernetes.io/docs/tasks/debug-application-cluster/troubleshooting/
[Kubernetes 论坛]: https://discuss.kubernetes.io/
[Pull request 处理]: /contributors/guide/pull-requests.md
[GitHub 工作流程]: /contributors/guide/github-workflow.md
[prow]: https://sigs.k8s.io/prow/pkg
[cla]: /CLA.md#how-do-i-sign
[cla 故障排除指南]: /CLA.md#troubleshooting
[命令]: https://prow.k8s.io/command-help
[kind]: https://prow.k8s.io/command-help#kind
[cc]: https://prow.k8s.io/command-help#cc
[hold]: https://prow.k8s.io/command-help#hold
[assign]: https://prow.k8s.io/command-help#assign
[SIGs]: /sig-list.md
[测试指南]: /contributors/devel/sig-testing/testing.md
[标签]: https://git.k8s.io/test-infra/label_sync/labels.md
[琐碎问题修复]: /contributors/guide/pull-requests.md#10-trivial-edits
[GitHub 工作流程]: /contributors/guide/github-workflow.md#3-branch
[压缩提交]: /contributors/guide/pull-requests.md#6-squashing-and-commit-titles
[owners]: /contributors/guide/owners.md
[本地测试]: /contributors/guide/README.md#testing
[Atlassian git 教程]: https://www.atlassian.com/git/tutorials
[git 魔法]: http://www-cs-students.stanford.edu/~blynn/gitmagic/
[安全和披露信息]: https://kubernetes.io/docs/reference/issues-security/security/
[approve]: https://prow.k8s.io/command-help#approve
