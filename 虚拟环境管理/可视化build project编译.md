# 可视化build project 编译
## 操作步骤
1.打开项目
2.创建并开启虚拟环境
3.点击build project 按钮进行交叉编译

## 预期结果

能够调用虚拟环境中的交叉工具链，执行交叉编译，最终产物为riscv架构

## 实际结果

能够调用虚拟环境中的交叉工具链，会调用宿主机工具链，编译产物为宿主机架构

[PR 138修复（build）：通过VenV感知策略和日志记录增强构建系统检测](https://github.com/ruyisdk/ruyisdk-vscode-extension/pull/138)暂未合并，等待后期复查。
