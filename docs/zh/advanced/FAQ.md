---
headerDepth: 3
icon: iconfont icon-ask
category: [FAQ]
order: 1
comment: false
description: 本页包含了一些常见的与用户网络和程序生命周期问题相关的问题及解决方案。
banner: https://opengraph.snapgenshin.cn/generate?url=https://hut.ao/zh/advanced/faq.html&has_description=False
---

# 其他常见问题

### 如何创建胡桃的桌面快捷方式（非管理员模式）

::: tip 社区力量
感谢 [CzHUV 提供的解决方案](https://github.com/DGP-Studio/Snap.Hutao.Docs/issues/12)
:::

- `Win+R` 呼出运行窗口，在窗口中输入`shell:AppsFolder`
  ![Run](https://img.alicdn.com/imgextra/i3/1797064093/O1CN01Jj8c6i1g6du728e5A_!!1797064093.png_.webp)
- Windows 会弹出应用程序目录，找到胡桃工具箱
- 右键，点击 “创建快捷方式”
- 根据提示操作你就可以获得一个桌面快捷方式了

### 如何创建胡桃的桌面快捷方式 （管理员模式）

你可以在程序设置页面中点击 “创建快捷方式” 来在桌面上添加一个具有管理员权限的快捷方式

### 如何让胡桃工具箱开机自动启动

- 请参考如下思路
  - 可以自行创建一个批处理文件，内容参考[此 issue](https://github.com/DGP-Studio/Snap.Hutao/issues/184) 中，令胡桃以管理员模式直接运行的命令。
  - 设置一个**计划任务程序**令上述批处理文件开机自启，或将上述批处理文件加入**启动项**中
  - 使用 `SkipUAC` 等可以使软件以管理员身份静默自启的程序
- 或其他可以使胡桃工具箱开机自启的思路，敬请自行探索

::: warning
请注意，上述各种办法均可能在实际使用中因种种问题而失效。我们并不支持尝试使胡桃开机自启的行为。
:::

### 无法使用管理员模式启动胡桃工具箱

> 该问题仅存在于 Windows 10 低于 22H2 的版本中

- 当用户系统版本低于 `Windows Build 19045`（即 `Windows 10 22H2` 版本）时，可能无法通过管理员模式启动胡桃工具箱
  - 该问题属于 Windows 内核级别问题，难以判断具体来源，故建议用户升级至 Windows 10 最新版本

### 如何通过网络代理使用胡桃工具箱

> Snap Hutao 有着良好的云端网络结构，在全球各地你都能获得良好的网络服务

推荐启用 `Loopback 网络`，详细教程见 [此处](loopback.md)