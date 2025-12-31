# 🤖 GLaDOS 自动签到 (GitHub Actions 版)

这是一个基于 GitHub Actions 的 GLaDOS 自动签到脚本。
每日定时运行，支持 Telegram 通知，零成本、免服务器。

## 📂 项目结构

为了方便维护和理解，本项目结构如下：

```text
glados-auto-checkin/
├── .github/
│   └── workflows/
│       └── schedule.yml    # ⚙️ 核心配置：设定每天几点运行
├── checkin.py              # 🐍 核心逻辑：签到和发送通知的代码
├── requirements.txt        # 📦 依赖列表：告诉环境需要安装 requests 库
└── README.md               # 📖 说明文档：即你现在看到的这份说明

