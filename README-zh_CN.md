# MIA Wiki


[中文](./README-zh_CN.md)  [English](./README.md)

欢迎来到 **MIA Wiki**。

**MIA**（Medical Image Analysis，医学图像分析）是一门结合人工智能和医学图像处理的前沿学科。随着人工智能技术的快速发展，医学图像分析在提高诊断准确率、加快疾病识别速度方面发挥着越来越重要的作用。

**MIA** 领域涉及广泛，技术更新迅速。新手面临的挑战是如何系统性地学习相关知识。市面上关于此领域的资料往往零散且复杂，初学者需要花费大量时间理解和整合这些信息。

为了帮助对 **MIA** 感兴趣的朋友们更好地入门，2016年10月，**MIA Wiki** 在 Github 上进行了首次提交。随着内容的持续丰富，**MIA Wiki** 获得了越来越多医学和人工智能领域爱好者的关注，逐渐吸引了更多志同道合的朋友加入。

作为一个自由的知识平台，**MIA Wiki** 围绕人工智能在医学图像分析中的应用，对相关知识和技术进行详细介绍，帮助初学者更好地学习和理解这一领域。

目前，**MIA Wiki** 主要包括医学图像分析的基础知识，并正在努力完善以下内容：

- 医学图像分析的高级知识
- 医学图像分析中的经典案例研究

有关上述待完善内容，请参见 **MIA Wiki** 的 [Projects](https://github.com/Kent0n-Li/mia-wiki)，详细列出了在进行中和计划中的项目。

此外，**MIA Wiki** 基于医学图像分析，但不局限于此。在未来，**MIA Wiki** 还将：

- 介绍与医学图像分析相关的工具
- 更多地与实际医疗场景结合

鉴于以下两点，

- 知识应以开放的方式共享。
- 医学和人工智能技术总在不断演进，旧技术可能无法应对新挑战。

最后，**MIA Wiki** 源于社区，作为**独立组织**，提倡**知识自由**，未来也将坚持不商业化，保持**独立自由**的特性。

## How to build？

本文档目前采用 [mkdocs](https://github.com/mkdocs/mkdocs) 部署在 [https://mia-wiki.org](https://mia-wiki.org)。

本项目可以直接部署在本地，具体方式如下：

```shell
# 1. clone
git clone https://github.com/mia-wiki/mia-wiki.git
# 2. requirements
pip install -r requirements.txt
# generate static file in site/
python3 scripts/docs.py build-all
# deploy at http://127.0.0.1:8008
python3 scripts/docs.py serve
```

**mkdocs 本地部署的网站是动态更新的，即当你修改并保存 md 文件后，刷新页面就能随之动态更新。**


你只是想本地浏览，并不想修改文档？试试 Docker 吧！

```
docker run -d --name=mia-wiki -p 4100:80 MIAwiki/mia-wiki
```
随后即可在浏览器中访问 [http://localhost:4100/](http://localhost:4100/) 阅读 MIA Wiki 。

## How to practice？

首先，通过在线阅读来学习一些基本的安全知识。

其次，MIA Wiki 还有两个姊妹项目

- MIA Wiki 中涉及的题目在 [MIA-challenges](https://github.com/mia-wiki/MIA-challenges) 仓库中，请根据对应的分类自行寻找。
- MIA Wiki 中涉及的工具会不断补充到 [MIA-tools](https://github.com/mia-wiki/MIA-tools) 仓库中。

## How to make MIA Wiki Better？

我们非常欢迎你为 Wiki 编写内容，将自己的所学所得与大家分享。我们期待着你的加入！

**在你决定要贡献内容之前，请你务必看完 [CONTRIBUTING](https://mia-wiki.org/en/contribute/before-contributing/)**。其中包含了详细的贡献方式。 

非常感谢一起完善 MIA Wiki 的小伙伴们

<a href="https://github.com/mia-wiki/mia-wiki/graphs/contributors"><img src="https://opencollective.com/mia-wiki/contributors.svg?width=890&button=false" /></a>

## What can you get?

- 快速学习新事物的能力
- 不一样的思考方式
- 乐于解决问题的心
- 有趣的安全技术
- 充实奋斗的时光

在阅读 Wiki 之前，我们希望能给予你几点建议：

- 学习 [提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way)
- 善用 Google 搜索能帮助你更好地提升自己
- 至少掌握一门编程语言，比如 Python
- 动手实践比什么都要管用
- 保持对技术的好奇与渴望并坚持下去

> 世界很大，互联网让世界变小，真的黑客们应该去思考并创造，无论当下是在破坏还是在创造，记住，未来，那条主线是创造的就对了。 ——by 余弦

安全圈很小，安全的海洋很深。安全之路的探险，不如就从 **MIA Wiki** 开始！

## Copyleft
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。

