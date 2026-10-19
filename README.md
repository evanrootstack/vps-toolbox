# vps-toolbox
VPS 运维常用 Linux 命令、3X-UI 面板管理与 VPS 测试脚本合集，持续更新.
> 记录 VPS 日常运维中常用的 Linux 命令、3X-UI 面板管理命令，以及好用的 VPS 测试脚本。想到一条就加一条，慢慢完善。

## 目录

- [一、VPS 常用 Linux 命令](#一vps-常用-linux-命令)
- [系统信息](#系统信息)
- [磁盘与内存](#磁盘与内存)
- [网络](#网络)
- [文件与权限](#文件与权限)
- [防火墙 UFW](#防火墙-ufw)
- [服务管理](#服务管理)
- [二、3X-UI 面板](#二3x-ui-面板)
- [三、VPS 测试脚本](#三vps-测试脚本)
- [更新日志](#更新日志)

---

## 一、VPS 常用 Linux 命令

### 系统信息

查看系统版本：
```bash
cat /etc/os-release
```
查看内核版本：
````bash
uname -r
````
### 磁盘与内存

查看磁盘占用：

```bash
df -h
```

查看内存占用：

```bash
free -h
```

### 网络

<!-- TODO: ping、curl、ss、ip addr 等常用命令 -->

### 文件与权限

<!-- TODO: ls、chmod、chown、tar 解压打包等 -->

### 防火墙 UFW

<!-- TODO: ufw allow / ufw status / ufw enable 等 -->

### 服务管理

<!-- TODO: systemctl status / start / restart / enable 等 -->

---

## 二、3X-UI 面板

<!-- TODO: 安装 / 更新 / 卸载 / 查看面板信息等命令 -->

官方仓库：<https://github.com/MHSanaei/3x-ui>

---

## 三、VPS 测试脚本

作者 [xykt](https://github.com/xykt) 的 XY 系列脚本：

| 脚本 | 用途 | 一键运行 |
| --- | --- | --- |
| IPQuality | IP 质量检测（流媒体解锁、风险评分、黑名单） | `bash <(curl -Ls https://IP.Check.Place) -I` |
| NetQuality | 网络质量检测 | `bash <(curl -Ls https://Check.Place) -N` |
| HardwareQuality | 硬件质量检测 | <!-- TODO --> |
| ScriptMenu | XY 系列脚本交互菜单 | <!-- TODO --> |

---

## 更新日志

- 2026-10-19：建仓，先搭架子，后续慢慢填
