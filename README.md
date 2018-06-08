# C#

- .Net Framework

	1. 什么是.net framework:
		
		- 微软为开发应用程序而创建的一个具有革命意义的平台
		- 主要包含一个庞大的代码库，可以在客户端与语言中，通过面向对象程序设计来使用这些代码 
		- CTS(Common Type System):公共类型系统 
		- CLR(Common Language Runtime):公共语言运行库，它负责管理用.net库开发的所有应用程序的执行
		- 库分为不同的模块
		- 使用.Net Freamework 编写程序，就是使用.Net代码库编写代码
		
	2. 编译使用.net framework库的代码 
	    
		- 第一阶段先编译为通用中间语言GIL(Common Intermediate Language)【或者叫做IL】,然后由JIT(Just In Time)编译器将GIL编译为专用于OS和目标机器结构的本机代码。目前有几种JIT编译器每种编译器都适用于不同的结构。CIL会使用合适的编译器创建所需的本机代码。
		- 编译应用程序时，所创建的CIL代码存储在一个程序集中。
		- GAC(Global Assembly Cache):全局程序集缓存，放置可重用的代码

	3. 创建.Net程序所需的步骤（p6）
