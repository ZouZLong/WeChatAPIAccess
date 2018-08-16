# WeChatAPIAccess
模拟微信的API接入，实现和微信客户端的功能交互


1.申请你的AppID
请到 开发者应用登记页面 进行登记，登记并选择移动应用进行设置后，将该应用提交审核，只有审核通过的应用才能进行开发。
微信开放平台->管理中心->创建移动应用->



<img height =“204” src =“https://cloud.githubusercontent.com/assets/464822/20228152/d3f36dc2-a804-11e6-80ff-51ada2d13ea7.png”>

＃[蓝图]（http://blueprintjs.com/）[！[CircleCI]（https://circleci.com/gh/palantir/blueprint/tree/develop.svg?style=svg）]（https：// circleci.com/gh/palantir/workflows/blueprint）

Blueprint是一个基于React的Web工具包。

它针对_desktop applications_构建复杂，数据密集的Web界面进行了优化。
如果您非常依赖移动互动并且正在寻找移动优先的UI工具包，那么这可能不适合您。

[**阅读介绍性博客文章▸**]（https://medium.com/@palantir/scaling-product-design-with-blueprint-25492827bb4a）

[**查看完整文档▸**]（http://blueprintjs.com/docs）

[**阅读我们在维基上的常见问题▸**]（https://github.com/palantir/blueprint/wiki/Frequently-Asked-Questions）

##：tada：3.0就在这里！：田田：

[** 3.0更改日志和迁移指南▸**]（https://github.com/palantir/blueprint/wiki/3.0-Changelog）

Blueprint 3.0通过更改命名空间来删除​​全局样式和解除冲突选择器，从而在同一页面上支持多个主要版本的Blueprint。它还在大多数软件包中恢复了对React 15的支持。

###从1.x升级

查看维基上的[** 2.0 changelog **]（https://github.com/palantir/blueprint/wiki/What's-new-in-Blueprint-2.0），并确保查看[** 2.0]迁移指南**]（https://github.com/palantir/blueprint/wiki/What's-new-in-Blueprint-2.0#migration-path），除上述3.0内容外。

##包

该存储库包含`packages /`目录中的多个项目，分为3类：

###图书馆

这些是我们发布到NPM的组件库。

-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/core.svg?label=@blueprintjs/core）]（https://www.npmjs.com/package/@ blueprintjs / core）＆ndash; 核心款式和组件。
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/datetime.svg?label=@blueprintjs/datetime）]（https://www.npmjs.com/package/@ blueprintjs / datetime）＆ndash; 用于与日期和时间交互的组件。
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/icons.svg?label=@blueprintjs/icons）]（https://www.npmjs.com/package/@ blueprintjs / icons）＆ndash; 用于生成和显示图标的组件。
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/select.svg?label=@blueprintjs/select）]（https://www.npmjs.com/package/@ blueprintjs / select）＆ndash; 用于从列表中选择项目的组件。
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/table.svg?label=@blueprintjs/table）]（https://www.npmjs.com/package/@ blueprintjs / table）＆ndash; 可扩展的交互式表组件
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/timezone.svg?label=@blueprintjs/timezone）]（https://www.npmjs.com/package/@ blueprintjs / timezone）＆ndash; 用于挑选时区的组件。
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/labs.svg?label=@blueprintjs/labs）]（https://www.npmjs.com/package/@ blueprintjs / labs）＆ndash; 新组件的孵化器和临时区域仍处于初始开发阶段。

###应用程序

这些作为静态Web应用程序托管在GitHub页面上：

- `docs-app`＆ndash; 文档站点在blueprintjs.com/docs
- `landing-app`＆ndash; 登陆页面在blueprintjs.com

这些用作开发游乐场环境：

- `table-dev-app`＆ndash; 支持手动测试所有表格功能的演示页面

###构建工具

这些包定义了开发依赖项并包含构建配置。它们遵循标准的NPM包布局，这允许我们为构建配置保持清晰的API边界并隔离`devDependencies`组。它们被发布到NPM，以允许其他与蓝图相关的项目在这个monorepo之外使用这个基础设施。

-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/docs-theme.svg?label=@blueprintjs/docs-theme）]（https://www.npmjs.com / package / @ blueprintjs / docs-theme）＆ndash; [Documentalist]（https://github.com/palantir/documentalist）数据的文档主题。
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/karma-build-scripts.svg?label=@blueprintjs/karma-build-scripts）]（https：// www .npmjs.com /包/ @ blueprintjs /卡玛 - 集结脚本）
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/node-build-scripts.svg?label=@blueprintjs/node-build-scripts）]（https：// www .npmjs.com /包/ @ blueprintjs /节点生成的脚本）
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/test-commons.svg?label=@blueprintjs/test-commons）]（https://www.npmjs.com /包/ @ blueprintjs /测试公地）
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/tslint-config.svg?label=@blueprintjs/tslint-config）]（https://www.npmjs.com /包/ @ blueprintjs / tslint-CONFIG）
-  [！[npm]（https://img.shields.io/npm/v/@blueprintjs/webpack-build-scripts.svg?label=@blueprintjs/webpack-build-scripts）]（https：// www .npmjs.com /包/ @ blueprintjs /的WebPack建造的脚本）

##贡献

寻找有助于代码库的地方？
首先阅读[贡献指南]（https://github.com/palantir/blueprint/blob/develop/CONTRIBUTING.md），
然后[查看“求助”标签]（https://github.com/palantir/blueprint/labels/help%20wanted）。

##开发

[Lerna]（https://lernajs.io/）管理此monorepo中的包间依赖关系。
构建是通过`lerna run`和NPM脚本编排的。

__Prerequisites __：Node.js v8 +，Yarn v1.0 +

###一次性设置

克隆此repo后，运行：

1.` yarn`安装所有依赖项。
1.“纱线验证”以确保所有构建工具正常工作。

###纳入上游变更

如果您之前处于工作状态并且刚刚从`develop`中提取了新代码：

- 如果有包依赖项更改，请在根目录下运行`yarn`。
  - 如果没有要安装的新东西，此命令非常快。
- 运行`yarn compile`以获取此repo中库包的最新版本。
  - 这个命令比`yarn verify`更快，因为它不构建应用程序包（`docs-app`，`landing-app`等）或运行测试

###开发库

从根目录运行`yarn dev`以观察所有包的更改，并使用webpack-dev-server运行docs应用程序。

或者，每个库都有自己的开发脚本来运行docs app并观察对该包（及其依赖项）的更改：`yarn dev：core`，`yarn dev：datetime`等。
一个例外是`table`：因为它有自己的dev应用程序，`dev：table`脚本运行`table-dev-app`而不是docs。

###更新依赖项

1.编辑您希望更改依赖关系的`package.json`。
1.在根目录下运行`yarn`来更新锁定文件。
1.提交结果。

###更新文档

Blueprint的大部分文档都存在于源代码中，如`.tsx`文件中的JSDoc注释和`.scss`文件中的KSS标记。使用[documentalist]（https://github.com/palantir/documentalist/）提取此文档并将其转换为静态JSON数据。

如果要更新文档源（_not_文档UI代码，它们位于`packages / docs-app`或`packages / docs-theme`中的docs主题），则需要从`packages /运行`yarn compile` docs-data`查看应用程序中反映的更改。为简单起见，根目录中存在别名脚本`yarn docs-data`以最小化目录跳转。

###更新图标

[一次性设置]（＃一次性设置）和[合并上游更改]（#incining-upstream-changes）步骤应生成生成的
此repo中的源代码用于构建图标文档。这对于大多数开发工作流程来说已足够。

如果要更新图标或添加新图标，则需要在`packages / icons`中运行`yarn compile`以查看之前反映的更改
运行任何开发脚本。

＃＃ 执照

该项目基于Apache 2.0许可证，以其自己的** Blueprint License **提供。

唯一的修改是我们要求的附加部分（第10段）
您没有将任何衍生产品作为Palantir的产品予以转让
Blueprint是一个设计工具包。
