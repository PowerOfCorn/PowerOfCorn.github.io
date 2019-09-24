# 如何睿智地写文档
[//]: # (Version:1.0.0)
人生太短，不能写没人会读的废话，如果你写了废话，没人会去读。所以好一点的文档是最好的。经理不会去理解这些东西，因为不好的文档会给他们错误的安全感以至于他们不敢依赖他们的程序员。如果一些人绝对坚持你真的在写没用的文档，就告诉他们“是的”，然后安静的找一份更好的工作。

没有其他事情比精确估计 把好的文档转为放松文档要求的估计 更为有效率。真相是冷酷而艰难的：文档，就像测试，会花比开发代码多几倍的时间。

首先，写好的文档是好的写作。我建议你找一些关于写作的事情，学习，练习他们。但即使你是一个糟糕的写手或者对你需要写文档的语言掌握不好，这条黄金规则是你真正需要的：己所不欲，勿施于人。花时间去确实地思考谁会读你的文档，他们从文档中想要获得的真正的东西是什么，并且你可以如何把这些东西交给他们。如果你这样做，你将会变成一个超过平均水平的文档编写者，和一个好的程序员。

当代码可以自成文档时，与提供文档给非程序员看相反，我认识的最好的程序员们有这样一个普遍的观点：编写具有自我解释功能的代码，仅在你不能通过代码清晰解释其含义的地方，才写注释。有两个好的原因：第一，任何人需要查看代码级别的文档大多数情况下都能够并且更喜欢阅读代码。不可否认的，有经验的程序员似乎比初学者更容易做到这件事，然而，更重要的是，没有文档的话，代码和文档不会是自相矛盾的。源代码最糟糕的情况下可能是错误并且令人困惑的。没有完美编写的文档，可能说谎，这可糟糕一千倍。

负责任的程序员也不能让这件事变得更简单些。如何写自解释的代码？那意味着什么？它意味着：

- 编写知道别人会去阅读的代码(译者注：编写给人看的代码)
- 运用黄金法则
- 选择直接的解决方案，即使你可以更快地获得另一个解决方案
- 牺牲那些可能混淆代码的小的优化
- 为读者考虑，把你珍贵的时间花在让她更加容易阅读的事情上,并且
- 永远不要使用这样的函数名比如 `foo`,`bar`, 或 `doIt`!

Next [如何在糟糕的代码上工作](06-How%20to%20Work%20with%20Poor%20Code.md)