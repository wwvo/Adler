# Adler Scoop Bucket

[![Tests](https://github.com/wwvo/Adler/actions/workflows/ci.yml/badge.svg)](https://github.com/wwvo/Adler/actions/workflows/ci.yml) [![Excavator](https://github.com/wwvo/Adler/actions/workflows/excavator.yml/badge.svg)](https://github.com/wwvo/Adler/actions/workflows/excavator.yml)

个人 [Scoop](https://scoop.sh) Bucket，收录官方仓库未收录的 Rust 开发工具。

## 包含的工具

| 工具                                                     | 描述                   | 上游仓库                                                              |
| -------------------------------------------------------- | ---------------------- | --------------------------------------------------------------------- |
| [cargo-nextest](https://nexte.st)                        | 下一代 Rust 测试运行器 | [nextest-rs/nextest](https://github.com/nextest-rs/nextest)           |
| [cargo-machete](https://github.com/bnjbvr/cargo-machete) | 检测未使用的 Rust 依赖 | [bnjbvr/cargo-machete](https://github.com/bnjbvr/cargo-machete)       |
| [release-plz](https://release-plz.dev)                   | 自动化 Rust crate 发布 | [release-plz/release-plz](https://github.com/release-plz/release-plz) |

## 使用方法

```pwsh
# 添加 bucket
scoop bucket add adler https://github.com/wwvo/Adler

# 安装工具
scoop install adler/cargo-nextest
scoop install adler/cargo-machete
scoop install adler/release-plz

# 更新工具
scoop update cargo-nextest cargo-machete release-plz
```

## 贡献

欢迎提交 Issue 或 Pull Request。新增 manifest 请参考 [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests) 文档。
