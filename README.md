# 中国官方调休日历

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

中国官方节假日和调休日历，提供 iCal 格式文件，支持 Google Calendar、Outlook、Apple Calendar 等日历应用订阅。

## ✨ 功能特点

- 📱 支持多种日历应用（Google Calendar、Outlook、Apple Calendar、Thunderbird 等）
- 🔄 及时同步官方假期安排
- 📅 包含节假日、调休日期、补班日期等完整信息
- 🌍 iCal 标准格式，兼容性强
- 🔗 直接订阅链接，即插即用

## 🚀 快速开始

### Google Calendar 订阅

1. 打开 [Google Calendar](https://calendar.google.com)
2. 左侧栏找到"其他日历"，点击 **+** 按钮
3. 选择 **从网址订阅**
4. 输入订阅链接：
   ```
   https://raw.githubusercontent.com/ifzyu/china-holidays-ical/main/calendars/cn-holidays-current.ics
   ```
5. 点击 **订阅**，日历会自动添加到您的日历列表

### Outlook / Office 365 订阅

1. 打开 Outlook 网页版或客户端
2. 点击 **添加日历**
3. 选择 **从网址订阅**
4. 粘贴上述链接
5. 确认订阅

### Apple Calendar (macOS / iOS)

1. 在 Calendar 应用中，选择 **文件** > **新建日历订阅**
2. 输入上述链接
3. 点击 **订阅**

### Thunderbird

1. 打开 Thunderbird，切换到日历视图
2. 右击左侧日历列表，选择 **新建日历**
3. 选择 **在网络上**
4. 输入链接并完成配置

## 📋 文件说明

| 文件 | 说明 |
|------|------|
| `cn-holidays-current.ics` | 当前年份完整节假日日历 |
| `cn-holidays-2025.ics` | 2025年节假日安排 |
| `cn-holidays-2026.ics` | 2026年节假日安排 |

## 📅 包含的信息

每个 iCal 文件包含：
- ✅ 国家法定节假日（春节、清明、端午、中秋、国庆等）
- ✅ 调休日期（周末补班日）
- ✅ 官方公布的放假安排
- 📝 完整的事件描述和提醒

## 🔄 更新周期

- 通常在每年年初更新
- 遵循国务院官方发布的节假日安排
- 重大调整会立即更新

## 📚 日期参考

### 2025年节假日

| 节假日 | 放假时间 | 调休补班 |
| 元旦 | 1月1日（周三）| 无 |
| 春节 | 1月28日（除夕、周二）-2月4日（周二） | 1月26日（周日）、2月8日（周六）补班 |
| 清明节 | 4月4日（周五）-4月6日（周日） | 无 |
| 劳动节 | 5月1日（周四）-5月5日（周一） | 4月27日（周日）补班 |
| 端午节 | 5月31日（周六）-6月2日（周一） | 无 |
| 国庆节、中秋节 | 10月1日（周三）-10月8日（周三） | 9月28日（周日）、10月11日（周六）补班 |

## 🔗 直接订阅链接

根据您的需求选择相应的链接：

```
当前年份：https://raw.githubusercontent.com/ifzyu/china-holidays-ical/main/calendars/cn-holidays-current.ics
2025年：  https://raw.githubusercontent.com/ifzyu/china-holidays-ical/main/calendars/cn-holidays-2025.ics
2026年：  https://raw.githubusercontent.com/ifzyu/china-holidays-ical/main/calendars/cn-holidays-2026.ics
```

## ⚙️ 技术细节

- **格式**: iCalendar (RFC 5545 标准)
- **编码**: UTF-8
- **时区**: Asia/Shanghai (UTC+8)
- **刷新频率**: 建议日历应用设置为每天刷新一次

## 📝 数据来源

- [国务院官网](http://www.gov.cn/) - 年度节假日放假安排
- [国务院办公厅](http://www.gov.cn/gongbao/) - 官方公告

## 📄 许可证

MIT License - 自由使用、修改和分发

## 🤝 贡献

如果您发现任何错误或有改进建议，欢迎：
- 提出 Issue
- 提交 Pull Request
- 发送反馈

## 📧 联系方式

- GitHub: [@ifzyu](https://github.com/ifzyu)
- 提交 Issue: [GitHub Issues](https://github.com/ifzyu/china-holidays-ical/issues)

---

⭐ 如果这个项目对您有帮助，请不要吝啬您的 Star！
