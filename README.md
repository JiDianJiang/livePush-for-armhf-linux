# livePush-for-armhf-linux
无人值守直播推流bash脚本，ARMhf Linux适用。

这是【Alpha】版本，处于开发阶段，仍然需要更多的探索和发现。

```
Copyright (c) 2023 机电匠(JiDianJiang)

该代码库使用 GNU General Public License v3.0 许可证进行发布，
具体许可证条款请参阅 LICENSE 文件。

GNU General Public License v3.0 (GPLv3)是一种Copyleft授权的开源软件许可证。
以下是GPLv3许可协议的主要权利和义务：

A.权利：
1.复制和分发：
  使用者可以复制和分发软件的副本，以及修改后的版本，只要他们也使用GPLv3许可协议分发。
2.访问源代码：
  使用者可以访问软件的源代码，以便了解软件的工作原理，并对其进行修改和重新分发。
3.修改和衍生作品：
  使用者可以修改软件并创建衍生作品，只要他们也使用GPLv3许可协议分发。
4.私人使用：
  使用者可以私人使用软件，而不受许可协议的限制。

B.义务：
1.公开源代码：
  如果使用者在软件中使用GPLv3许可协议的部分或全部代码，
  他们必须公开这些代码，并使用GPLv3许可协议进行分发。
2.包含许可证和版权声明：
  使用者必须在每个软件副本中包含许可证和版权声明，以及代码中的相应注释。
3.承认贡献者：
  如果使用者对软件进行了修改，并分发了该修改后的版本，
  则必须在修改后的版本中承认原始作者和其他贡献者的贡献。
4.没有附加限制：
  使用者不能添加任何附加限制或限制，
  这些限制可能会阻止其他人行使其在GPLv3许可协议下的权利。

总之，GPLv3许可协议允许使用者自由使用、复制、修改和分发软件，
但要求在使用和分发软件时公开源代码，并保留许可协议和版权声明。
```

ARMhf 指 ARM HF（armhf）架构的处理器，适用范围如下：（未全部测试）

```
ARM Cortex-A系列处理器：
Cortex-A7(已测)、Cortex-A8、Cortex-A9、Cortex-A15、Cortex-A17、Cortex-A53、
Cortex-A57、Cortex-A72、Cortex-A73、Cortex-A75、Cortex-A76、Cortex-A77、
Cortex-A78、Cortex-A79。

Qualcomm Snapdragon系列处理器：
Snapdragon 200系列、Snapdragon 400系列、Snapdragon 600系列、
Snapdragon 700系列、Snapdragon 800系列。

MediaTek系列处理器：
MT65xx系列、MT67xx系列、MT81xx系列、MT83xx系列、MT85xx系列。

Samsung Exynos系列处理器：
Exynos 3系列、Exynos 4系列、Exynos 5系列、Exynos 7系列、Exynos 9系列。

Rockchip系列处理器：
RK30xx系列、RK31xx系列、RK32xx系列、RK33xx系列、RK3368、RK3399
```

## 使用说明：

```
只需要运行bash脚本文件‘livePush’就能执行所有功能，
‘livePush’启动后，有菜单提示，对新手操作很友好。
文件夹‘op’和‘install’里面的文件运行时需要它们配合，
请不要改变它们和脚本文件‘livePush’的相对位置。

需要注意的是，你需要在命令行来执行这个脚本，所以只需要安装服务器版本的Linux。
```

## Beta 版本（公测版）获取方式：

```
这是【Beta】版本，处于测试阶段，相对比较稳定，但仍会出现某些问题或不稳定。

【Beta】版本的性能，仍然是优于处于开发阶段的【Alpha】版本，
并且，能为您节约至少2个月的开发和测试时间（这只是经验估计，且无法精确衡量），
它更适合投入到项目中使用。

【Beta】版本，所使用的ffmpeg从v4版本升级到了v5版本，
并且，扩展了适用范围，适用于x86_32、x86_64、arm_64、armhf、armel架构的处理器，
已在centOS @ x86_64、Ubuntu @ armhf正常运行。

下面的内容，是您了解并认同的：
1.对于【Beta】版本的源代码，我们使用 收费 方式来分发；
2.收取的费用，仅仅用于平衡这个项目的预先投入和后续迭代，而非其他用途；
3.分发的源代码仍然使用 GNU General Public License v3.0 许可证进行发布；
4.迭代的执行时间，将根据我们收集的用户和市场的反馈来确定，这将是一个不固定的时间；
5.您需要具备对源代码的阅读能力，我们除了提供必要的使用说明，不提供任何形式的服务；
6.您了解任何阶段的软件，都无法确保不会出现问题，无论您是以何种方式获得的；
7.如果，用户有特别的订制需求，请另外与作者商谈。

Beta 版本（公测版）获取方式：
1.B站：发布在‘机电匠的工房’里
  https://mall.bilibili.com/neul-next/index.html?page=mall-up_itemDetail&noTitleBar=1&from=items_share&msource=items_share&itemsId=1102396023
2.淘宝：发布在‘机电匠自营店’里

上述发布渠道，可能会有延迟或变更，我们会尽快在这里更新。
```
