# DSH-Go Huawei DroiTong Patch Build

> Unofficial build of DSH Go, based on upstream v1.0.16.
> Fixes local engine startup failures under HarmonyOS inside DroiTong container, including issues with PRoot initialization, `getcwd` anomalies and `clone3` thread creation.

## 中文说明
这是基于上游 DSH Go 1.0.16 的非官方修复构建版本。
专门针对 HarmonyOS + 卓易通（DroiTong）容器环境，修复本机引擎启动相关问题：
- PRoot 初始化启动失败
- `getcwd` 路径获取异常
- `clone3` 线程创建报错

📦 **下载**：前往 [Releases](../../releases) 获取最新构建包。

---

## English
This is an unofficial patched build based on upstream DSH Go v1.0.16.
It targets the HarmonyOS + DroiTong container environment and resolves local engine startup problems:
- PRoot initialization failure
- `getcwd` abnormal behavior
- `clone3` thread creation errors

📦 **Download**: Get the latest artifacts from [Releases](../../releases).
