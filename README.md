<div align="center">

<img src="https://img.shields.io/badge/Dork--Recon-v1.0.0-red?style=for-the-badge&logo=target&logoColor=white" alt="Dork-Recon"/>

# 🔍 Dork-Recon

### AI-Powered Google Dorking & OSINT Reconnaissance Tool

[![Live Demo](https://img.shields.io/badge/Live%20Demo-dork--recon.netlify.app-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://dork-recon.netlify.app/)
[![GitHub](https://img.shields.io/badge/GitHub-rohit--1006-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rohit-1006)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Made With](https://img.shields.io/badge/Made%20With-Google%20AI%20Studio-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://aistudio.google.com/)

> ⚠️ **Disclaimer:** This tool is intended for **authorized security research, bug bounty hunting, and educational purposes only.** Unauthorized use against systems you do not have explicit permission to test is illegal. The developer assumes no liability for misuse.

</div>

---

## 🧠 About the Project

**Dork-Recon** is an AI-powered Google Dorking and OSINT (Open Source Intelligence) reconnaissance web application built for security researchers, penetration testers, and bug bounty hunters. It leverages Google AI Studio to intelligently generate targeted search dorks based on user-defined targets, helping researchers discover exposed files, sensitive directories, login panels, vulnerable parameters, and much more — all from a clean, intuitive web interface.

Traditional Google dorking requires deep knowledge of advanced search operators. Dork-Recon eliminates that barrier by using AI to generate high-quality, context-aware dorks tailored to your target domain or technology stack.

---

## ✨ Features

- 🤖 **AI-Powered Dork Generation** — Uses Google Gemini AI to generate smart, context-aware Google dorks
- 🎯 **Target-Based Reconnaissance** — Input a domain or keyword and get dorks tailored to that target
- 📂 **Categorized Results** — Dorks are organized by category (files, logins, configs, vulnerabilities, etc.)
- ⚡ **One-Click Search** — Instantly redirect generated dorks to Google with a single click
- 📋 **Copy to Clipboard** — Quickly copy any dork for use in your terminal or browser
- 🌐 **Fully Web-Based** — No installation needed; accessible from any browser
- 🎨 **Clean UI** — Intuitive, hacker-aesthetic interface designed for usability
- 🔐 **Ethical Design** — Built with responsible disclosure principles in mind
- 📱 **Responsive** — Works across desktop and mobile devices

---

## 🌐 Live Demo

> 🚀 Try it now — no installation required!

**[https://dork-recon.netlify.app/](https://dork-recon.netlify.app/)**

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **AI Engine** | Google Gemini (via Google AI Studio) |
| **Deployment** | Netlify |
| **Design** | Custom CSS with hacker/security aesthetic |

---

1. **Input your target** — Enter a domain name (e.g., `example.com`) or a technology keyword (e.g., `WordPress`, `Apache`).
2. **AI generates dorks** — The integrated Gemini AI model constructs relevant Google dorks using advanced operators like `inurl:`, `intitle:`, `filetype:`, `site:`, `ext:`, etc.
3. **Review and search** — Browse categorized results and click any dork to run it directly on Google, or copy it for use in your recon workflow.

---

## 🎯 Use Cases

- 🔎 **Bug Bounty Recon** — Quickly surface exposed endpoints, sensitive files, and misconfigured services on target domains
- 🕵️ **OSINT Investigations** — Gather open-source intelligence on organizations or individuals
- 🧪 **Penetration Testing** — Supplement your recon phase with AI-driven dork suggestions
- 🎓 **Security Education** — Learn Google dorking techniques by observing AI-generated examples
- 📝 **CTF Challenges** — Find hidden flags and clues in Capture The Flag competitions

---

## 📂 Google Dork Categories

Dork-Recon generates dorks across the following categories:

| Category | Description | Example Operators |
|----------|-------------|-------------------|
| 📄 **Exposed Files** | Find sensitive documents and files | `filetype:pdf`, `ext:sql`, `ext:env` |
| 🔐 **Login Panels** | Discover admin and login portals | `intitle:"admin login"`, `inurl:/admin` |
| ⚙️ **Config Files** | Locate exposed configuration files | `inurl:config.php`, `filetype:xml` |
| 🗄️ **Database Files** | Find exposed database dumps | `filetype:sql "password"` |
| 🚨 **Vulnerable Params** | Identify potentially injectable parameters | `inurl:?id=`, `inurl:?page=` |
| 📁 **Open Directories** | Find directory listings | `intitle:"index of"` |
| 🔑 **Credentials** | Discover leaked credentials | `intext:"password" filetype:log` |
| 📊 **OSINT** | Gather organizational intelligence | `site:linkedin.com`, `site:pastebin.com` |
| 🖥️ **Technology Fingerprinting** | Identify tech stack details | `inurl:wp-content`, `intitle:"phpMyAdmin"` |
| 📋 **Backup Files** | Locate backup files | `ext:bak`, `ext:backup`, `ext:old` |

---

## 🚀 Getting Started

### Option 1: Use the Live Web App (Recommended)

No installation needed. Just visit:
```
https://dork-recon.netlify.app/
```

## 📖 Usage Guide

### Basic Recon

1. **Open the tool** at [dork-recon.netlify.app](https://dork-recon.netlify.app/)
2. **Enter your target** in the input field (e.g., `target.com`)
3. **Select dork categories** you want to generate (or select all)
4. **Click "Generate"** — the AI will create targeted dorks
5. **Click any dork** to search it on Google instantly, or use the copy button

### Advanced Usage

- Combine a **domain + technology** for more specific dorks (e.g., `example.com WordPress`)
- Use with **VPN or anonymous browsing** for OPSEC during authorized recon
- Export generated dorks and use them with tools like **Shodan**, **Censys**, or **DorkScanner**
- Integrate with your **bug bounty workflow** alongside tools like Burp Suite, Amass, or Subfinder

---

## 📸 Screenshots

> *(Add your screenshots here)*

| Home Screen | Dork Generation | Results View |
|:-----------:|:---------------:|:------------:|
| ![Home](screenshots/home.png) | ![Generate](screenshots/generate.png) | ![Results](screenshots/results.png) |

---

## 🔐 Security & Ethics

This tool is built with **responsible disclosure** in mind:

- ✅ Only test on systems you **own** or have **written permission** to test
- ✅ Follow the target's **bug bounty policy** and **scope**
- ✅ Report discovered vulnerabilities through **proper channels**
- ❌ Do not use this tool for unauthorized access or illegal activities
- ❌ Do not use on systems outside your authorized scope

**Resources:**
- [HackerOne Disclosure Guidelines](https://www.hackerone.com/disclosure-guidelines)
- [Bugcrowd VRT](https://bugcrowd.com/vulnerability-rating-taxonomy)
- [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)

---

## 🗺️ Roadmap

- [x] AI-powered dork generation with Gemini
- [x] One-click Google search integration
- [x] Categorized dork output
- [x] Responsive web UI
- [ ] Export dorks as `.txt` / `.csv`
- [ ] Dork history & session saving
- [ ] Integration with Shodan / Censys APIs
- [ ] Custom dork templates
- [ ] Bulk domain input support
- [ ] Browser extension version
- [ ] CLI version (Python)

---

## 🤝 Contributing

Contributions are welcome! If you have ideas, dork templates, or improvements:

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

Please make sure your contributions follow ethical security research principles.

---

## 👤 Author

<div align="center">

**Rohit10 (rohit-1006)**

*Security Researcher · Penetration Tester · Bug Bounty Hunter · CTF Player*

```
class Rohit:
    role       = "Security Researcher & Tool Developer"
    focus      = ["Web Application Security", "Bug Bounty", "Penetration Testing"]
    languages  = ["Python", "Bash", "PowerShell"]
    platforms  = ["Kali Linux", "Parrot OS", "BlackArch"]
    currently  = "Building and improving open-source security tooling"
```

</div>

---

## 🌐 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-rohit--1006-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rohit-1006)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Rohit10-212C42?style=for-the-badge&logo=tryhackme&logoColor=red)](https://tryhackme.com/p/Rohit10)
[![HackerOne](https://img.shields.io/badge/HackerOne-Bug%20Hunter-494649?style=for-the-badge&logo=hackerone&logoColor=white)](https://hackerone.com)
[![Bugcrowd](https://img.shields.io/badge/Bugcrowd-Bug%20Hunter-F26822?style=for-the-badge&logo=bugcrowd&logoColor=white)](https://bugcrowd.com)

</div>

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**⭐ If this tool helped your recon workflow, please give it a star!**

*Built with ❤️ by [rohit-1006](https://github.com/rohit-1006) for the security community*

[![Visits](https://visitor-badge.laobi.icu/badge?page_id=rohit-1006.dork-recon)](https://github.com/rohit-1006)

</div>
