# Brains School Weekly Briefing 中文家长版

每周自动整理 Brains International School 的 *Briefing Semanal* 通知，给中国家长用：
中文翻译 + 关键时间点 + 家长行动清单 + 可一键导入手机的日历文件。

📄 **本周浏览**：https://hola-1129.github.io/brains-school-briefing/

## 内容

| 文件 | 用途 |
|---|---|
| `index.html` | 中文家长版主页 |
| `school_events.ics` | 本周全部活动；点击导入手机日历 |
| `events/*.ics` | 每个活动单独的日历文件 |
| `weekly_briefing_cn.md` | 完整 markdown 详版 |
| `weekly_briefing_summary.txt` | 微信群转发版（短） |
| `extracted_links.json` | 主 PDF 抽到的所有链接和处理状态 |
| `processing_log.txt` | 自动化处理日志 |
| `archive/<YYYY-Www>/` | 历史周次归档 |

## 怎么用

iOS 用户：用 Safari 打开主页 → 点 "📅 一键添加本周全部日历" → 出现"加入日历"对话框 → 全部添加。

Android 用户：浏览器会下载 `.ics` 文件 → 用日历 app 打开导入。

## 维护

每周由 `school_helper` agent 自动生成、push 到本仓库。代码不在这里，只发布产物。

## 隐私

- 仓库公开，但只发布学校官方下发的通知翻译，不含家庭隐私
- API key、本地路径等敏感信息均不会进入产物
