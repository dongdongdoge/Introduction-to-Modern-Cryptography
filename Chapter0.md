# 古典密码学介绍（前序）

本书的观点：旨在通过可用的，合理的顺序提供一个严格的对现代密码学主题的系统性介绍。

现代密码学源自1980年代后期开始，主要强调三点

1. 准确的定义

   - 共识：formal deﬁnitions of security are an essential ﬁrst step in the design of any cryptographic primitive or protocol
   - 如果不知道自己要实现什么，无从谈起安全本身，为安全证明提供工具。

2. 精确的假设

   - 共识：any such assumption must be clearly stated and unambiguously deﬁned.

   - 目前密码学组件不能被无条件证明或者证伪，精确合理的假设不仅提供了客观的评价指标，也为严格的安全证明提供工具。

3. 严格的安全性证明

   - 共识：cryptographic constructions can be proven secure with respect to clearly stated deﬁnitions of security and relative to well-deﬁned cryptographic assumptions.
   - 使得密码学的研究从艺术转变为一门科学。

以上三点是标准化的unified approach around the world.

与传统的密码学相对比

| classical     | modern                         |      |      |
| ------------- | ------------------------------ | ---- | ---- |
| Ad-hoc fasion | well defined and proved models |      |      |

背景知识

1. 熟悉基本的离散数学概率论与模算数
2. 熟悉算法（复杂度）与伪代码基本编写
3. 熟悉一般的抽象数学证明

书本内容

1. 古典密码学：1，2章
2. 对称加密：3（密钥加密），4（消息认证），5（哈希函数）章
3. 不对称加密：8（数论），9，10（最新技术）