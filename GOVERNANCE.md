# BIO-SIG 治理

该Charter内容遵循openEuler [ SIG-governance.md](https://gitee.com/openeuler/community/blob/master/en/technical-committee/governance/SIG-governance.md)描述的约定，本文会根据需要进行更新，以满足openEuler BIO-SIG的需求。

​为了使社区席位设置规范化和标准化,让社区参与者更好的融入社区, BIO-SIG 社区席位设置应该遵循以下准则：

## SIG maintainers

当前,BIO-SIG的maintainer均在[OWNERS](/OWNERS)文件中列出.

SIG组的maintainer来自不同的地区、高校、公司,根据背景不同也有着不同的职责，但所有的maintainer都有着共同点：

1. 他们对项目的成功负有共同的责任。
2. 他们进行了长期地、经常性地时间投资来改进项目。
3. 他们花费时间做任何需要做但不一定是最有趣的事情。

Maintainer经常因为他们所做的工作不太明显而被低估。往往识别出极好的且技术先进的功能是很简单的，
但欣赏没有bug、缓慢但稳定的改进或发布过程的可靠性往往是比较难的，而这些却是一个伟大的项目和一个好项目的根本区别。

## 增加 maintainers

maintainer首先是长期活跃在社区的贡献者。贡献者通过不少于三个月的代码贡献、代码审查、issue讨论分类来获得maintainer提名资格。

但仅靠贡献并不能使贡献者成为maintainer。其还需要赢得当前maintainer和其他项目贡献者的信任，其决定和行动需要符合项目的最大利益。

现有的maintainer会定期整理一份贡献者名单，这些贡献者在过去几个月中在项目上表现出定期活动。 从这个列表中，选择maintainer候选人并在maintainer邮件列表中提名。

在maintainer邮件列表上提名候选人后，现有maintainer将在接下来的 5 个工作日内讨论候选人，提供反馈并投票。新提名maintainer至少需要获得 66% 的当前维护者的赞成票。

如果候选人获得批准，maintainer会联系候选人，邀请他们建立将贡献者添加到 OWNERS 文件中的PR。 当PR被合并后，候选人将成为maintainer。

## 移除 maintainers

Maintainer可以根据本人的自愿放弃请求或者在项目中无法有效履行maintainer职责而被移除权限。

### 自愿放弃

由于兴趣和热情等因素的改变，当前maintainer自觉无法/无意愿继续行使maintainer职责的可告知其他maintainer其自愿放弃maintainer席位。
放弃者应尽可能帮助社区寻找接任者,其至少需要确保社区的工作不至于因其离开而中断。

在您通知其他maintainer后，创建一个PR以将您自己从 OWNERS 文件中删除。

### 无法有效履行maintainer职责
  
maintainer代表会定期审查所有maintainer在过去三个月中的社区活动。如果现有maintainer在项目中长期没有表现出重要的活动，则可以考虑将其移除。
maintainer代表由所有maintainer轮值，轮值期三个月。

如果maintainer在此期间表现出的活动不足，maintainer代表将联系相关者，询问他们是否想继续担任maintainer。 如果其决定退出maintainer队伍，maintainer代表将建立PR将其从 OWNERS 文件中删除。

如果该maintainer想继续担任此角色，但无法履行所需职责，则可以通过至少 66% 的当前maintainer 的赞成票来将其移出,讨论中的维护者将不被允许投票。

投票可通过maintainer邮件列表来邀请SIG组的maintainer参与,投票期为五个工作日。
与讨论中的maintainer的表现相关的问题应该在投票过程中与其他maintainer讨论，所有的讨论应该客观地处理，不准人身攻击。

## 社区决策

openEuler 核心项目和SIGs都是具有开放设计理念的开源项目。这意味着代码仓是项目和SIG组理念、设计、发展规划等各个方面的真实来源。

因此，每个决定都可以表示为代码仓的更改。

所有影响BIO-SIG代码仓的决策，无论大小，都遵循相同的步骤：

  * **第 1 步**：建立PR。 任何人都可以做到这一点。

  * **第 2 步**：讨论PR。 任何人都可以做到这一点。

  * **第 3 步**：Maintainer合并、关闭或拒绝PR。

PR由 BIO-SIG 代码仓的当前maintainer审查。
