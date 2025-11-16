---
layout: default
title: Disciplinio - Support & Documentation
---

# Disciplinio

![Disciplinio](https://img.shields.io/badge/version-1.0.0-blue)
![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20macOS-lightgrey)
![Swift](https://img.shields.io/badge/Swift-5.9-orange)

**A task management app designed to help you stay disciplined and focused on your deadlines.**

Created by [mookdel.dev](https://mookdel.dev)

---

## Features

### ⏰ Deadline Tracking
Color-coded urgency alerts help you prioritize tasks with approaching deadlines.
- 🔴 Red: Less than 5 minutes remaining
- 🟠 Orange: Less than 1 hour remaining
- ⚪ Default: More than 1 hour remaining

### 📊 Task Organization
View your backlog and history with tasks grouped by date for easy management.

### ✅ Completion Tracking
Track your progress with detailed completion statistics and time invested.

### ⚡ Quick Actions
Swipe gestures make it easy to complete, delete, or manage tasks on the go.

### 💾 Local Storage
Your data stays on your device with SwiftData, ensuring privacy and offline access.

### 🎨 Native Design
Beautiful, native SwiftUI interface that feels right at home on iOS and macOS.

---

## How to Use

### Creating a Task
1. Tap the **+** button in the Backlog tab
2. Enter a task title
3. Set the estimated duration using the slider
4. Choose your deadline timeframe (from/to dates)
5. Tap **Create**

### Managing Tasks
- **Complete a task**: Swipe left on a task in the Backlog tab, tap the green checkmark
- **Delete a task**: Swipe right, tap the delete button
- **Undo completion**: Go to History tab, swipe right, tap the orange button to reopen

### Viewing Statistics
Navigate to the **Settings** tab to see:
- Total tasks count
- Completion rate
- Time invested
- Average task duration
- And more!

---

## Frequently Asked Questions

### What do the different colors mean?
Task colors indicate urgency:
- **Red** means less than 5 minutes remaining
- **Orange** means less than 1 hour remaining
- **Default color** means more than 1 hour until the deadline

### Can I undo a completed task?
Yes! Go to the History tab, swipe right on the completed task, and tap the orange button to reopen it. The task will return to your backlog.

### Is my data synced across devices?
Currently, Disciplinio stores all data locally on your device using SwiftData. Cloud sync is not available in version 1.0.0, but may be added in future updates.

### How do I delete all my data?
Go to **Settings → Data Management** and choose to delete either all completed tasks or all tasks. This action cannot be undone, so use with caution.

### What platforms are supported?
Disciplinio is built with SwiftUI and runs natively on iOS and macOS devices.

---

## Privacy

### Your Data, Your Device

Disciplinio takes your privacy seriously. All your tasks and data are stored locally on your device using SwiftData. We don't collect, transmit, or store any of your personal information on external servers. Your task data never leaves your device, ensuring complete privacy and security.

[Read Full Privacy Policy →]({{ site.baseurl }}/disciplinio/privacy-policy)

---

## Technical Details

- **Framework**: SwiftUI
- **Data Persistence**: SwiftData
- **Minimum iOS Version**: iOS 17.0+
- **Minimum macOS Version**: macOS 14.0+
- **Architecture**: MVVM

---

## Screenshots

*(Screenshots coming soon)*

---

## Support

Have questions or feedback? We'd love to hear from you!

**Contact**: [mookdel.dev](https://mookdel.dev)

---

## Version History

### Version 1.0.0 (November 2025)
- Initial release
- Backlog and History views
- Task creation with deadline tracking
- Color-coded urgency alerts
- Swipe actions for task management
- Statistics and analytics
- Local data storage with SwiftData

---

## License

Copyright © 2025 [mookdel.dev](https://mookdel.dev). All rights reserved.

---

**Made with ❤️ by [mookdel.dev](https://mookdel.dev)**
