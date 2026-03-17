# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## 已安装技能

| 技能 | 状态 | 功能 |
|------|------|------|
| feishu-doc | ✅ ready | 飞书文档读写 |
| feishu-drive | ✅ ready | 飞书云盘 |
| feishu-perm | ✅ ready | 飞书权限管理 |
| feishu-wiki | ✅ ready | 飞书wiki |
| coding-agent | ✅ ready | 编程代理 |
| healthcheck | ✅ ready | 安全检查 |
| node-connect | ✅ ready | 节点连接诊断 |
| skill-creator | ✅ ready | 创建技能 |
| skill-vetter | ✅ ready | 安全扫描 |
| weather | ✅ ready | 天气查询 |
| self-improving | ✅ ready | 自我学习 |
| proactivity | ✅ ready | 主动做事 |
| github-cli | ✅ ready | GitHub操作 |
| gh | ✅ | GitHub CLI (系统命令) |

## 待安装技能

| 技能 | 功能 | 备注 |
|------|------|------|
| xiaohongshu-mcp | 小红书自动化 | 需要装 |
| qmd | 本地文档搜索 | 需要 sudo npm install -g @tobilu/qmd |
| bb-browser | 浏览器自动化 | 需要装 |

## 常用命令

```bash
# 重启 Gateway
openclaw gateway restart

# 查看技能状态
openclaw skills list

# 安装技能
npx clawhub install <skill-name>

# 搜索技能
npx clawhub search <keyword>
```

## Cameras

- living-room → Main area, 180° wide angle
- front-door → Entrance, motion-triggered

## SSH

- home-server → 192.168.1.100, user: admin

## TTS

- Preferred voice: "Nova" (warm, slightly British)
- Default speaker: Kitchen HomePod
