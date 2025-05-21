# nexterfack# 
🔍 NexterFack – Elite Dorking Tool for Bug Bounty & OSINT 🔐

**NexterFack** is a custom-built Bash script designed by **Inayat Hussain** to generate highly effective **Google** and **GitHub dorks** for reconnaissance, OSINT, and ethical hacking. It empowers bug bounty hunters and penetration testers to find exposed files, sensitive information, admin panels, and developer secrets across the web.

---

## 🎯 Why NexterFack?

NexterFack automates the generation of advanced dorks so that you can focus on exploitation and discovery, not syntax. Ideal for users with limited hardware, this tool requires **no installation of external tools** and runs smoothly even on **4GB RAM** systems or low-end setups like **Replit** or **Termux**.

---

## 🚀 Features

- 🧠 Google Dork Generator (config leaks, logins, APIs, etc.)
- 💻 GitHub Dork Generator (tokens, environment files, passwords)
- ✍️ User-input domain targeting
- ⚡ Extremely lightweight and fast
- 🛠️ Beginner-friendly and educational

---

## 🛠️ How to Use

1. Give execution permission:
   ```bash
   chmod +x nexterfack.sh

    Run the tool:

./nexterfack.sh

Enter your target domain when prompted (e.g., example.com)

NexterFack will generate a list of useful Google and GitHub dorks like:

    site:example.com intitle:"index of"
    site:example.com ext:env OR ext:sql
    site:example.com inurl:admin
    github.com/example.com "password"
    github.com/example.com filename:.env

    You can copy-paste these dorks into:

        🔎 Google

        🐙 GitHub Code Search

📁 Output Example

site:example.com intitle:"index of"
site:example.com ext:log | ext:sql | ext:env
site:example.com inurl:login
github.com/example.com "token"
github.com/example.com filename:config.json

📌 Use Cases

    🔐 Discover misconfigured endpoints

    🔍 Find credentials and API keys in public repos

    📚 Educational reference for learning dork syntax

    ⚔️ Passive reconnaissance during bug bounty engagements

👤 Author

Crafted with dedication by:

Inayat Hussain (a.k.a. Inayat Raj Chohan)
🌍 LinkedIn
📘 Facebook: Inayat Raj Chohan
🐙 GitHub: https://github.com/your-github-username
⚠️ Disclaimer

This tool is intended only for educational and authorized testing purposes. You must have explicit permission to target and test any asset. The creator is not responsible for any misuse.
⭐ Support

If this tool helped you, please star the repository and share it to support my open-source contributions. I’m building tools with limited resources to empower global learners and bug bounty hunters like you!
