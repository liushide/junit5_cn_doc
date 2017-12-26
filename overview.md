## 1. 概述

这个文档的目标是为程序员编写测试、扩展者和构建工具和IDE供应商的引擎作者以及提供全面的参考文档。  
此文档也可作为[PDF下载](http://junit.org/junit5/docs/current/user-guide/index.pdf)。

### 1.1. JUnit 5是什么？

与以前的JUnit版本不同，JUnit 5是由三个不同子项目的几个不同的模块组成。  
**JUnit 5 = JUnit Platform（平台） + JUnit Jupiter（朱庇特（主宰）） + JUnit Vintage（过时版、老版本）**

**JUnit Platform：**是在JVM上启动测试框架的基础。它还定义了用于开发平台上运行的测试框架的TestEngine API。此外，该平台还提供了一个控制台启动器，可以从命令行启动平台，并为Gradle和Maven构建插件，以及一个基于JUnit 4的运行器，用于在平台上运行任何TestEngine。

**JUnit Jupiter：**是在JUnit 5中编写测试和扩展的新编程模型和扩展模型的组合。Jupiter子项目为在平台上运行Jupiter的测试提供了一个TestEngine （测试引擎）。

**JUnit Vintage：**提供了一个在平台上运行JUnit 3和JUnit 4的测试引擎。

### 1.2. 支持的java版本

JUnit 5在运行时需要Java 8\(或更高版本\)。但是，您仍然可以用先前JDK版本编译的代码进行测试。

### 1.3. 获得帮助

问关于JUnit 5的相关问题（[Stack Overflow](https://stackoverflow.com/questions/tagged/junit5)），或者和我们一起讨论（[Gitter](https://gitter.im/junit-team/junit5)）。

