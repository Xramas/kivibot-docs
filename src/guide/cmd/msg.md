# KiviBot 消息命令

`KiviBot` 🤖 没有 UI 界面，插件管理、管理变更、状态监控通过 **QQ 消息命令**实现。

向机器人发送 `#帮助` 可查看所有框架命令，**仅限管理员使用**，私聊群聊均有效。

### 消息命令列表

下表列出了框架所有的管理员消息命令列表

消息命令里的尖括号代表此处应该填写变量，**实际发送的时候不需要加尖括号**，按实际情况输入

| 管理员消息命令        | 功能与说明                                     |
| --------------------- | ---------------------------------------------- |
| `#帮助`               | 显示框架命令列表                               |
| `#状态`               | 检测并上报当前机器人状态以及系统状态           |
| `#插件`               | 查看插件相关的消息命令及其格式                 |
| `#插件 列表`          | 查看本地所有检测到的插件                       |
| `#插件 启用 <插件名>` | 通过插件名启用指定插件                         |
| `#插件 重载 <插件名>` | 通过插件名重载指定插件                         |
| `#插件 禁用 <插件名>` | 通过插件名禁用指定插件                         |
| `#插件 启用所有`      | 启用所有检索到的插件                           |
| `#插件 禁用所有`      | 禁用所有检索到的插件                           |
| `#设置`               | 查看框架设置消息命令及其格式                   |
| `#设置 详情`          | 查看框架详细设置                               |
| `#设置 加管理 <qq>`   | 添加机器人管理并立即生效                       |
| `#设置 删管理 <qq>`   | 删除机器人管理并立即生效                       |
| `#设置 开启通知`      | 开启机器人消息通知，仅通知主管理员             |
| `#设置 关闭通知`      | 关闭机器人消息通知，仅通知主管理员             |
| `#设置 检查更新`      | 检查所有依赖（KiviBot、oicq 等）的新版本并更新 |
| `#关于`               | 查看框架介绍、版本号等                         |
