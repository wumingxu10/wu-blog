# 编译方案

## 自己重新写一份makefile，通过gcc编译
 - 耗时，多人开发时还需额外维护makefile
 - 不能直接通过s32ds导入后直接编译

 ## 基于s32ds，自动生成makefile编译
 - windows、linux下都有s32ds安装包
 - 可直接调用命令导入s32ds项目后直接编译，makefile有s32ds接管
 - 可打包成docker image