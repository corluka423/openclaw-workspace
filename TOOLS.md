# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## 技能分类目录

~/.openclaw/workspace/skills/
- ai/ - AI/编程相关
- productivity/ - 效率工具
- security/ - 安全工具
- memory/ - 记忆学习
- social/ - 社交媒体

## 已安装技能

| 技能 | 分类 | 功能 |
|------|------|------|
| feishu-doc | (飞书内置) | 飞书文档读写 |
| feishu-drive | (飞书内置) | 飞书云盘 |
| feishu-perm | (飞书内置) | 飞书权限管理 |
| feishu-wiki | (飞书内置) | 飞书wiki |
| coding-agent | ai/ | 编程代理 |
| github-cli | ai/ | GitHub操作 |
| healthcheck | security/ | 安全检查 |
| node-connect | security/ | 节点连接诊断 |
| skill-creator | productivity/ | 创建技能 |
| skill-vetter | security/ | 安全扫描 |
| weather | (通用) | 天气查询 |
| self-improving | memory/ | 自我学习 |
| proactivity | productivity/ | 主动做事 |

## 系统工具

| 工具 | 位置 | 功能 |
|------|------|------|
| gh | /opt/homebrew/bin/ | GitHub CLI |
| openclaw | /usr/local/bin/ | OpenClaw核心 |

## 待安装技能

| 技能 | 分类 | 功能 |
|------|------|------|
| xiaohongshu-mcp | social/ | 小红书自动化 |
| qmd | ai/ | 本地文档搜索 |
| bb-browser | ai/ | 浏览器自动化 |

## 常用命令

```bash
# 重启 Gateway
openclaw gateway restart

# 查看技能状态
openclaw skills list

# 安装技能到指定分类
npx clawhub install <skill-name>

# 搜索技能
npx clawhub search <keyword>
```
