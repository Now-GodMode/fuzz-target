# fuzz-target

> A repository for tracking fuzzing campaigns against high-risk libraries, with CVE hunting and exploit proof-of-concepts, primarily for patches of software vulnerabilities that are incomplete fixed.
>
> 用于跟踪针对高风险库的模糊测试活动的存储库，其中包含 CVE 搜寻和利用概念验证, 主要针对不完全修复的软件漏洞补丁对象

## OpenJPEG

* CVE-2019-6988 & CVE-2023-39328
* issue#1283 & CVE-2020-27814

## ImageMagick

* CVE-2022-32546 & CVE-2023-34151

## W3M

* CVE-2022-38223 & CVE-2023-4255

> [!TIP]
>
> .gitmodules 文件中包含了子模块相关信息
>
> 仓库中添加子模块：`git submodule add https://github.com/xxx.git savename`
>
> 切换到指定分支：`git checkout tags/v2.3.0`
>
> 克隆仓库的指定分支：`git clone -b branchname https://github.com/xxx.git`
>
> 克隆含子模块的仓库：` git clone --recursive git://github.com/xxx.git`
>
> 删除子模块：（过程较为复杂）
>
> * 删除子模块 cached 和文件夹
> * 删除 .gitmodules 中子模块信息
> * 删除 .git/config 中子模块信息
> * 删除 .git 文件夹中的相关子模块文件
