---
comment: false
externalLinkIcon: false
index: false
banner: https://opengraph.snapgenshin.cn/generate?url=https://hut.ao/en/statements/update-log.html
sidebar: false
navbar: false
footer: false
copyright: false
editLink: false
breadcrumbExclude: true
breadcrumb: false
lastUpdated: false
contributors: false
backToTop: false
pageInfo: false
---

# 🎉 已成功更新至 1.13.0 版本

**简体中文** | [English](/en/statements/latest.html)

- **【🎉新增】** 更换了程序图标 - 宿雪桃红
- **【🎉新增】** 新增日历服务器时区设置，可以调整主页日历卡片使用的时区
- **【🎉新增】** 标题栏新增元数据加载指示器
- **【🎉新增】** 新增胡桃通行证页面，同时移除了设置页面中的胡桃通行证部分
  * 新增重置邮箱功能
  * 新增刷新用户信息功能
  * 集成兑换码兑换功能
- **【🎉新增】** 引导界面新增了静态图片文件下载提示
- **【🎉新增】** 用户面板米游社扫码登录功能回归
- **【✨优化】** 胡桃通行证的修改密码/注销账号现在会默认为当前登录账号
- **【✨优化】** 胡桃通行证的祈愿记录云服务与 CDN 云服务在未获得时长时不再显示为 1970 年
- **【✨优化】** 在网络请求异常时显示 DNS 信息
- **【✨优化】** 调整了胡桃通知的显示方式，现在无法手动关闭严重（红色）/重要（黄色）类型的通知
- **【✨优化】** 紧凑网页窗口新增加载指示器/刷新按钮
- **【✨优化】** 优化了频繁改变窗口尺寸可能会导致应用内容闪烁的问题
- **【✨优化】** 启动游戏功能现在会正确的提示空路径
- **【✨优化】** 启动游戏功能现在会正确的禁用选择游戏路径按钮
- **【✨优化】** 现在在使用不支持的自定义背景图片时会产生更好的崩溃弹窗 [#2335](https://github.com/DGP-Studio/Snap.Hutao/issues/2335)
- **【✨优化】** 启动游戏功能游戏文件管理弹出的新窗口现在会保持与主窗口相同的主题风格
- **【✨优化】** 启动游戏功能游戏文件管理现在支持中断后恢复安装
- **【✨优化】** 启动游戏功能游戏文件管理现在会额外计算 1 GB 的安装缓存
- **【✨优化】** 启动游戏功能游戏文件管理现在会在安装时动态清理不需要的文件
- **【✨优化】** 启动游戏功能游戏文件管理现在会正确跳过已完成更新的文件
- **【✨优化】** 引导界面现在在选择语言后不再自动前往下一步
- **【✨优化】** 应用内错误提示现在可以复制文本了
- **【✨优化】** 调整了我的角色页面圣遗物主词条的显示效果，以便与副词条进行区分
- **【✨优化】** 我的角色界面在搜索无结果后会显示默认提示了
- **【✨优化】** 调整了祈愿记录页面中胡桃云功能的 UI
- **【✨优化】** 现在自动查找游戏路径时会判断可执行文件是否存在
- **【✨优化】** 养成计划页面材料统计页签树脂预估功能现在会记忆选择的世界等级
- **【✨优化】** 养成计划页面养成物品现在会分行展示天赋等级
- **【🔨修复】** 修复了部分设备在未使用快捷连点功能时也能通过某些按键触发的问题 [#2296](https://github.com/DGP-Studio/Snap.Hutao/issues/2296)
- **【🔨修复】** 修复了缩放比较高的设备在窗口较小时会崩溃的问题 [#2349](https://github.com/DGP-Studio/Snap.Hutao/issues/2290)
- **【🔨修复】** 修复了部分设备删除养成物品可能会导致崩溃的问题 [#2290](https://github.com/DGP-Studio/Snap.Hutao/issues/2290)
- **【🔨修复】** 修复了已经处于成就页面时由其他应用启动导入成就不会显示导入弹窗的问题 [#2306](https://github.com/DGP-Studio/Snap.Hutao/issues/2306)
- **【🔨修复】** 修复了特定情况下会尝试打开多个对话框的问题 [#2307](https://github.com/DGP-Studio/Snap.Hutao/issues/2307)
- **【🔨修复】** 修复了预下载可用时无法更改游戏路径的问题 [#2317](https://github.com/DGP-Studio/Snap.Hutao/issues/2317)
- **【🔨修复】** 修复了部分设备无法正确枚举容器应用从而导致崩溃的问题 [#2339](https://github.com/DGP-Studio/Snap.Hutao/issues/2339)
- **【🔨修复】** 修复了我的角色页面中达达利亚的天赋对普通攻击技能等级加成不显示的问题
- **【🔨修复】** 修复了在我的角色页面添加到养成计划时，弹出的提示数量不正确的问题
- **【🔨修复】** 修复了幻想真境剧诗页面上场率统计没有垂直居中的问题
- **【🔨修复】** 修复了 Cookie 失效后直接重新登录后仍然会显示网络异常的问题
- **【🔨修复】** 修复了连点功能启用时关闭连点功能开关没有停止连点的问题
- **【🔨修复】** 修复了我的角色页面网格视图下角色名片背景没有垂直居中的问题
- **【🔨修复】** 修复了我的角色/角色资料/武器资料中搜索框的待选提示中部分图标显示不完整的问题
- **【🔨修复】** 修复了特定情况下窗口尺寸可能初始化为不正确的大小的问题
- **【🔨修复】** 修复了祈愿记录页面计时页签中卡池尚未开始也会被计入的问题
- **【🔨修复】** 修复了实时便笺不会正确发送通知的问题
- **【🔨修复】** 修复了部分缩放率下实时便笺的角色探索部分可能会布局异常的问题
- **【🔨修复】** 修复了注销胡桃通行证失败时仍然会退出登录的问题
