# My Personal Portfolio 🚀

This is the source code for my personal portfolio website, live at [syversen.dev](https://syversen.dev). I use this site to showcase my personal projects, experience from internships, and my IT skills.

## 🛠 Tech Stack
* **Frontend:** Clean HTML5 and CSS3 (No heavy frameworks, just responsive code).
* **Hosting:** Cloudflare Pages.
* **Version Control:** Git & GitHub.

## 🌐 Environment Setup (Dev, QA, Prod)
To mirror the workflow used by professional developer teams at large tech companies, I have set up three separate branches and environments for this project:

* **Prod (`main` branch):** Deployed live to `syversen.dev`. This is the public site everyone can see.
* **QA (`qa` branch):** Used to test and double-check changes before they go live on the main site.
* **Dev (`dev` branch):** My personal sandbox environment on the web for testing out new features first.

### 🔒 Security & IP-Locking via Cloudflare WAF
To prevent the public from seeing my unfinished work in Dev and QA, I have secured these environments:
* Using **Cloudflare WAF**, I created a rule that blocks everyone in the world from accessing `dev.syversen.dev` and `qa.syversen.dev`.
* These domains are **only open for my own home IP address**. Since my ISP originally used CGNAT, I contacted Altibox and got a dedicated public IPv4 address (CGNAT-opt-out) so I could set up this firewall protection properly.

## 📂 Repository Structure
* `/images` - Images and icons used across the website.
* `/files` - Downloadable documents like my CV and certificates.
* `index.html` - The main entry point for the portfolio.
* `style.css` - All the custom styling and responsive layout rules.

