# Everest

这里是一个个人自用分支, 包含一些更改(下列描述可能会过期, 不保证完全匹配分支状态):

- 添加环境变量 `EVEREST_PATH_EVEREST`, `PathEverest` 会优先读取它, 这使得可以用同一个游戏来加载位于不同位置的 `Mods` 文件夹
- 回退了 `piton-apphost` 的更改, 让 `EverestSplash`, `MiniInstaller` 依然使用 `apphost`, 没什么原因, 只是单纯个人不喜欢
- 合并了 [`nested-options` #1057](https://github.com/EverestAPI/Everest/pull/1057), 这是让选项页面更好浏览的一个改进, 但是相关 pr 没有任何推进