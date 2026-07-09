# 每个程序员都应该知道的延迟数字

这是一个交互式延迟数字页面，用时间线展示 1990 到 2026 年间 CPU、内存、网络和存储延迟的变化。页面可以帮助工程师直观理解不同硬件层级之间的数量级差异，也适合作为性能预算、系统设计评审和工程培训时的参考材料。

## 来源

本页面基于 Colin Scott 的交互式作品 **Latency Numbers Every Programmer Should Know** 构建，并继承了 Jeff Dean / Peter Norvig 经典清单 **Numbers Everyone Should Know** 的核心内容。

页面将原时间线扩展到 2026 年，并参考 Omar Bohsali 的 **Latency Numbers You Should Know in 2026**、Erick Guan 的 2024 年延迟数据，以及其他公开资料，对现代 CPU、DRAM、PCIe、NVMe、网络和 HDD 指标进行了补充与校验。

## 作用

这个页面用于回答一个工程实践中经常出现的问题：一次缓存命中、一次主存访问、一次网络往返、一次 SSD 或 HDD 读取，彼此到底相差多少。

通过拖动年份滑块，读者可以看到不同技术演进速度的差异：有些指标持续改善，有些指标受到物理、地理距离、机械结构或一致性协议限制，已经进入平台期。

## 译者

中文版本由 [LLQuant](https://github.com/llquant/) 翻译、校对并整理。
