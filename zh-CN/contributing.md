# 开发规范: 贡献代码

Cortex 是开源项目，欢迎大家对 cortex 进行改进或在 cortex 基础上进行开发。目前标准的仓库在 [GitHub](https://github.com/cortexjs/cortex)。


## 如何贡献你的修改

作为开发者可以 [fork](https://help.github.com/articles/fork-a-repo) 仓库到自己的帐户下。（你一定有 github 帐户的对吧， 什么?! 还没有，赶紧去注册一个吧）

在修改代码之前，建议花几分钟想清楚

你可以在自己 fork 的版本上进行修改，建议创建新的分支，如:

    git checkout -b <new-branch>

当你已经完成程序的修改和编写，测试好了之后，便可以在 _GitHub_ 上提交 _Pull Request_了。 可以参考文章 [Creating a pull request](https://help.github.com/articles/creating-a-pull-request)

### 动手之前

1. 在动手之前，请先确认你的本地电脑上已经获取了最新的代码，如果你之前 fork 过，请先跟 [原项目进行同步](https://help.github.com/articles/fork-a-repo#pull-in-upstream-changes)。
2. 如果想帮助 cortex 修正一个 bug, 可以先到 [issues](https://github.com/kaelzhang/cortex/issues?state=open) 列表中查看是否已经有人提交这个 bug 了，以免重复。
3. 在修复任何 bug 之前，最好的做法是[先提交新的 issue](https://github.com/kaelzhang/cortex/issues/new)。
4. 如果觉得自己想法不够成熟，也可以在你的 issue 中 / 社区 / QQ群 / 邮件组里呵大家讨论。

### 如何写更好的 git comments

见 [git-comments.md](./git-comments.md)

### 原则和注意项

* 最小改动原则：尽量用最小的改动来实现目标。
* 在进行大的改进前请务必先 [提交 issue]()，或者在 [google group](http://ctx.io/-group) 或者 [mail group](mailto:cortexjs@googlegroups.com) 中提出，以免重复劳动或者在错误的方向上前进。
* 保证向后兼容, 不论是修改bug还是新增feature，都请保证现有的API和命令行接口。


### 加入核心开发团队

嘛，先邮件联系 [i@kael.me](mailto:i@kael.me)，我们先聊聊，如果有可能 —— 比如你也在上海 —— 先出去喝一杯怎么样？

