# 🎬 **YouTube Browser App with uBlock Origin** 🚫

A **100% open-source** and lightweight **Electron-based** browser app that loads **YouTube** with the **uBlock Origin** extension to block ads and trackers. 🧑‍💻

---

### 🌟 Features:
- 🚀 **100% Open Source**: The entire codebase is available for anyone to contribute to, modify, or distribute.
- 📺 **Load YouTube** directly in the app.
- 🚫 **Blocks all ads and trackers** using **uBlock Origin**.
- 🔄 **uBlock Origin extension** loads automatically into the app to handle ad-blocking seamlessly.
- 💻 **Runs as a standalone Windows app**. It is available as a separate application and is also **coming soon to macOS**.
- 🛠️ **Dedicated navigation buttons**: Back, Forward, and Reload, providing a smooth browsing experience similar to a regular browser.
- 🔐 **Google Login Supported**: Log in to YouTube using your Google account and access all your subscriptions, history, and personalized features.

---

### ⚙️ Installation Instructions:

1. **Download the installer** (`YouTube Browser Setup 1.0.0.exe`) from the latest release.
2. **Run the installer** and follow the setup steps.
3. Once installed, you can launch the app like any other Windows application. 💻

---

### ⚠️ Known Limitations & Notes

- **Ad-blocking may not be fully effective at the start.**
  - uBlock Origin needs some time to **learn and block ads** effectively as you browse. Ads and trackers may show up initially, but over time, the extension will start filtering them more accurately. ⏳
  - **Be patient!** While it might not block everything right away, it will eventually improve and filter more effectively as you continue browsing.

- **Partial API support in uBlock Origin:**
  - uBlock Origin was originally designed for **Chrome** extensions, and some APIs are only partially supported in **Electron**. ⚙
  - Although the warnings about unsupported APIs (like `webNavigation`, `privacy`, and `contextMenus`) might appear, **ad-blocking will still work** effectively for YouTube and other common ad scenarios.

- **Feature Development**:
  - This app is being actively improved, and future updates will improve compatibility and add more features, including **macOS** support.

---

### 🧑‍💻 Technologies Used:
- **Electron**: Framework for building cross-platform desktop apps.
- **uBlock Origin**: Popular ad-blocking extension.
- **Node.js**: JavaScript runtime for the app's back-end.

---

### 💡 Contributing

This project is open-source, and we welcome contributions! Feel free to fork the repo, make changes, and submit a pull request.

We are open to **bug fixes**, **improvements**, and **feature suggestions**.

---

### 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

Enjoy using your ad-free YouTube experience! 🎉🚫
