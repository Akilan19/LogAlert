# 🛎️ LogAlert

Are you tired of digging through the inspect element console to find your precious log messages? Say hello to **NotifyLog.js** – the JavaScript library that brings your logs right to your screen thru notifications!

NPM link: https://www.npmjs.com/package/notif_log

## 🚀 What is notif_log.js?

notif_log.js is a JavaScript library that replaces those boring old and tedious process of checking the `console.log` messages on broswer with eye-catching notifications.

## 😃 Features

- **Instant Notifications**: Get your log messages as browser notifications in real-time.
- **Easy to Use**: A simple and intuitive npm pack that anyone can use.
- **Customizable**: Customize the appearance and behavior of your notifications.
- **Cross-Browser Support**: Works seamlessly on all modern browsers.

## 📦 Installation

Install notif_log.js using npm:
```bash
npm i notif_log
```

1) include notif_log.js
2) Initialise with logger.init()

🛠️ Usage
Using notif_log.js is as easy as pie! Replace your console.log with the below and watch the magic happen.
- Initialises the logger
```bash
  logger.init()
  ```
- Logs the message via a Desktop Notification only
  ```bash
  logger.log()
  ```
- Logs the message via a Desktop Notification and in the browser console
  ```bash
  console.log()
  ```
- Reverts console.log to original functionality
```bash
  logger.destroy()
  ```
