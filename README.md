# obs(open build service)

> 基于 [buildbot](https://www.buildbot.net/) 实现的定制化打包服务

## 目标

使用 buildbot + docker 实现打包过程，目前暂定需要实现的：
- 内核模块构建（同时支持多操作系统版本、多cpu架构）
- 整个项目打包（基于ubuntu18.04多cpu架构，部分二进制基于uos、kylin这样的国产化环境）

## 思路

