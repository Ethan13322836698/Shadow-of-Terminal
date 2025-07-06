---
# Shadow of Terminal

极度拟真的黑客模拟游戏  
A hyper-realistic hacking simulation game

---

## 简介 | Introduction

**Shadow of Terminal** 是一款以真实渗透测试技术为核心的命令行黑客游戏。  
游戏中的所有命令均为真实世界可执行命令，工具名称与语法无任何魔改或虚构。

Shadow of Terminal is a command-line based hacking game that emphasizes realism.  
Every command and tool used in the game reflects real-world penetration testing practices.

---

## 核心特色 | Core Features

- 真实命令：如 `nmap -sV`、`sudo apt install`、`hydra` 等，均为原样使用
- 真实工具：内置类 Unix/Linux 环境，模拟 apt、nmap、hydra、msf 等行为
- 拟真流程：信息收集 → 漏洞扫描 → 利用 → 提权 → 数据渗透
- 命令行交互：无图形化，仅终端操作，要求玩家具备一定技术水平
- 可用于训练：适合作为学习网络安全或实训辅助平台

- Real-world syntax: Commands like `nmap -sV`, `sudo apt install`, and `hydra` are used as-is
- Realistic tools: Simulated Linux environment with behavior mimicking actual security utilities
- Authentic attack flow: Reconnaissance → Scanning → Exploitation → Privilege Escalation → Data Exfiltration
- CLI only: No GUI, fully terminal-driven gameplay for advanced users
- Training value: Usable as an educational or practical cyber range platform

---

## 示例命令 | Example Commands

sudo apt update && sudo apt install nikto
nmap -sV 192.168.0.0/24
hydra -l root -P rockyou.txt ssh://192.168.0.100
````

---

## 当前状态 | Project Status

开发中，以下功能已实现：

* 自定义终端解释器
* 真实命令模拟执行
* 网络环境模拟（主机发现、端口扫描）
* 简单软件安装系统（APT 仿真）

In development. Currently implemented:

* Custom terminal interpreter
* Simulated execution of real commands
* Virtual network with host/port emulation
* Basic software installation via fake APT

---

## 未来计划 | Roadmap

* 加入 Metasploit 框架仿真
* 增加漏洞库与 CVE 模拟
* 多用户虚拟靶场支持
* 戏剧性剧情模式与任务系统

Planned features:

* Simulated Metasploit framework
* Vulnerability database with CVE emulation
* Virtual multi-user training environment
* Story mode and mission engine

---

## 运行要求 | Requirements

* Linux / macOS /Windows 推荐
* Python 3.10+

* 终端分辨率建议：80x24 或以上

* Recommended: Linux / macOS / Windows

* Python 3.10+

* Suggested terminal resolution: 80x24 or above

---
