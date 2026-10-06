# 双人射箭对决 (Twoplayersarchery)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

用 AI 辅助编程制作的 C++ 控制台双人对战游戏。两名玩家在带有墙壁障碍物的地图中移动，互相射箭，先将对方 HP 降至 0 即为胜利。

![screenshot](https://raw.githubusercontent.com/Sunset10086/Twoplayersarchery/main/screenshot.png)

## 游戏玩法

- 两名玩家在布满墙壁的地图中对战
- 每箭命中造成 **40 HP** 伤害
- 默认 HP 为 **100**（可在设置中调整）
- 射击冷却时间默认 **300ms**（可调整）
- 墙壁阻挡移动和箭矢，玩家不能站在同一格
- 按 **Esc** 暂停游戏

## 操作说明

| 功能 | 玩家 1 | 玩家 2 |
|------|--------|--------|
| 移动 | W A S D | ↑ ← ↓ → |
| 射击（上） | I | 8 |
| 射击（左） | J | 4 |
| 射击（下） | K | 5 |
| 射击（右） | L | 6 |

## 编译与运行

### 系统要求

- Windows 操作系统
- 支持中文显示的终端

### 使用 MSVC 编译

```bash
cl /EHsc /Fe:双人射箭对决.exe 双人射箭对决.cpp
```

### 使用 MinGW/GCC 编译

```bash
g++ -o 双人射箭对决.exe 双人射箭对决.cpp -std=c++11
```

## 项目结构

```
Twoplayersarchery/
├── README.md              # 本文件
├── LICENSE                # MIT 许可证
├── .gitignore             # Git 忽略规则
└── 双人射箭对决.cpp        # 游戏源码
```

## 开发背景

作者（东风九号）在 2017 年初中时期制作了一个贪吃蛇 MOD，本项目是其升级版本，于 2026 年 6 月使用 AI 辅助编程重新构建。

## 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件
# Twoplayersarchery
用ai辅助编程做的C++控制台双人小游戏，两人互相射箭，击败对方为胜。算是我以前一个项目的升级版。使用ai辅助编程
<img width="699" height="580" alt="QQ截图20260629123417" src="https://github.com/user-attachments/assets/51600ebb-92a0-41d8-98a4-edc1ae19ea3f" />
