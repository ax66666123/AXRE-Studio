# Beta 发布审计状态

## 当前结论

`0.1.0-beta.41` 公开测试包已完成最小合规重构，可以作为 GitHub Pre-release 发布。

## 许可与载荷

- 自用版完整 Shader、Texture 和 Preset 库未进入公开安装包；
- 公开包仅内置 GITC Uplift v1.7.0 的 `Uplift.fx` 与 `UpliftMask.fx`；
- Shader/FXH 共 2 个，来源已确认 2 个，未确认 0 个；
- Texture 共 0 个，个人预设 0 个；
- 未包含 iMMERSE、RTGI、METEOR、NVIDIA DLL、Streamline 或 DLSS SDK；
- GITC Uplift、ReShade 和各 Add-on 的许可及上游资料随包保留。

## 自动检查

- 安装载荷文件：603；
- 源码、工程文件、PDB、证书私钥、混淆映射：0；
- 个人绝对路径：0；
- 静默安装、注册版本、文件清单和静默卸载：通过；
- 安装后 Shader 数量 2、Texture 数量 0：通过；
- 安装器已使用 AXBRO Beta 测试证书签名并添加 DigiCert 时间戳；
- 最终 SHA-256：`DB3F599067AEFE5C427D547D0F9FBC30090F7B1A1543A9346A6C7C897BD2841C`。

## 已知限制

Beta 测试证书不是公开受信任的商业代码签名证书，Windows 仍可能显示“未知发布者”。公开包采用最小效果库；其他效果应由用户根据原作者许可从可信上游自行安装。
