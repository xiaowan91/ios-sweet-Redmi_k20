# ios-sweet- ios 16.7.16 on Redmi K20 (davinci)

基于 ios-sweet (XNU 8796) 的分支。移植目标：Redmi K20 (SM7150-AA/ 骁龙730)。
该项目将苹果开源的XNU内核（xnu-8796，iOS 16）移植到小米Redmi k20（高通SM7150-AA）上。在其上运行着未修改的 iOS 16.7.16（20H392）

> [!WARNING]
> ⚠️ **警告：本项目为底层探索分支，尚未进行实机验证。**
> 
> - 目前生成的 `ios16-root.img`（EXT4）和 `shim-boot.img` 未在 K20 真机测试过。
> - 刷入此镜像会格式化 `userdata` 分区，导致你手机里的所有数据丢失！
> - 请勿将此分支的产物用于日常使用或主力机。刷机风险自担。
