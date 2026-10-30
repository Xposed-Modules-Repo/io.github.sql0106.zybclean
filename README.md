# zybclean

作业帮（`com.zuoyebang.knowledge`）净化模块，适配 14.34.0 (1738)。

- 去广告：拦截广告聚合层 `com.fastad` 的加载与展示，屏蔽开屏 / 激励视频等广告页
- 去首页信息流与「科普专区」，隐藏首页搜索框、通知铃铛、红点角标与绑定账号推广卡
- 屏蔽 AI 解题页，注入 JS 隐藏结果页 H5 里的 AI 解题 tab 与「讲解中」浮窗
- 开屏提速

不重打包原 APK，不收集任何数据。

源码、详细说明与反馈：https://github.com/SQL0106/zuoyebang_xposed

代码由 LLM 在人工指导下生成，未经逐行安全审计，MIT 许可，按现状提供。
