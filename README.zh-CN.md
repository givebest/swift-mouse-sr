# Mouse SR

[English](README.md) | 简体中文

Mouse SR 是一款 macOS 小工具，主要解决两件事：让普通鼠标的滚轮更顺滑，以及给 Finder 增加几个顺手的右键操作。

如果你觉得第三方鼠标滚动时总是一格一格地跳，Mouse SR 可以把它变成连续滚动。滚动距离、平滑程度、加速度和方向都能按自己的习惯调整，不会改变触控板等原本就支持连续滚动的设备。

![Mouse SR 的平滑滚动与 Finder 右键工具](screenshots/01-overview.webp)

## 下载

[下载最新版 Mouse SR for Mac](https://github.com/givebest/swift-mouse-sr/raw/refs/heads/main/releases/MouseSR.dmg)

Mouse SR 支持 **macOS 15 及以上版本**。建议下载 `.dmg` 安装包，打开后将 Mouse SR 拖入“应用程序”文件夹即可。

首次使用平滑滚动时，macOS 会要求授予“辅助功能”权限，应用会引导你打开对应的系统设置。Finder 右键工具需要另外启用 Mouse SR Finder 扩展，并在应用中选择允许使用这些菜单的文件夹。

Mouse SR Pro 提供 7 天完整功能试用，试用不会自动续费或扣费。试用结束后，平滑滚动和 Finder 右键工具会暂停使用；你可以[一次性购买永久版](https://hp60.com/mouse-sr/pricing/)，不需要订阅，一份许可证最多可激活 3 台 Mac。

## 平滑滚动

Mouse SR 会把鼠标滚轮一格一格的生硬跳动，转换成更连贯的滚动。你可以分别调整：

- 每格滚动多远
- 滚动有多平滑
- 连续滚动时的加速度
- 鼠标滚动方向

应用平时可以待在菜单栏，需要时随手开启或暂停。

![调节鼠标滚轮的距离、平滑程度、加速度和方向](screenshots/02-smooth-scrolling.webp)

## Finder 右键工具

启用 Finder 扩展后，菜单会根据你右键的位置和所选项目显示对应操作，包括：

- 在终端中打开当前文件夹或选中的文件夹
- 新建空白 TXT 文件
- 新建空白 Markdown 文件
- 复制文件或文件夹路径

你可以自己选择哪些文件夹显示这些菜单，其他位置不会受到影响。新建文件遇到重名时，Mouse SR 也会自动换一个可用的名称。

![在 Finder 右键菜单中打开终端、新建文件或复制路径](screenshots/03-file-actions.webp)

## 隐私

鼠标处理和文件操作都在你的 Mac 本机完成。Mouse SR 不会上传鼠标输入、文件内容或文件路径；Finder 工具也只会出现在你主动选择的文件夹及其子文件夹中。

激活永久版时，应用会向许可证服务发送许可证密钥、随机生成的安装标识、Mac 名称和应用版本。定期校验也会发送必要的许可证及版本信息，但不会发送鼠标活动或文件数据。

遇到问题可以[联系支持](https://hp60.com/mouse-sr/about/contact/)。另请参阅[隐私政策](https://hp60.com/mouse-sr/about/privacy/)和[使用条款](https://hp60.com/mouse-sr/about/terms/)。
