# 隐私政策 / Privacy Policy

LeanPixel（轻像素）· 最后更新：2026-10-21

## 中文

### 一、我们不收集什么

LeanPixel 不会上传、传输或备份你的任何图片。所有压缩都在你的电脑本地完成，图片不会离开本机。

我们不收集姓名、邮箱、电话、位置、设备标识或使用行为数据。没有账号系统，无需注册即可使用全部免费功能。

### 二、哪些数据会写到你的电脑上

| 数据 | 位置 | 用途 |
| --- | --- | --- |
| 设置 | `%APPDATA%\LeanPixel\settings.json` | 记住你的压缩偏好 |
| 历史记录 | `%APPDATA%\LeanPixel\history.jsonl` | 在"历史记录"页显示最近处理过的文件 |
| 日志 | `%LOCALAPPDATA%\LeanPixel\leanpixel.log` | 出现问题时排查；可在设置中导出 |
| 崩溃记录 | 同上 | 记录未处理异常，便于反馈 |
| 剪贴板图片副本 | `%LOCALAPPDATA%\LeanPixel\cache` | 粘贴图片时的临时源文件 |

粘贴图片时，程序只在您按下 `Ctrl+V` 或全局热键时读取剪贴板，不会后台监听。

在 Microsoft Store 版本中，上述路径被系统重定向到 `%LOCALAPPDATA%\Packages\LeanPixel.Desktop_*\LocalCache` 下，仅本应用可读。

### 三、唯一的网络请求

应用可能发起一次 HTTPS 请求以检查新版本，请求内容仅包含当前版本号，不包含任何个人信息。该功能可在设置中关闭；Microsoft Store 版本由商店负责更新，不发起该请求。

购买 Pro 时的支付流程完全由 Microsoft Store 处理，我们不接触你的支付信息。是否拥有 Pro 权限由 Store 客户端 API 在你本机查询，我们不建立自己的账号或服务器。

### 四、数据删除

- 设置与历史：在设置页点"清空历史记录"，或直接删除 `%APPDATA%\LeanPixel` 目录。
- 卸载应用时，MSIX 会删除包数据目录；直装版卸载会执行 `--cleanup` 清理注册表项。
- 我们不保留任何服务端数据，因此无需申请删除。

### 五、儿童隐私

本应用不面向儿童设计，不收集任何个人信息。

### 六、变更与联系方式

政策变更会随应用更新发布在本文件。问题请联系：`liufeng_knight@163.com`。

---

## English

### What we do not collect

LeanPixel never uploads, transmits, or backs up your images. All compression runs locally on your PC; your files never leave the machine.

We collect no names, email addresses, phone numbers, location, device identifiers, or usage analytics. There is no account system and no sign-up is required to use the free feature set.

### Data written to your PC

| Data | Location | Purpose |
| --- | --- | --- |
| Settings | `%APPDATA%\LeanPixel\settings.json` | Remember compression preferences |
| History | `%APPDATA%\LeanPixel\history.jsonl` | Show recently processed files |
| Log | `%LOCALAPPDATA%\LeanPixel\leanpixel.log` | Troubleshooting; exportable from Settings |
| Crash record | same folder | Unhandled exceptions, for support |
| Clipboard copy | `%LOCALAPPDATA%\LeanPixel\cache` | Temporary source file when pasting |

The clipboard is read only when you press `Ctrl+V` or the global hotkey; there is no background monitoring.

In the Microsoft Store build these paths are redirected by Windows into `%LOCALAPPDATA%\Packages\LeanPixel.Desktop_*\LocalCache`, readable only by this application.

### The only network request

The app may make a single HTTPS request to check for a newer version. It sends the current version string and nothing else. This can be disabled in Settings. The Microsoft Store build is updated by the Store and does not make this request.

Pro purchases are handled entirely by Microsoft Store; we never see your payment details. Entitlement is queried locally through the Store client API — there is no account or server of ours.

### Deleting your data

- Settings and history: use "Clear history" in Settings, or delete `%APPDATA%\LeanPixel`.
- Uninstalling removes the package data folder; the standalone installer runs `--cleanup` to remove registry entries.
- We hold no server-side data, so there is nothing to request from us.

### Children's privacy

This app is not directed at children and collects no personal information.

### Changes and contact

Policy changes ship with application updates. Contact: `liufeng_knight@163.com`.
