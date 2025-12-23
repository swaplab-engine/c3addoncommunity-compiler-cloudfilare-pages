# 🛠️ C3Addon Community Compiler (Cloud Edition)

A professional real-time bridge service designed to compile and distribute Construct 3 Addons (SDK v2) directly from source repositories.

---

## 🌐 Overview
**C3Addon Community Compiler** acts as a transparent bridge between public source code collections and the final distribution format. This service automates the process of wrapping repository content into a valid `.c3addon` package in real-time.

- **Frontend Host:** [Cloudflare Pages](https://c3addoncommunity.swaplab.net)
- **API Bridge:** Hosted on SwapLab Private VPS
- **Primary Source:** [EMIINDO GitHub Repositories](https://github.com/EMIINDO?tab=repositories)

---

## ⚙️ How It Works
The compiler follows a strictly transparent workflow to ensure the integrity of the original source code:

1.  **Direct Fetch:** The system pulls the latest source code from the public repositories at [EMIINDO](https://github.com/EMIINDO).
2.  **Real-time Wrapping:** The bridge processes the project root, ensures the presence of `addon.json`, and wraps the contents into a `.c3addon` ZIP structure.
3.  **Instant Distribution:** Users receive a ready-to-install package for Construct 3 without any modification to the original logic or scripts.

---

## 📜 Documentation & Technical Resources
For developers looking to understand the underlying SDK structure or porting process:

* **Official Manual:** [SDK v2 Porting & Documentation](https://www.construct.net/en/forum/construct-3/plugin-sdk-10/porting-list-addon-sdk-v2-185208)
* **SDK Reference:** Construct 3 Plugin SDK v2 standards.

---

## ⚖️ Intellectual Property & Credits
Transparency is our core principle. This project is a **utility tool** and does not claim ownership over the addons compiled through this service.

> [!IMPORTANT]
> **Original Works & Developers:** All community addons, original logic, and documentation are credited to their respective owners. You can find the original developer resources, community support, and documentation for every addon at the **Construct 3 Official Addon Store**:
> 👉 [https://www.construct.net/en/make-games/addons](https://www.construct.net/en/make-games/addons)

---

## 🌍 Explore Other Community Tools
We provide a suite of free tools to support the Construct 3 ecosystem:

* **[Public SwapLab](https://public.swaplab.net)**: A sign-in-free build service for testing custom addons. 
    * *Details & Discussion:* [Construct Forum Thread](https://www.construct.net/en/forum/game-development/tools-and-resources-27/tool-addon-devs-test-custom-187542).
* **[Keystore SwapLab](https://keystore.swaplab.net)**: A dedicated management tool for Android Keystore files, essential for mobile application publishing.

---

## 🚀 Deployment Features
This repository is deployed using **Cloudflare Pages** for maximum availability and speed.
- **DDoS Protection:** Secured by Cloudflare & Rate-Limiting Redis.
- **Real-time Synchronization:** Fetches live data from GitHub API.
- **Automated Cleanup:** Temporary build files are purged automatically from the bridge server.


<img width="1179" height="693" alt="c3addon-community" src="https://github.com/user-attachments/assets/0617df62-64c0-4e89-b292-e9bee932dd1a" />


---

## 🤝 Contribution & Feedback
This is a public repository under the **SwapLab Engine** organization. We welcome transparency and community feedback to improve the compilation bridge.

---
© 2025 [SwapLab Engine](https://swaplab.net) | [C3Addon Community Compiler](https://c3addoncommunity.swaplab.net)
