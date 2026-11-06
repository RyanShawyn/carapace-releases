# Carapace Releases

Carapace（macOS 菜单栏持仓应用）的安装包与自动更新源。源码在私有仓库 `RyanShawyn/carapace`。

- 下载最新版：https://github.com/RyanShawyn/carapace-releases/releases/latest
- 应用内自动更新读取本仓库的 latest Release；安装包附带 SHA-256。
- 安装包为 ad-hoc 签名，首次打开需右键 → 打开，或执行 `xattr -dr com.apple.quarantine /Applications/Carapace.app`。

App 只替换自身，数据库和设置在 `~/Library/Application Support/Carapace`，不会随更新覆盖。