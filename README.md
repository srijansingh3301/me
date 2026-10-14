<h1>Hi, I'm Hiro 👋</h1>

**Self taught developer from Varanasi, India.** I build and run web products end to end. Backend, frontend, payments, and the infra that keeps them up.

Mostly **Python** and **JavaScript**. I've been shipping and maintaining things in production since 2022.

🌐 [srijann.dev](https://srijann.dev)

<hr>

### What I work on

* **Full stack web apps.** Flask backends, admin panels, auth and payment flows
* **Payment integrations.** Crypto, card and PayPal checkouts, webhooks, retries and reconciliation
* **Discord bots and automation.** Order queues, ticket handling, services that run unattended for months
* **Running production.** Cloudflare, logging, database locking, uptime, all the unglamorous parts

<hr>

### Tech

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<hr>

### Projects

**[Sboosts](https://sboosts.com)** is a Discord custom bot platform. Founded 2022, built and run solo.
Flask + SQLAlchemy backend, vanilla JS frontend, four payment gateways (crypto, card, PayPal, Razorpay), self serve reseller and customer panels, admin dashboard with server side pagination and search, and a Pycord bot handling the order queue and support tickets.

<hr>

### GitHub

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=srijansingh3301&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs?username=srijansingh3301&layout=compact&hide_border=true&langs_count=6" alt="Top languages" />
</p>

<hr>

### Reach me

[![Website](https://img.shields.io/badge/srijann.dev-000000?style=flat-square&logo=firefox&logoColor=white)](https://srijann.dev)
[![Email](https://img.shields.io/badge/Email-8B89CC?style=flat-square&logo=protonmail&logoColor=white)](mailto:hiroo1337s@proton.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-handle)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/users/your-id)

<hr>

<details>
<summary><code>hiro.py</code></summary>

```python
from dataclasses import dataclass


@dataclass(frozen=True)
class Hiro:
    role: str = "Developer"
    location: str = "Varanasi, India"
    languages: tuple[str, ...] = ("Python", "JavaScript")
    focus: tuple[str, ...] = ("backend", "payments", "automation")
    editor: str = "vscode"
    open_to_work: bool = True


me = Hiro()
```

</details>
