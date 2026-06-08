# 中国官方调休日历 📅

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

中国官方节假日和调休日历，提供 iCal 格式文件，支持 Google Calendar、Outlook、Apple Calendar 等日历应用订阅。

## ✨ 功能特点

- 📱 支持多种日历应用（Google Calendar、Outlook、Apple Calendar、Thunderbird 等）
- 🔄 自动更新，及时同步官方假期安排
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
| `cn-holidays-2024.ics` | 2024年节假日安排 |
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
|--------|---------|---------|
| 元旦 | 1月1日 (周三) | 无 |
| 春节 | 1月29日-2月6日 | 1月19日、2月8日补班 |
| 清明 | 4月4日-4月6日 | 4月7日补班 |
| 劳动节 | 5月1日-5月5日 | 4月27日、5月10日补班 |
| 端午 | 6月11日 | 6月10日补班 |
| 中秋 | 9月18日 | 9月15日补班 |
| 国庆 | 10月1日-10月7日 | 9月29日、10月11日补班 |

## 🔗 直接订阅链接

根据您的需求选择相应的链接：

```
当前年份：https://raw.githubusercontent.com/ifzyu/china-holidays-ical/main/calendars/cn-holidays-current.ics
2024年：  https://raw.githubusercontent.com/ifzyu/china-holidays-ical/main/calendars/cn-holidays-2024.ics
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

## 🙏 常见问题

**Q: 为什么订阅后没有显示日历？**
A: 请确保：
- 链接输入正确
- 网络连接正常
- 日历应用允许添加外部日历
- 尝试手动刷新或重启应用

**Q: 如何更新已订阅的日历？**
A: 大多数日历应用会自动刷新。您也可以手动刷新或删除后重新订阅。

**Q: 可以离线使用吗？**
A: 可以。下载 `.ics` 文件后导入到您的日历应用即可。

**Q: 支持其他国家/地区的假期吗？**
A: 目前仅提供中国大陆的官方假期安排。

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
