
# 调试模式

`GF`框架的各个模块在一些关键功能节点会打印出一些调试信息，原本仅供框架内部开发者在开发阶段使用。这些调试信息默认情况下是关闭的，不会影响框架性能，框架的开发者和使用者可以通过以下方式打开：

1. 命令行启动参数 - `gf.debug=true`；
2. 指定的环境变量 - `GF_DEBUG=true`；


需要注意的是，框架的模块调试信息仅会输出到终端标准输出。