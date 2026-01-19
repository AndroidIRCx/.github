# AndroidIRCx 🚀

**AndroidIRCx** is an open-source ecosystem focused on building a **modern, secure, and privacy-first IRC experience** for Android and the web.

The project combines:
- 📱 a powerful Android IRC client
- 🌐 a supporting web / backend system
- 🔐 strong end-to-end encryption
- 🌍 a decentralized, network-friendly IRC approach

---

## 📦 Repositories

### 🔹 AndroidIRCx (Android Application)
📁 Repository: **AndroidIRCx/AndroidIRCx**

The main Android IRC client, built using **React Native with native Kotlin/Java modules**.

#### ✨ Key Features
- Full IRCv3 support
- TLS 1.3 (ChaCha20-Poly1305)
- **End-to-End Encryption** (XChaCha20-Poly1305)
- ZNC integration (including TOR connections)
- Multiple networks and servers
- NickServ / ChanServ support
- DCC support (work in progress)
- Push notifications
- Google Play Integrity API
- Strong focus on user privacy and anonymity

#### 🛠 Tech Stack
- React Native (Hermes)
- Kotlin / Java (native modules)
- Firebase (Crashlytics, FCM)
- Libsodium-style cryptography
- Android 8+ (API 26+)

➡️ Repository:  
https://github.com/AndroidIRCx/AndroidIRCx

---

### 🔹 e2e.dll (End-to-End Encryption Library)
📁 Repository: **AndroidIRCx/e2e.dll**

A standalone **cryptographic library** designed for secure, end-to-end encrypted communication within the AndroidIRCx ecosystem and beyond.

#### ✨ Features
- XChaCha20-Poly1305 authenticated encryption
- Secure key generation and handling
- Message authentication and integrity protection
- Designed for IRC-style messaging workflows
- Minimal, auditable codebase

#### 🛠 Tech Stack
- Native cryptographic primitives
- Libsodium-compatible design
- Cross-platform friendly architecture

➡️ Repository:  
https://github.com/AndroidIRCx/e2e.dll

---

## 🔐 Security & Privacy

AndroidIRCx is built with a **privacy-first philosophy**:
- Minimal logging
- Client-side message encryption
- No IP address sharing with third parties
- TOR-friendly infrastructure
- Open-source codebase for full transparency

---

## 🤝 Contributing

Contributions are welcome:
- 🐞 Bug reports
- 💡 Feature requests
- 🔧 Pull requests
- 🌍 Translations (i18n)

Please review the repository-specific guidelines before submitting a pull request.

---

## 📜 License

Projects within the AndroidIRCx organization are released under:
- **GPL-3.0**, or
- another clearly specified open-source license per repository

---

## 🌐 Links
- 🌍 Website: https://androidircx.com
- 📱 Google Play: https://play.google.com/store/apps/details?id=com.androidirc
- 💬 IRC: `#AndroidIRCx`
- 🧠 GitHub Organization: https://github.com/AndroidIRCx

---

## ❤️ Author & Maintainer

Developed and maintained by  
**Velimir Majstorov** and the AndroidIRCx community.

If you value IRC, privacy, and open-source software — welcome aboard.
