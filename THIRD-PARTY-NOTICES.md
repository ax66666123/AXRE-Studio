# 第三方组件、来源与许可

[简体中文](THIRD-PARTY-NOTICES.md) | [English](THIRD-PARTY-NOTICES_EN.md)

AXRE Studio 与 ReShade、NVIDIA 及任何游戏厂商不存在隶属、赞助或官方认可关系。第三方名称和商标归各自权利人所有。

## 随发布包提供的组件

| 组件 | 作者/项目 | 来源 | 许可 |
| --- | --- | --- | --- |
| ReShade / ReShade64.dll / injector | crosire 及贡献者 | [crosire/reshade](https://github.com/crosire/reshade) | BSD 3-Clause |
| OBS Capture ReShade Add-on | ReShade 项目 | [ReShade 示例](https://github.com/crosire/reshade/tree/main/examples/11-obs_capture) | BSD 3-Clause |
| GITC Uplift v1.7.0 | ghostinthecamera 及贡献者 | [官方项目](https://github.com/ghostinthecamera/GITC-Uplift) | MIT，另含上游第三方声明 |
| IGCS Connector | Frans Bouma | [FransBouma/IgcsConnector](https://github.com/FransBouma/IgcsConnector) | MIT |
| Shader Toggler | Frans Bouma | [FransBouma/ShaderToggler](https://github.com/FransBouma/ShaderToggler) | MIT |
| ReShade Effect Shader Toggler | Frans Bouma、alex、社区维护者 | [Pav-Osmolski/ReshadeEffectShaderToggler](https://github.com/Pav-Osmolski/ReshadeEffectShaderToggler) | MIT |
| .NET / Windows App SDK / WinUI 3 / WebView2 | Microsoft 及贡献者 | [dotnet/runtime](https://github.com/dotnet/runtime)、[WindowsAppSDK](https://github.com/microsoft/WindowsAppSDK) | 各项目随附许可 |

安装包内应保留上述项目的完整 LICENSE、README 和 NOTICE 文件。本页只是索引，不能替代上游完整许可证。

## 仅提供兼容入口或链接

NVIDIA DLSS、Streamline、NGX 运行库属于 NVIDIA 专有组件。AXRE 不分发 `nvngx_*.dll`、`sl.*.dll`、DLSS SDK 或其他 NVIDIA 专有运行库。用户必须从 NVIDIA 官方或其他明确合法的渠道自行取得，并遵守相应条款。

- [NVIDIA DLSS 开发者入口](https://developer.nvidia.com/rtx/dlss)
- [GITC Uplift 官方发布](https://github.com/ghostinthecamera/GITC-Uplift/releases/tag/v1.7.0)
- [GITC Uplift 中文项目](https://github.com/pennyone4/GITC-Uplift-Chinese)

## 不进入公开发布包

- iMMERSE Ultimate、RTGI、METEOR 及要求单独授权或含专有声明的文件；
- 来源不明或无法确认再分发许可的 Add-on、Shader、纹理和预设；
- NVIDIA 专有运行库及重复的 DLSS/Streamline 文件；
- 用户个人预设、截图、游戏配置、日志和绝对路径；
- 签名私钥、测试证书私钥、混淆映射和内部调试材料。

效果与纹理可能分别采用 MIT、BSD、GPL、CC 或专有许可。没有明确来源和许可的文件，默认不得进入公开发布包。
