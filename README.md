# ORBIT 应用启动器

Windows 应用启动与管理工作台。由 xuanju 维护。

## 安装与更新

请从 [Releases](https://github.com/xuanju-LN/orbit-launcher-releases/releases/latest) 下载 `ORBIT-Setup-版本号-x64.exe`。支持 Windows 10/11 x64。便携版可直接运行。

应用内打开“关于 ORBIT → 检查更新”。升级时先正常退出 ORBIT，再把安装目录选为原目录；程序会保留 config.json 并在升级前备份配置和旧 EXE。卸载保留用户配置。

默认安装到 D:\Applications\ORBIT；没有 D 盘时使用当前用户的应用目录，可自行选择。首次迁移便携版建议先导出配置，再在安装版中导入。

## 完整性校验

每个 Release 附 SHA256SUMS.txt。可使用 `Get-FileHash .\安装包文件名.exe -Algorithm SHA256` 核对。当前安装包未使用付费代码签名证书。

这是公开二进制发布仓库，不包含开发仓库、个人应用列表、凭据或记忆配置。

## 素材署名

地表/云层纹理由 Solar System Scope / INOVE 提供，CC BY 4.0：https://www.solarsystemscope.com/textures/ 。完整说明见每版 ATTRIBUTION.md。
