<div align="center">

# 李宏杰

### 用代码解决实际问题，持续构建实用的开源工具

主要使用 **Rust** 和 **Go**，关注文档自动化、数据处理与开发者工具。

[![GitHub](https://img.shields.io/badge/GitHub-lihongjie0209-181717?logo=github)](https://github.com/lihongjie0209)
[![Rust](https://img.shields.io/badge/Rust-工具开发-000000?logo=rust)](https://www.rust-lang.org/)
[![Go](https://img.shields.io/badge/Go-服务与CLI-00ADD8?logo=go)](https://go.dev/)

</div>

## 项目

### 文档自动化

#### [📄 docx-jsx](https://github.com/lihongjie0209/docx-jsx)

用 JSX/TSX 描述 Word 文档并编译为 DOCX，也支持将部分 DOCX 逆向为 JSX。

`Rust` · `CLI` · `内嵌 V8` · `docx-rs`

#### [📊 xlsx-jsx](https://github.com/lihongjie0209/xlsx-jsx)

用 JSX/TSX 描述 Excel 工作簿并构建 XLSX，也支持将部分工作簿逆向为 JSX。

`Rust` · `CLI` · `内嵌 V8`

### 运维工具

#### [🧽 server-sponge](https://github.com/lihongjie0209/server-sponge)

面向 Linux 的动态资源占位与自动避险工具，可按目标动态调节内存和 CPU 占用，用于压测模拟、资源预留与混部环境验证。提供实时 Web 监控面板、压力模拟控制，并支持安装为 systemd 服务。

`Rust` · `Linux` · `PID 控制` · `PSI` · `systemd`

#### [🪟 nssm-rs](https://github.com/lihongjie0209/nssm-rs)

用 Rust 实现的 Windows 服务管理 CLI，可安装、配置和控制服务，并监督服务进程、管理日志。

`Rust` · `Windows` · `CLI` · `Windows 服务`

## 关注方向

- **文档即代码**：让 Office 文档可以版本管理、复用和自动生成。
- **可靠的双向转换**：明确保留能力边界，避免静默丢失内容与格式。
- **面向 Agent 的 CLI**：提供机器可读规范、校验诊断和可执行的修复建议。

欢迎通过项目仓库的 Issue 和 Pull Request 交流与贡献。
