---
headerDepth: 2
category: [功能, 教程]
tag: [祈愿导出, 抽卡, 祈愿]
order: 5
comment: false
description: 祈愿导出功能允许玩家自由地将游戏账号上当前的祈愿数据导出并永久性在本地储存并备份，通过长久的数据积累进行数据追踪和祈愿数据分析。
---

# 祈愿记录

抽卡是原神的核心玩法之一，无论是出于纪念、炫耀的目的还是认真规划抽取计划，对历史抽卡进行统计分析都是非常重要的。
但是原神官方只为玩家提供了半年的抽卡记录，这是很不友好的（~~但是他们还是统计了你一整年杀了多少提米的鸽子~~）。

因此，我们需要利用这半年的抽卡记录调取窗口，将抽卡记录转移到我们自己手中，这就是胡桃工具箱中祈愿记录导出功能的目的所在。

有关原神祈愿记录导出的技术原理，你可以参阅我们的[**祈愿系统与导出原理**](../advanced/Gacha-system-and-export-principal.html)一文。

![祈愿导出](https://img.alicdn.com/imgextra/i2/1797064093/O1CN01otuXYg1g6e0wnNwX2_!!1797064093.png_.webp)

如上图所示，从胡桃工具箱的祈愿导出功能，你可以清晰地获取到包括：**抽卡总数、当前已垫抽数、不同稀有度获取的数量和百分比、每次五星稀有度获取的抽数以及保底情况**。

**胡桃云用户可以额外地获取由云端服务器计算的抽卡预测数据。**

::: note 原神抽卡记录的延迟性
胡桃工具箱获取抽卡记录的来源也为米哈游服务器，因此短时间内刚刚结束的抽卡无法被获取。
当你在游戏内抽卡历史记录中看到了最新的一批抽卡记录，则可以在胡桃中获取统计数据。

:::

## 获取祈愿数据

### SToken 刷新 <Badge text="推荐" type="tip" />

::: info 提示

- 已登录的米游社账号是使用 SToken 刷新方法的前提，你可以参考[米游社多账号切换](mhy-account-switch.md)一文在胡桃工具箱中登录你的账号
- SToken 刷新方法暂不支持国际服
  :::

- 在胡桃工具箱中确保你需要获取记录的米游社帐号已登录
- 从左侧菜单栏进入“祈愿记录”页面
- 点击右上角的“刷新”，并点击“SToken刷新”
- 等待读取完毕，即可查看最新的祈愿记录

### 网页缓存刷新 <Badge text="支持国际服" type="tip" />

- 从左侧菜单栏进入“祈愿记录”
- 启动游戏并登入游戏，打开游戏内的祈愿历史记录
- 回到胡桃工具箱，点击“刷新”按钮，在刷新菜单中点击“网页缓存刷新”

::: tip
若出现“网页缓存刷新”功能异常的情况：

- 点击“设置-储存空间”
- 点击“删除游戏内网页缓存”功能以执行删除操作
- 重新打开原神祈愿记录界面
- 再次刷新祈愿记录
  :::

### 手动输入 URL <Badge text="支持国际服" type="tip" />

- 如果你通过其它工具获取到了你祈愿历史记录的 Url，可以选择“手动输入Url”并根据提示操作，但你应注意此类 Url **具有时效性**

### 全量刷新模式

在默认情况下，胡桃工具箱会在匹配到本地已有记录的祈愿 ID 后停止导入。
但如果你希望完整地获取原神服务器中所有的历史记录（即使它已经存在于你的本地祈愿记录中），你可以勾选“全量刷新”。

**不勾选“全量刷新”不会使你丢失祈愿数据，勾选“全量刷新”也不会让你的本地记录错误地额外记录一次相同的祈愿数据。**

## 导入 UIGF 祈愿数据 <Badge text="UIGF" type="info" />

胡桃工具箱支持导入 `UIGF 数据格式` 的祈愿记录数据[^UIGF-Org]。如果你希望导入这一类数据，可以：

- 从原本的原神工具中导出 UIGF 数据文件
- 点击“设置-祈愿记录-迁移-导入”按钮，在弹出的文件选择器中选择你的 `UIGF Json` 数据文件
- 在弹出的窗口中确认你的导入数据

::: warning
如果你的祈愿记录版本过于老旧，请点击“设置-祈愿记录-迁移-升级较早版本的 UIGF 文件”，再将升级完成后的 UIGF 文件进行导入。

:::

::: tip
如下图所示，在导入时，胡桃仅允许“补全”而不允许“通过备份文件更新至最新”。如果你的抽卡记录包含最新数据，请先同步一次抽卡数据再导入。

![祈愿导入原理](/images/202404/wish_import_zh-tw.webp)

:::

## 导出 UIGF 祈愿数据 <Badge text="UIGF" type="info" />

胡桃工具箱支持导出 `UIGF数据格式` 的 Json 文件格式的祈愿记录数据

如果你希望导出祈愿数据，可以：

- 启动胡桃工具箱，从左侧菜单栏进入“设置”
- 依次找到“祈愿记录-迁移”
- 点击“导出”按钮即可
- 在弹出的界面选择您需要将此导出的祈愿记录数据文件存放的位置，并点击“导出”

::: tip
祈愿记录现已支持导出多个账号的数据到一个文件中，无须分别操作。

:::

## 祈愿记录云同步

> 祈愿记录云同步功能基于胡桃云账号，你需要[在设置中注册并登录胡桃账号](hutao-settings.md#胡桃账号)以使用该功能

用户可以使用该功能，将本地的祈愿记录上传到胡桃云，避免珍贵的祈愿记录丢失，方便数据在多设备之间转移。

### 云同步权限

### 上传

- 在“祈愿记录”界面，选择你需要同步的祈愿存档
- 点击右上角的“胡桃云”按钮
- 点击“上传当前的祈愿存档”即可备份当前的存档数据至云端

### 下载

- 在“祈愿记录”界面，点击右上角的“胡桃云”按钮
- 在对应 UID 的账号右侧点击下载按钮即可下载目标存档的云端数据至本地

### 删除

- 在祈愿导出界面，点击右上角的“胡桃云”按钮
- 在对应 UID 的账号右侧点击删除按钮即可删除目标存档的云端数据

[^UIGF-Org]: 统一标准化的原神数据格式由 [UIGF-Org](https://uigf.org/) 提供