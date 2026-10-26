# 爽阅 v1.0.5（1.0.5+35）

发布日期：2026-10-26
发布：https://github.com/win818/shuangyuebook/releases/tag/v1.0.5

## 本版提交

- chore: 触发双端构建（阶段1 管道验证） (3d9b510)
- ci: 自动发版工作流（push main 即升版本号/打双端包/建 Release）+ 文档 (743caee)
- fix(site): 官网版本号取 Release tag 与公告里更高的一个 (e78bc0b)
- release(v1.0.4): 版本号定为 1.0.4+12，两版更新内容糅合成一份面向用户的说明 (2e60015)
- release: v1.0.5+11——网络字体按需下载 + 1000 书源与低端机卡顿治理 (f0d0e78)
- perf(app): 1000+ 书源与低端机卡顿治理（列表懒构建 / 后台 isolate / 减少整页重建） (5c5c4aa)
- feat(reader): 网络字体按需下载——不内置字体文件，选中即下载并应用 (0f71682)
- perf(reader): 切下一章不再双发请求——预取与前台共用同一 Future (8cec7f8)
- fix(legado): 非 ASCII 请求头值剔除而非抛异常 (939c74a)
- fix(legado): CSS 兄弟组合子 ~ / + 与 jsoup 伪类共存 (dbf76ad)
- fix(legado): 目录规则三处语义补齐（顺序前缀/字符串条目/被吞掉的补网） (9975028)
- feat(legado): 补齐 java.* 脚本 API（getElements/setContent/字节与交互类成员） (f0bd0f9)
- feat(legado): jsoup 节点树导航（children/parent/兄弟/ownText） (2ad86e3)
- feat(legado): 发现页分类异步补全（脚本内联网的源） (e027785)
- feat(legado): 发现页支持 JS 形态 exploreUrl（含 infoMap 分栏选择器） (abe9480)
- feat(legado): 支持 jsoup 文本伪类 :contains / :containsOwn (1073dc3)
- feat(legado): 打通 WebView 链路（java.webView + 章网址 webView 选项） (11cbe5a)
- fix(legado): Packages.java 加密链路两处致命缺陷 (d1fc6d5)
- feat(legado): createSymmetricCrypto / 字节数组 / 登录态与 book 变量等 JS 桥补齐 (787e860)
- feat(legado): data: URI 本地响应 / source.put-get-remove / source 实体字段注入 (c5f660e)
- feat(cookie): 全局 LegadoCookieJar 替代私有 jar，跨请求/JS 桥共享 Cookie (d283bdc)
- fix(js): 大字符串结果分片取回，修复桥 JS_Eval 8192 上限导致的静默变空 (1aec10e)
- feat(legado): 书源变量持久化 / 请求描述对象 / 单源超时预算 / 内置源清理只跑一次 (6145ad0)
- feat(legado): 位置伪类切段选择 / 字符串上的 jsoup 调用 / 表格片段解析 (662dbfc)
- fix(legado): 孤立代理项导致脚本返回值丢失 + 渲染后选项拆分 (7e4d7a9)
- feat(legado): 请求层与条目上下文对齐 legado——重定向/Referer/重试、java.ajax 返回正文、JSON 串条目 (0016eba)
- feat(legado): 书源脚本执行复刻 P0——Packages 兼容层与 HTTP 响应对象 (a4a1f1a)
- 爽阅 v1.0.3：书源解析与性能大修 + 公告增加网盘备用线路 (7184e26)
- 更新时序改造：下载期间应用保持可用，完成后才退出换装 (795ee98)
- Windows 更新流程重做：独立更新器 updater.exe 后台包办 (cf36581)
- 爽阅 v1.0.2：JS 书源全量可用 + 阅读手感修复 + 音量键翻页 (cab8ef2)
- 网络获取书源：移除失效的大辉狼预设（jsdelivr 被拦 + 16MB），换入 5 条移动网络实测直链（yiove 稳定合集 / Xiu 精品 / 一程 / 破冰 / 关耳女频） (3a53ffe)
- 爽阅 v1.0.1 发布版源码：书源导入浏览器 · 首页实时刷新 · 详情自动换源 · 体检确认制 (3b8ba77)
- 书源引擎全量兼容修复（651 源实测）+ 网络书源获取自动测试 (7f99cb6)
- 爽阅 v1.0.0 发布版源码 (ed04dc1)

> 本文件由 GitHub Actions 自动生成；面向用户的详细更新说明请补充于此，
> 或发布到 docs/announcement.json（官网与 App 公告同源）。
