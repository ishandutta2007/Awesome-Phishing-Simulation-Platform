# Awesome-Phishing-Simulation-Platform

## Top Phishing Simulation Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Security Awareness Training, Phishing Simulations, Employee Testing & Behavioral Risk Reduction*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Phishing Simulation**. These systems send realistic but safe simulated phishing emails to employees, track interactions, deliver just-in-time training, and help organizations measure and reduce human risk.



**Examples** include Hoxhunt, KnowBe4, Cofense PhishMe, Proofpoint PhishAlarm / ZenGuide, Infosec IQ, Usecure, Hook Security, Living Security, Phished, and SafeTitan (the category leaders).



**Open-source emphasis**: The standout open-source tool is **Gophish**, widely used for authorized phishing simulations. Additional open toolkits and automation helpers exist. Full enterprise awareness platforms with adaptive AI, large content libraries, and managed services remain commercial. This section prioritizes practical open options.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Starting Pricing | Free Tier / Trial Limits |
| --- | --- | --- | --- |
| **[Hoxhunt](https://hoxhunt.com/)** | Adaptive, gamified phishing simulation and security awareness platform focused on behavioral change and personalized difficulty. | Starts at ~$35 to $45/user/year (~$3.00–$3.75/user/month, min. seat commit typically 250+ users) | 30-day guided proof-of-concept / free pilot (up to ~50–100 trial users by request) |
| **[KnowBe4](https://www.knowbe4.com/)** | Leading security awareness training and phishing simulation platform with extensive template libraries and reporting. | Starts at $10.05/user/year (Silver tier for 100–999 users; minimum annual purchase of 25–100 seats) | Free Phishing Security Test (PST) for up to 100 users (single baseline test, 1 phishing template) |
| **[Cofense PhishMe](https://cofense.com/)** | Phishing simulation and reporting platform that emphasizes real-world attack simulation and employee reporting workflows. | Starts at ~$2.50/user/month (~$30/user/year, typically requiring a 100–500 seat minimum commitment) | Free PhishMe trial for 30 days (limited to 50 simulated email sends & reporting workflow test) |
| **[Proofpoint (PhishAlarm / ZenGuide)](https://www.proofpoint.com/)** | Enterprise phishing simulation and awareness capabilities integrated with Proofpoint’s broader email security and training suite. | Starts at ~$2.80–$3.50/user/month (~$34–$42/user/year, typically bundled with minimum contract sizes of 100+ seats) | 30-day proof-of-concept trial upon partner/sales approval (capped to ~50 test mailboxes) |
| **[Infosec IQ](https://www.infosecinstitute.com/iq/)** | Security awareness and phishing simulation platform offering training content and campaign management. | Starts at ~$1.75–$2.20/user/month billed annually (~$21–$26/user/year, min. 25–50 seats) | Free 30-day trial (capped to 1 phishing simulation campaign for up to 25 employees) |
| **[Usecure](https://www.usecure.io/)** | Security awareness platform that includes phishing simulation (uPhish) and automated training assignments. | Starts at £1.70 (~$2.15)/user/month (Core plan for uPhish + uLearn; no long-term contract lock-in) | 14-day full-feature free trial (unlimited simulation sends for up to 50 users) |
| **[Hook Security](https://www.hooksecurity.co/)** | Phishing simulation and awareness training focused on realistic campaigns and measurable risk reduction. | Starts at $2.25/user/month billed annually (Deepfake & Phishing bundle, min. 25 seats) | 14-day free trial (includes access to PsySec simulation templates and testing for up to 25 users) |
| **[Living Security](https://www.livingsecurity.com/)** | Human risk management platform that includes phishing simulations, training, and behavioral analytics. | Starts at ~$2.90–$3.75/user/month billed annually (~$35–$45/user/year, min. 250 seats) | 14-day guided sandbox / trial access (limited to up to 25 simulated phishing test recipients) |
| **[Phished](https://phished.io/)** | Phishing simulation and awareness platform aimed at continuous testing and employee education. | Starts at €2.50 (~$2.75)/user/month billed annually (Essential AI-driven simulation plan, min. 25 seats) | 14-day free trial (up to 20 automated phishing simulation tests with immediate reporting) |
| **[SafeTitan](https://www.safetitan.com/)** | Security awareness and phishing simulation solution with campaign management and training features. | Starts at $1.65/user/month billed annually (TitanHQ Security Awareness suite, min. 25 users) | 14-day full-access free trial (up to 50 mailboxes for phishing campaigns & training modules) |



## Open-Source GitHub Projects

- **[Gophish](https://github.com/gophish/gophish)**  

  The leading open-source phishing toolkit. Allows security teams to create and run authorized phishing campaigns, track results, and support awareness training. Simple to deploy and widely adopted.



- **[King Phisher](https://github.com/CrimsonForge-io/king-phisher)**  

  Open-source phishing campaign toolkit with flexible email and landing-page control, useful for more advanced or customized simulations.



- **[Gophish automation and provisioning helpers (G-SIM and similar)](https://github.com/)**  

  Community tools that simplify deploying and managing Gophish instances (e.g., cloud provisioning scripts).



- **[PhishForge and newer open simulation experiments](https://github.com/)**  

  Emerging open-source phishing simulation projects focused on campaigns, templates, and lighter-weight training workflows.



- **[Landing-page and template open collections](https://github.com/)**  

  Community repositories of phishing email templates and cloned pages intended for authorized testing only.



- **[Campaign reporting and analytics open scripts](https://github.com/)**  

  Tools that process Gophish or similar campaign results into dashboards or risk scores.



- **[Email delivery and SMTP testing open utilities](https://github.com/)**  

  Supporting tools for ensuring simulation emails are properly configured and delivered.



- **[Integration connectors for Gophish](https://github.com/)**  

  API clients and scripts that connect open simulation platforms to ticketing, SIEM, or LMS systems.



- **[Educational phishing labs and CTF-style tools](https://github.com/)**  

  Open projects designed for security training environments and controlled learning scenarios.



- **[Policy and playbook open resources](https://github.com/)**  

  Templates and guidance for running ethical, authorized phishing simulation programs.



### Additional Strong Open-Source Options

- Deploying **Gophish** as the core engine for internal phishing simulations.

- Extending Gophish with custom templates, landing pages, and reporting scripts.

- Using **King Phisher** when more granular control over campaign content is required.

- Accepting that large adaptive content libraries, AI-driven personalization, gamification at scale, and fully managed awareness programs still favor commercial platforms (KnowBe4, Hoxhunt, Cofense, Proofpoint, etc.).

- Combining open simulation tools with commercial training content when a hybrid approach is preferred.



**Frameworks for building custom systems**: Deploy Gophish (or King Phisher) → create realistic templates and landing pages → run authorized campaigns against employee groups → capture results and click/report metrics → deliver immediate training or coaching → track improvement over time. This stack is fully open and effective for many organizations. Commercial platforms remain the practical choice when teams need extensive content, advanced analytics, automated assignment of training, and enterprise support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Phishing simulations must only be conducted with explicit organizational authorization. Unauthorized phishing is illegal and unethical. Open-source tools can be powerful; they must be used responsibly, with proper scoping, legal review, and employee communication policies. Always protect collected data and comply with privacy regulations. This list is not legal, security, or compliance advice.



---

**Made for security awareness teams, CISOs, and organizations that want to strengthen the human layer of defense.**

Let's keep phishing resilience high, ethical, and continuously improving.
