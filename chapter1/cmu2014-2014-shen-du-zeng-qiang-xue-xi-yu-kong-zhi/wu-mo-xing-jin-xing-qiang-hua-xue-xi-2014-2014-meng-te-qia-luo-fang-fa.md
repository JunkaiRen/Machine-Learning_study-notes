总结Summary

* MC 相对于DP\(Dynamic Programming, 动态规划\)具有很多优点：

* 可以直接从环境交互中学习\(interaction with environment\)

* 不需要完整的模型

* 不需要学习所有的状态（即不需要引导\(bootstrapping\)）

* 能较少地受到违背了马尔科夫特性\(Markov property，之后会讲\)带来的影响

* MC方法提供了一种交替策略评估过程\(alternate policy evaluation process\)

* 需要注意的一个问题： 需维持足够的探索\(maintaining sufficient exploration\):为了让策略评估能效力于动作值\(action value\)，我们必须确保连续的探索，以上两者都是以这个为前提的。



