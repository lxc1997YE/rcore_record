# rcore_record
2023a-rcore-record

记录rcore学习文档

------

Day1
====
### 计划
1. 配置实验环境代码
2. 学习PPT for RISC-V特权指令级架构
3. 阅读指导文档ch1章节

### 成果
1. 环境配置完成
2. 学习了解 RISC-V指令到底是个啥，明白为啥要用qemu等一系列的工具，后续更新个文档记录一下内容
3. 学习了如何完成一个最简单的LibOS，基本的代码框架如何实现


Day2
====
### 计划
1. 总结RISC-V PPT知识点
2. 阅读 ch2 章节
3. 科研ing，领域泛化代码调试中，苦逼科研人

### 成果
1. 知识点汇总：https://github.com/lxc1997YE/rcore_record/blob/main/rcore/RISC-V.md 
2. 学习了特权级是如何切换的，只是汇编代码看的是在头疼，Trap是如何保存上下文的一些细节还是没太明白，既然内核栈用于保存Trap上下文，那么用户栈在这个过程中扮演的角色是什么呢？这部分还要再仔细阅读。
3. 学习了如何借助syscall实现应用程序代码，以及syscall的运作逻辑。