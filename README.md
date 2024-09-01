# Linyaps Packaging SIG (如意玲珑生态共建组) 小组仓库
## 仓库介绍
  欢迎来到Linyaps Packaging SIG，一个专注于丰富玲珑应用生态的特别兴趣小组。我们致力于进行玲珑格式包应用的构建，并持续优化软件的构建及分发流程，促进Linux生态的发展。
  本仓库用于存放 Linyaps Packaging SIG (如意玲珑生态共建组) 团队的贡献指导文档，如需管理 应用仓库，请直接访问[如意玲珑社区构建仓库管理平台](https://github.com/linglongdev/Repository-Manager)

## 其它说明
  为了保障开源社区各贡献者的权益，我们真诚建议您在开始参与 如意玲珑社区 (OpenAtom-Linyaps) 活动前[签署社区CLA（贡献者许可协议）](https://linglong.dev/icla)，确保您对社区的贡献合法有效。

## 成为新应用贡献者
  在正式为 Linyaps Packaging SIG (如意玲珑生态共建组) 小组提交应用贡献前，我们建议您参考本指导来知悉 Linyaps Packaging SIG (如意玲珑生态共建组) 对于应用生态-新增应用的贡献流程

### 仓库声明
  Linyaps Packaging SIG (如意玲珑生态共建组) 小组目前为各大生态贡献者提供了玲珑项目构建服务平台，如果您已经做好提交生态贡献的准备，请在[如意玲珑社区构建仓库管理平台](https://github.com/linglongdev/Repository-Manager)中根据相关要求提交一个应用仓库的申请，用于存放应用的基本信息并开始使用构建服务平台。

### 确认应用仓库可申请性
  在提交应用仓库申请前，为避免包名占用以及应用重复提交的问题，您应该参考以下途径来确保您即将创建的应用仓库当前未被其他贡献者持有:

- **查看 [如意玲珑社区构建仓库管理平台](https://github.com/linglongdev/Repository-Manager) 库内是否存在和您即将提交应用id相同的目录**
- **通过`ll-cli search`模块对该应用/id进行模糊搜索，如应用的英文名称**
- **如果是Firefox等比较热门的应用，建议和 Linyaps Packaging SIG (如意玲珑生态共建组) 小组管理员确认是否该应用暂时未被贡献者认领**

  上述均为自行验证的途径，当您提交了新应用仓库申请之后， Linyaps Packaging SIG (如意玲珑生态共建组)  小组管理委员会将会对当次提交的内容进行审核，以确保您即将提交的应用当前未被其他贡献者认领。

## 提交新应用维护记录
  当您看到这一步时，意味着您已经确认您即将提交的应用当前未被其他贡献者提交，在参考后续流程即可成为该应用的维护者了！

### 创建准备
  这个步骤中，您需要参考 [构建服务平台新应用仓库申请指导](https://github.com/linglongdev/Repository-Manager/blob/main/README.md) 以发起 Pull Request 的形式来认领新应用的维护。

#### 应用仓库结构规范
  根据 [构建服务平台新应用仓库申请指导](https://github.com/linglongdev/Repository-Manager/blob/main/README.md) 的说明，每一个应用仓库在更新玲珑工程配置文件 `linglong.yaml' 并提交 Pull Request 后将会自动提交一次自动构建任务。

### 创建申请提交
  在完成上述准备后，您已经准备好提交新应用仓库申请了。
  在发起 Pull Request 时，请以 `[新 应用仓库申请 提案] 应用id==应用名称` 为格式作为 Pull Request 的标题，并按下面段落的格式，在描述区域简单提供应用仓库的创建原因。
  若您对 GitHub 的 Pull Request 工作流程不熟悉，您也可以开启 Issue ，提供上述信息，来请求 Linyaps Packaging SIG (如意玲珑生态共建组) 小组委员会协助创建。

#### 后续步骤

  Pull Request 发起后，Linyaps Packaging SIG (如意玲珑生态共建组) 小组委员会会在三个工作日内予以反馈。若提出了反馈意见，则申请人或其它小组成员应在 Pull Request 中与委员会进行讨论并达成一致。

  当 Pull Request 最终被合入时，该 应用仓库 即创建完成，意味着您已经成为了该应用的首席维护者。若最终决定不再创建 应用维护记录，则可直接关闭对应的 Pull Request。