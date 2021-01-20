简体中文 | [English](https://github.com/imgcook/imgcook/blob/master/README.md)

# imgcook

[imgcook](https://www.imgcook.com/) 是阿里巴巴集团在前端智能化方向的落地产品，专注以 Sketch、PSD、静态图片等形式的视觉稿作为输入，通过智能化技术一键生成可维护的前端代码，包含视图代码、数据字段绑定、组件代码、部分业务逻辑代码。<br />

<p align="center">
  <a href="http://www.imgcook.com">
    <img alt="imgcook" src="https://img.alicdn.com/tfs/TB1pWhIk.H1gK0jSZSyXXXtlpXa-686-127.png" width="343">
  </a>
</p>

我们期望 imgcook (图像大厨) 能够利用智能化手段，成为一位 P5 级别的前端工程师，在对设计稿轻约束的前提下实现高度还原，释放前端生产力，助力前端与设计师高效协作，让您关注更具挑战性的事情！

我们期望能做到：

- 100% 还原：对设计师而言，减少视觉走查成本。
- 100% 兼容：对测试而言，减少 UI 适配成本。
- 极速上线：最重要的是对前端而言，可自动生成视图代码、数据字段绑定、组件代码和部分业务逻辑代码；以天猫双十一会场为例，目前生成代码的可用率为 79.43%（imgcook 生成被保留上线后代码 / 总模块总线上代码）。


## 产品功能

imgcook 的主要功能是视觉稿一键还原和基于还原后的可视化编辑，Sketch/Photoshop 设计稿的还原从安装插件开始，在设计稿中通过插件导出视觉稿的 JSON 描述信息粘贴到 imgcook 可视化编辑器，在编辑器中可以进行视图编辑、逻辑编辑等，生成代码后可将代码导出到本地或您的工程文件。主流程如下箭头所示。

<p align="center">
<img src="https://img.alicdn.com/tfs/TB1nCkvG1H2gK0jSZJnXXaT1FXa-1500-402.png" width="746">
</p>

除了视觉稿还原服务，我们还提供了如 imgcook-cli、imgcook VS Code 插件等工程效率工具，也支持用户自定义 DSL、自定义 Plugin 等。另外我们还在全链路探索 AI 赋予 imgcook 的能力，如图片生成代码、文本语义理解等。

对于创建的模块，您还可以按团队、项目维度来管理，如果您想看一些精选案例，可以前往广场查看。


## 使用场景

imgcook 目前支持各种场景的页面或模块的高度还原，您可以根据以下场景分类选择是否使用 imgcook。

- 移动端细粒度模块开发场景 - `特别推荐`
- 移动端活动页 - `特别推荐`
- 移动端全页面开发 - `推荐`
- PC 端 toC 应用 - `推荐`
- PC 端 toB 应用
- PC 端富交互应用 - `不推荐`
- 游戏场景 - `不推荐`


## 面向用户

如果您是一位设计师，遵循 imgcook 的设计稿规范，您可以产出高质量设计稿，自己试用或交付于开发，都可以实现一键还原！

如果您是一位开发者，可以使用规范化的设计稿，运用 imgcook 智能化策略及 imgcook 平台可视化辅助操作，实现页面的极速开发！

目前我们提供了 React、H5、Vue 等多种官方 DSL，您可以将视觉稿一键生成多种 DSL 代码。当然如果期望按照自己的需求生成代码，您也可以自定义 DSL，例如小程序规范、Ant-Design 组件等。

## 谁在使用

在阿里巴巴集团，imgcook 已承担了双 11 大促活动中所有模块的开发，在闲鱼、飞猪、蚂蚁保险等 BU 也有广泛使用。在集团外部，有赞、51信用卡等公司也在使用 imgcook 来提高前端开发效率。

<p align="center">
  <a href="http://www.imgcook.com">
    <img alt="imgcook" src="https://img.alicdn.com/tfs/TB1HX3_kF67gK0jSZPfXXahhFXa-1126-263.png" width="563">
  </a>
</p>


## 更多帮助

### 官方文档

[https://www.imgcook.com/docs](https://www.imgcook.com/docs)

### 问题反馈

[https://github.com/taofed/imgcook/issues](https://github.com/taofed/imgcook/issues)

### 钉钉交流

**社区同学** 请扫码加入 **社区群**，**阿里内部同学** 请加入 **内部群**。

<p align="center">
    <img src="https://img.alicdn.com/tfs/TB11kDbqUz1gK0jSZLeXXb9kVXa-993-1280.png" width="250">
    <img src="https://img.alicdn.com/tfs/TB1G02dqHr1gK0jSZR0XXbP8XXa-993-1280.png" width="250">
</p>
