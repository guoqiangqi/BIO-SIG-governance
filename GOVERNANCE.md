# BIO-SIG governance

This Charter follows the discription in openEuler [SIG-governance.md](https://gitee.com/openeuler/community/blob/master/en/technical-committee/governance/SIG-governance.md). This article would been updated as needed to meet the needs of openEuler BIO-SIG.

​In order to standardize the setting of community seats, so that community participants can get involed better, the BIO-SIG community seats setting should follow the following guidelines:

该Charter内容遵循openEuler [ SIG-governance.md](https://gitee.com/openeuler/community/blob/master/en/technical-committee/governance/SIG-governance.md)描述的约定，本文会根据需要进行更新，以满足openEuler BIO-SIG的需求。

​为了使社区席位设置规范化和标准化,让社区参与者更好的融入社区, BIO-SIG 社区席位设置应该遵循以下准则：

## SIG maintainers

The current maintainers of the BIO-SIG repository are listed in the
[OWNERS](/OWNERS) file.

当前,BIO-SIG的maintainer均在[OWNERS](/OWNERS)文件中列出.

There are different types of maintainers, with different responsibilities, but
all maintainers have 3 things in common:

 1. They share responsibility in the project's success.
 2. They have made a long-term, recurring time investment to improve the project.
 3. They spend that time doing whatever needs to be done, not necessarily what is the most interesting or fun.

在社区中根据不同的职责有不同类型的maintainer,但他们都有3个共同点：

1. 他们对项目的成功负有共同的责任。
2. 他们进行了长期地、经常性地时间投资来改进项目。
3. 他们花费时间做任何需要做但不一定是最有趣的事情。

Maintainers are often under-appreciated, because their work is less visible.
It's easy to recognize a really cool and technically advanced feature. It's harder
to appreciate the absence of bugs, the slow but steady improvement in stability,
or the reliability of a release process. But those things distinguish a good
project from a great one.


Maintainer经常因为他们所做的工作不太明显而被低估。往往识别出极好的且技术先进的功能是很简单的，
但欣赏没有bug、缓慢但稳定的改进或发布过程的可靠性往往是比较难的，而这些却是一个伟大的项目和一个好项目的根本区别。

## Adding maintainers

Maintainers are first and foremost contributors who have shown their
commitment to the long term success of a project. Contributors who want to
become maintainers first demonstrate commitment to the project by contributing
code, reviewing others' work, and triaging issues on a regular basis for at
least three months.

The contributions alone don't make you a maintainer. You need to earn the
trust of the current maintainers and other project contributors, that your
decisions and actions are in the best interest of the project.

Periodically, the existing maintainers curate a list of contributors who have
shown regular activity on the project over the prior months. From this
list, maintainer candidates are selected and proposed on the maintainers
mailing list.

After a candidate is announced on the maintainers mailing list, the
existing maintainers discuss the candidate over the next 5 business days,
provide feedback, and vote. At least 66% of the current maintainers must
vote in the affirmative.

If a candidate is approved, a maintainer contacts the candidate to
invite them to open a pull request that adds the contributor to
the OWNERS file. The candidate becomes a maintainer once the pull
request is merged.

维护者首先是表现出对项目长期成功的承诺的贡献者。想要成为维护者的贡献者首先通过贡献代码、审查他人的工作和至少三个月的定期分类问题来证明对项目的承诺。

仅靠贡献并不能使您成为maintainer。你需要赢得当前maintainer和其他项目贡献者的信任，你的决定和行动符合项目的最大利益。

现有的maintainer会定期整理一份贡献者名单，这些贡献者在过去几个月中在项目上表现出定期活动。 从这个列表中，选择维护者候选人并在maintainer邮件列表中提名。

在maintainer邮件列表上提名候选人后，现有maintainer将在接下来的 5 个工作日内讨论候选人，提供反馈并投票。新提名maintainer至少需要获得 66% 的当前维护者的赞成票。

如果候选人获得批准，maintainer会联系候选人，邀请他们建立将贡献者添加到 OWNERS 文件中的PR。 当PR被合并后，候选人将成为maintainer。

## Removing maintainers

Maintainers can be removed from the project, either at their own request
or due to [project inactivity](#inactive-maintainer-policy).

Maintainer可以根据本人的请求或者在项目中的不活跃而被移除权限。

### How to step down

Life priorities, interests, and passions can change. If you're a maintainer but
feel you must remove yourself from the list, inform other maintainers that you
intend to step down, and if possible, help find someone to pick up your work.
At the very least, ensure your work can be continued where you left off.

After you've informed other maintainers, create a pull request to remove
yourself from the OWNERS file.

由于生活中优先事项、兴趣和热情可能会改变，如果您是一个maintainer,当觉得必须从maintainer列表中删除自己时，
您可以通知其他maintainer你打算下台。如果可能的话，帮助找人接手你的工作,你至少需要确保你的工作可以在你离开的节点继续。

在您通知其他maintainer后，创建一个PR以将您自己从 OWNERS 文件中删除。

### Inactive maintainer policy

An existing maintainer can be removed if they do not show significant activity
on the project. Periodically, the maintainers review the list of maintainers
and their activity over the last three months.

If a maintainer has shown insufficient activity over this period, a project
representative will contact the maintainer to ask if they want to continue
being a maintainer. If the maintainer decides to step down as a maintainer,
they open a pull request to be removed from the OWNERS file.

If the maintainer wants to continue in this role, but is unable to perform the
required duties, they can be removed with a vote by at least 66% of the current
maintainers. The maintainer under discussion will not be allowed to vote. An
e-mail is sent to the mailing list, inviting maintainers of the project to
vote. The voting period is five business days. Issues related to a maintainer's
performance should be discussed with them among the other maintainers so that
they are not surprised by a pull request removing them. This discussion should
be handled objectively with no ad hominem attacks.
  
如果现有maintainer在项目中没有表现出重要的活动，则可以将其移除。maintainer会定期审查maintainer列表及其在过去三个月中的活动。

如果maintainer在此期间表现出的活动不足，项目代表将联系maintainer，询问他们是否想继续担任maintainer。 如果其决定退出维护队伍，项目代表将建立PR将其从 OWNERS 文件中删除。

如果maintainer想继续担任此角色，但无法履行所需职责，则可以通过至少 66% 的当前维护者投票将其移除,讨论中的维护者将不被允许投票。
通过邮件列表发送电子邮件，邀请项目的maintainer投票,投票期为五个工作日。
与讨论中的maintainer的表现相关的问题应该在投票过程中与其他maintainer讨论，这样他们就不会对删除相关maintainer的PR感到惊讶。所以的讨论应该客观地处理，不准人身攻击。

## Project decision making  

Short answer: **Everything is a pull request**.

The openEuler core project and sigs are all open-source project with an open design
philosophy. This means that the repository is the source of truth for **every**
aspect of the project, including its philosophy, design, road map, and APIs.
*If it's part of the project, it's in the repo. If it's in the repo, it's part
of the project.* 

As a result, each decision can be expressed as a change to the repository.

All decisions affecting the BIO-SIG repository, both big and small, follow
the same steps:

 * **Step 1**: Open a pull request. Anyone can do this.

 * **Step 2**: Discuss the pull request. Anyone can do this.

 * **Step 3**: Maintainers merge, close or reject the pull request.

Pull requests are reviewed by the current maintainers of the BIO-SIG
repository.

简答：一切都是PR.

openEuler 核心项目和SIGs都是具有开放设计理念的开源项目。这意味着代码仓是项目各个方面的真实来源，包括其理念、设计、路线图和API。
如果它是项目的一部分，那么它就在代码仓中。如果它在代码仓中，它就是项目的一部分。

因此，每个决定都可以表示为代码仓的更改。

所有影响BIO-SIG代码仓的决策，无论大小，都遵循相同的步骤：

  * **第 1 步**：建立PR。 任何人都可以做到这一点。

  * **第 2 步**：讨论PR。 任何人都可以做到这一点。

  * **第 3 步**：Maintainer合并、关闭或拒绝PR。

PR由 BIO-SIG 代码仓的当前maintainer审查。
