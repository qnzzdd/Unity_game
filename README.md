# Godot Game Project

## 项目简介
本项目是由我们四名学生团队在业余时间共同完成的 Godot 游戏开发练习。
项目旨在提升我们的游戏开发能力、编程实践经验，以及团队协作能力。

当前项目类型为：**俯视角动作类 Rogue 游戏（Top-down Action Roguelike）**
平台支持：Windows

---

## 技术栈
- 游戏引擎：Godot
- 编程语言：GDScript
- 版本控制：Git + GitHub

---

## 团队成员
- swomHL
- Techyacrs
- Muxa
- （待补充）

---

## 项目结构
```text
project/
├── project.godot      # 项目配置文件（核心文件，请勿删除）
├── scenes/            # 场景文件（.tscn）
├── scripts/           # 脚本文件（.gd）
├── assets/            # 图片、音频等资源
├── ui/                # UI相关资源（可选）
└── docs/              # 项目文档（可选）

---
## 环境配置与运行
1.**Gotdot安装**
   - 前往以下网址进行下载
   - https://docs.godotengine.org/zh-cn/4.x/
   - 所有成员请保持版本一致，避免兼容问题

2.**Gotdot配置**
   -

## 注意事项
1. **Git 安装**  
   - 请先安装 [Git](https://git-scm.com/)  
   - Windows 用户推荐勾选 **“Git from the command line”**  

2. **克隆仓库**  
   - 打开 Git Bash / PowerShell  
   - 输入：
     ```bash
     git clone https://github.com/qnzzdd/Gotdot_game.git
     ```
   - 进入项目文件夹：
     ```bash
     cd Gotdot_game
     ```

3. **提交修改**
   - ***请严格按照协作规范***
   - 修改完成后，依次执行：
     ```bash
     git add .
     git commit -m "简单描述你做的修改"
     git push
     ```

4. **拉取最新代码**  
   - 每次开始工作前，先执行：
     ```bash
     git pull
     ```
   - 保证本地仓库与远程仓库同步

5. **不要上传大文件**  
   - 例如 `Library/`、`Temp/`、`Obj/` 文件夹请不要上传  
   - 仓库已配置 `.gitignore`，请遵守规则

6. **保持提交简洁**  
   - 每次提交只修改或新增相关功能  
   - 提交信息尽量描述清楚修改内容，如：
     ```
     修复角色跳跃逻辑
     添加新道具 Prefab
     ```

---
## Godot 使用注意事项

- `project.godot` 是项目核心文件，请勿删除
- `.import/` 文件夹需要提交（Godot依赖资源导入信息）
- 不同版本 Godot 可能导致项目无法打开，请统一版本
- 场景（.tscn）和脚本（.gd）是核心开发文件

## Git注意事项
- GitHub 仓库主要存放 **项目资源、脚本、场景文件**
- 建议在开发前熟悉 **Git 基本操作**，避免覆盖他人修改
