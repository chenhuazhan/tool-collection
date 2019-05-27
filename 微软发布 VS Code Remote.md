（ 北京时间 2019 年 5 月 3 日 ），在 PyCon 2019 大会上，微软发布了 VS Code Remote，开启了远程开发的新时代！这次发布包含了三款核心的全新插件，它们可以帮助开发者在容器，物理或虚拟机，以及 Windows Subsystem for Linux (WSL) 中实现无缝的远程开发。通过安装 Remote Development Extension Pack ，你可以快速上手远程开发。



**![img](https://mmbiz.qpic.cn/mmbiz_png/Pn4Sm0RsAuhzGbHK1kg8LtrlfLZaLaRRFCpuC4UboJhcO9Bm3KFt3picbagjYNXpaxq2vnToD3rIl68L6mVrQpQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)**

**远程开发**



![img](https://mmbiz.qpic.cn/mmbiz_png/Z4WC9OGHQlHrkTIM9FvggMDKOVughR131f7u9Q7QMxMvAeBHkwibXnz7bYCtJYguetTfWU2WOOj2bzicBXEibVmeA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

Visual Studio Code Remote 允许开发者将容器，远程计算机，或 Windows Subsystem for Linux (WSL) 作为完整的开发环境。你可以：

- 在部署相同的操作系统上进行开发，或者使用更大或更专业的硬件。
- 把开发环境作为沙箱，以避免影响本地计算机配置。
- 让新手轻松上手，让每个人都保持一致的开发环境。
- 使用原本在本地环境不可用的工具或运行时，或者管理它们的多个版本。
- 在 WSL 里开发 Linux 应用。
- 从多台不同的计算机访问现有的开发环境。
- 调试在其他位置（比如客户网站或云端）运行的应用程序。

所有以上的功能，并不需要在你的本地开发环境有源代码。通过 VS Code Remote，轻松连接上远程环境，在本地进行开发。



**![img](https://mmbiz.qpic.cn/mmbiz_png/Pn4Sm0RsAuhzGbHK1kg8LtrlfLZaLaRRSwIGDrNvhDVRTQOXpZibAW5eIkDB1Ug3E1wxtRj0mxD3DlRV8TXx6Iw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)**

**Remote Development extension pack**



![img](https://mmbiz.qpic.cn/mmbiz_png/Z4WC9OGHQlHrkTIM9FvggMDKOVughR13RdYj2pt39J2A1ms6aibbULCh5Gib5N6o8Zf4KSeQqtvR8peK7ds0TzicA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

Remote Development extension pack 包括三个扩展：

- **Remote - SSH** - 通过使用 SSH 打开远程计算机或者VM上的文件夹，来连接到任何位置。
- **Remote - Containers** – 把 Docker 作为你的开发容器。
- **Remote - WSL** - 在 Windows Subsystem for Linux 中，获得 Linux 般的开发体验。



**![img](https://mmbiz.qpic.cn/mmbiz_png/Pn4Sm0RsAuhzGbHK1kg8LtrlfLZaLaRR1egUapOLlzTibNHKa2HtxQgl0MHiblDkJlCqaPN3NVMIxkjV2U2ouELw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)**

**Remote – SSH**



![img](https://mmbiz.qpic.cn/mmbiz_png/Z4WC9OGHQlHrkTIM9FvggMDKOVughR13bFd6ALXIn1V7Qia4Pg1CJq0iawzn4M75tw6guaMR9GulDQofmHsMMG9w/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

- 在比本地机器更大、更快或更专业的硬件上进行开发。
- 在不同的远程开发环境之间快速切换，安全地进行更新，而不必担心影响本地计算机。
- 调试在其他位置运行的应用程序，例如客户网站或云端。

例如，假设你正在开展深度学习项目。您通常需要一个高GPU性能的虚拟机（例如 Azure Data Science Virtual Machine），配置了训练大数据模型所需的所有工具和框架。

你可以使用 Vim over SSH 或 Jupyter Notebooks 来编辑远程代码，但是你放弃了本地开发工具的丰富功能。相反地，使用 Remote-SSH 扩展，你只需连接到 VM，安装必要的扩展（如 Python 插件），然后你就可以利用VS Code的所有强大功能，如 IntelliSense、代码跳转和调试，就像你在本地开发一样。



**![img](https://mmbiz.qpic.cn/mmbiz_png/Pn4Sm0RsAuhzGbHK1kg8LtrlfLZaLaRR8bhmP5Dic6Efy9l8sy3ZgXndXQWKss4lqSSib0b7ks1COcZibTJlfKbFQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)**

**Remote – Containers**



![img](https://mmbiz.qpic.cn/mmbiz_png/Z4WC9OGHQlHrkTIM9FvggMDKOVughR13fsV6TuYtnBfMGnNBQ4vynt7cKIwMHV1nPWglicUxGIEDJiaSGdNXlicLw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

- 你可以在部署的同一操作系统上，使用一致的工具链进行开发。
- 容器是隔离的，这意味着你可以在不影响本地计算机的情况下在不同的开发环境之间快速切换。
- 其他人可以轻松地为你的项目做出贡献，因为他们可以在一致的开发环境中轻松开发、构建和测试。

一个 devcontainer.json 文件可以被用来告诉 VS Code 如何配置开发容器，包括使用的 Dockerfile、端口映射以及在容器中安装哪些插件等等。



**![img](https://mmbiz.qpic.cn/mmbiz_png/Pn4Sm0RsAuhzGbHK1kg8LtrlfLZaLaRRJRC7DY5BO55JNjqicFhWVOLibewGQCqxdLZqvibYwYDCPpRMTWKljcjIg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)**

**Remote – WSL**



![img](https://mmbiz.qpic.cn/mmbiz_png/Z4WC9OGHQlHrkTIM9FvggMDKOVughR13R5B0DIcsmcNoVAWgw2a9T3eiaITic0l5wJubKZHNmlPQ6j8iawNkUN3qw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

- 使用 Windows 在基于 Linux 的环境中进行开发，使用平台特定的工具链和程序。
- 编辑位于 WSL 中的文件或挂载的 Windows 文件系统（例如 /mnt/c）。
- 在 Windows 上运行和调试基于 Linux 的应用程序。

插件直接在 Linux 发行版中运行，因此你不需要担心路径问题、软件兼容性或其他跨平台的问题。你可以像在 Windows 中一样，在 WSL 中无缝地使用 VS Code。



**![img](https://mmbiz.qpic.cn/mmbiz_png/Pn4Sm0RsAuhzGbHK1kg8LtrlfLZaLaRRmaOOA7Gb9k6NVyydicGiafic9XEdkCWswKzOG7w7MqTI4VJnnQkBic4UYw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)**

**开发新时代！**



好了，说了这么多，不如直接上手来试试。赶紧下载 Remote Development Extension Pack 来一起玩转 VS Code Remote 吧！远程开发的新时代已经到来！

https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack



（北京时间 2019 年 5 月 7 日），在微软 Build 2019 开发者大会上，微软宣布了 Web 版本的 VS Code - **Visual Studio Online**。

相信读者们对 Web 版的 VS Code 期待已久了。对 VS Code 熟悉的朋友应该知道，VS Code 是基于 Electron 开发的，而 Electron 是使用 Web 技术栈（JavaScript、HTML 和 CSS）来开发跨平台桌面应用的。所以，把 VS Code 搬到浏览器中，则是必然的趋势。

此次 Build 大会上，微软发布了 Visual Studio Online 的 Private Preview 版本。开发者们现在就可以通过注册链接来申请试用 Visual Studio Online：https://aka.ms/vsfutures-signup



未来，通过 https://online.visualstudio.com ，你可以方便地连接到你的远程环境。Visual Studio Online 基于 Visual Studio Code，所以你能在浏览器中体验到许多在 VS Code 中的强大功能，包括各类的 VS Code 插件。同时，Visual Studio Online 支持打开 VS Code 和 VS IDE 的项目。此外，Visual Studio Online 还内置了 Visual Studio IntelliCode 和 Live Share，使得开发如虎添翼。

此外，微软还宣布了云端开发环境（Cloud-Hosted Development Environments）。开发者可以通过 Visual Studio Code 或者 Visual Studio 连上云端开发环境。当你在开发一个新项目，或者在 review 一个 PR 时，你可以快速地获取一个云端的开发环境。这使得开发者可以有更多的时间在 coding 上，而不是把时间浪费在搭建开发环境上。

