<div align="center">

<img src="logo.png" alt="Whiiteroom Logo" width="80" height="80" />

# Whiiteroom

**The OS-Level Distraction-Free Focus Workspace for Windows & Android**

[![Website](https://img.shields.io/badge/Official_Website-whiiteroom.com-6366f1?style=for-the-badge&logo=googlechrome&logoColor=white)](https://whiiteroom.com)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://whiiteroom.com)
[![Android](https://img.shields.io/badge/Android-APK%20Available-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://whiiteroom.com)
[![License](https://img.shields.io/badge/License-Freeware%20%2F%20Proprietary-amber?style=for-the-badge)](https://whiiteroom.com)
[![Release](https://img.shields.io/github/v/release/archits790-ui/whiiteroom-releases?style=for-the-badge&color=emerald)](https://github.com/archits790-ui/whiiteroom-releases/releases)

<br />

<p align="center">
  <strong>Whiiteroom</strong> is an OS-enforced deep work environment that eliminates digital distractions. Unlike browser extensions or standard blocking apps that are easy to bypass, Whiiteroom enforces session limits directly at the operating system level, combined with an embedded Chromium browser that strips YouTube of algorithmic feeds, comments, and recommendations.
</p>

[**🌐 Visit Official Website**](https://whiiteroom.com) • [**⚡ Try Interactive Mockup**](https://whiiteroom.com) • [**📥 Download for Windows**](https://github.com/archits790-ui/whiiteroom-releases/releases/download/v1.5.3/Whiiteroom-Windows-1.5.3-Setup.exe) • [**📖 Product Documentation**](https://whiiteroom.com/docs)

</div>

---

## 🚀 Key Highlights & Features

### 1. 🧠 Whitelist Mode (Allow-Only Control)
The ultimate high-commitment focus environment. Specify only the exact desktop apps, mobile applications, website domains, specific URLs, or local PDF textbook files you need. **Everything else outside your whitelist is blocked by default** — preventing impulsive context switching during exams, study marathons, and deep coding blocks.

### 2. 🔥 Blacklist Mode (Block-Only Control)
Prefer open web access? Target and block only specific time-sink apps, distracting domains, or social media platforms while keeping the rest of your tools and search engines open. Ideal for researchers, journalists, and open-ended technical workflows.

### 3. 📺 Distraction-Free YouTube Engine
Watch educational lectures, coding courses, or specific playlists without the distraction traps. Whiiteroom's embedded browser allows approved video, playlist, or channel URLs while **completely stripping the YouTube homepage feed, recommendation sidebar, Shorts, comments, and autoplay traps from the DOM**.

### 4. 📅 Auto-Start Session Scheduler
Set up a weekly focus calendar. Define recurring or one-time scheduled sessions for specific days and times. Whiiteroom **auto-starts your focus session on time with zero manual action required**. Each schedule supports independent custom whitelists/blacklists and configurable pre-launch warning notifications (1–15 min lead time).

### 5. 🔒 3 Strictness Modes
* **Relax Mode:** Flexible sessions that you can exit early anytime without barriers.
* **Friction Mode:** Adds deliberate typing challenges before letting you quit, eliminating impulsive session cancellation.
* **Strict Mode:** Completely locks workspace boundaries until your session timer finishes — resisting force-kills, task switching, and reboots.

### 6. ☕ Scheduled Rest Windows & Break Timers
Sustainable focus requires planned recovery. Configure scheduled break intervals (e.g., a 10-minute break every 50 minutes). Restrictions automatically lift during break windows for full device access and seamlessly auto-resume when break time expires.

### 7. 🛡️ OS-Level Enforcement & Reboot Persistence
Whiiteroom operates at the kernel/process level using native OS APIs to intercept unauthorized processes and URL navigations before network requests are initiated. If your machine restarts or loses power, Whiiteroom's local state persistence automatically re-engages the lockdown upon boot with your remaining session timer intact.

### 8. 📊 100% Private Distraction Score
Track total focused hours, clean study streaks, and distraction attempt counts over time. All session analytics and whitelist profiles are **stored 100% locally on your device** — your browsing data is never tracked, collected, or sold.

---

## ⚖️ Whiiteroom vs Traditional Focus Apps

A side-by-side technical comparison showing how Whiiteroom differs from traditional website blockers and timer apps:

| Feature / Capability | Whiiteroom | Cold Turkey | Freedom | Opal |
| :--- | :---: | :---: | :---: | :---: |
| **Whitelist Mode (Allow-Only Engine)** | **Native OS-Level**<br><sub>Everything blocked by default</sub> | **Partial**<br><sub>Desktop only</sub> | **No**<br><sub>Blacklist only</sub> | **No**<br><sub>Blacklist only</sub> |
| **Blacklist Mode (Block-Only Control)** | **Yes**<br><sub>Switchable per profile</sub> | **Yes** | **Yes** | **Yes** |
| **Granular YouTube Filtering** | **Yes**<br><sub>Whitelist specific video/playlist/channel; strips feed, comments, Shorts</sub> | **No**<br><sub>Domain block only</sub> | **No**<br><sub>Domain block only</sub> | **No**<br><sub>Domain block only</sub> |
| **Auto-Start Session Scheduler** | **Yes**<br><sub>Weekly recurring & one-time calendar with pre-launch warning</sub> | **No**<br><sub>Manual start required</sub> | **No**<br><sub>Manual start required</sub> | **No**<br><sub>Manual start required</sub> |
| **Scheduled Break Windows** | **Yes**<br><sub>Auto-lift & auto-resume timer windows</sub> | **No**<br><sub>Binary block duration</sub> | **No**<br><sub>Binary block duration</sub> | **No**<br><sub>Binary block duration</sub> |
| **Kernel / OS-Level Enforcement** | **Yes**<br><sub>Process enum & Chromium browser control</sub> | **Yes**<br><sub>Registry locking</sub> | **No**<br><sub>VPN / DNS proxy level</sub> | **No**<br><sub>Screen Time API (iOS)</sub> |
| **Crash & Reboot Persistence** | **Yes**<br><sub>Auto re-locks upon reboot via local SQLite state</sub> | **Partial**<br><sub>Re-engages on boot</sub> | **No**<br><sub>Session ends on restart</sub> | **Partial**<br><sub>iOS Screen Time dependent</sub> |
| **Data Privacy & Telemetry** | **100% Local Device**<br><sub>Zero tracking, zero cloud logging</sub> | **Local** | **Cloud-Synced** | **Cloud-Synced** |
| **Cross-Platform Availability** | **Windows 10/11 & Android**<br><sub>(macOS & iOS on roadmap)</sub> | **Windows & macOS**<br><sub>(No mobile app)</sub> | **Windows, Mac, iOS, Android** | **iOS & macOS Only**<br><sub>(No Windows / Android)</sub> |
| **Launch Pricing Model** | **100% Free PRO Access**<br><sub>(Launch phase offer)</sub> | **$29.99 USD**<br><sub>(One-time Pro license)</sub> | **$39.99 / year**<br><sub>(Subscription)</sub> | **$59.99 / year**<br><sub>(Subscription)</sub> |

---

## 💻 Supported Operating Systems

* **Windows:** Windows 10 & Windows 11 (64-bit native application with process management & embedded Chromium browser).
* **Android:** Native APK available with app whitelist/blacklist interception, YouTube filter, and strict discipline profiles.
* **macOS & iOS:** On active development roadmap.

---

## 📥 Quick Download & Installation

### Windows 10 / 11
1. Download the latest installer from the official release page:
   👉 **[Download Whiiteroom for Windows (Setup.exe)](https://github.com/archits790-ui/whiiteroom-releases/releases/download/v1.5.3/Whiiteroom-Windows-1.5.3-Setup.exe)**
2. Run the installer and follow the setup prompt.
3. Launch Whiiteroom, configure your whitelist or blacklist profile, and start your first focus session.

### Android
* Download the APK directly from the [Official Website Downloads](https://whiiteroom.com/#downloads).

---

## 📚 Community, Guides & Documentation

* 🌐 **Official Website:** [https://whiiteroom.com](https://whiiteroom.com)
* 📖 **Feature Matrix & Guides:** [whiiteroom.com/features](https://whiiteroom.com/features)
* ⏱️ **Focus Sessions & Scheduling:** [whiiteroom.com/focus-sessions](https://whiiteroom.com/focus-sessions)
* 🔒 **Strict Mode & Anti-Bypass Details:** [whiiteroom.com/strict-mode](https://whiiteroom.com/strict-mode)
* 📺 **Distraction-Free YouTube Guide:** [whiiteroom.com/youtube-filter](https://whiiteroom.com/youtube-filter)
* ⚖️ **Comparisons:**
  * [Whiiteroom vs Cold Turkey](https://whiiteroom.com/vs-cold-turkey)
  * [Whiiteroom vs Freedom](https://whiiteroom.com/vs-freedom)
  * [Whiiteroom vs Opal](https://whiiteroom.com/vs-opal)
* ❓ **Frequently Asked Questions:** [whiiteroom.com/faq](https://whiiteroom.com/faq)

---

## 💬 Issue Tracking & Feedback

This public repository serves as the official issue tracker, bug reporting center, and feature roadmap discussion board for Whiiteroom.

* 🐛 **Found a bug?** [Open an Issue](https://github.com/archits790-ui/whiiteroom-App/issues)
* 💡 **Have a feature request or suggestion?** [Start a Discussion](https://github.com/archits790-ui/whiiteroom-App/discussions)

---

<div align="center">
  <sub>Built for students, software engineers, researchers, and competitive exam aspirants (JEE, NEET, UPSC, GATE, CA) who demand real isolation over gentle reminders.</sub>
  <br />
  <br />
  <strong>© 2026 Whiiteroom. All rights reserved. • <a href="https://whiiteroom.com">whiiteroom.com</a></strong>
</div>
