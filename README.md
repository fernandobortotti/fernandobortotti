<!-- ░▒▓ CYBERPUNK HEADER ▓▒░ -->
<a href="https://github.com/fernandobortotti">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0221,50:ff003c,100:00fff5&height=200&section=header&text=Fernando%20Bortotti&fontColor=00fff5&fontSize=50&fontAlignY=35&desc=%2F%2F%20red%20team%20operator%20//%20pentester%20//%206x%20CVE&descAlignY=58&descSize=18&animation=fadeIn" alt="header"/>
</a>

<div align="center">

<!-- TYPING SVG -->
<a href="https://fernandobortotti.github.io/artigos/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00FFF5&center=true&vCenter=true&width=650&lines=%3E+Breaking+what+others+build.;%3E+Web+%26+Mobile+Application+Security;%3E+Bug+Bounty+Hunter+%2F%2F+Offensive+Security;%3E+6+CVEs+published+and+counting..." alt="Typing SVG" />
</a>

<!-- STATUS BADGES -->
<p>
  <img src="https://img.shields.io/badge/ROLE-RED_TEAM-ff003c?style=for-the-badge&labelColor=0d0221" />
  <img src="https://img.shields.io/badge/CVEs-6-00fff5?style=for-the-badge&labelColor=0d0221" />
  <img src="https://img.shields.io/badge/STATUS-HUNTING-9d00ff?style=for-the-badge&labelColor=0d0221" />
</p>

</div>

---

```console
root@bortotti:~# whoami
```
```yaml
operator:      Fernando Bortotti
class:         Offensive Security / Red Team
focus:         [ Web AppSec, Mobile AppSec, Cloud (AWS), Bug Bounty ]
credentials:   6x CVE author  //  bug bounty researcher
blog:          https://fernandobortotti.github.io/artigos/
status:        > actively hunting_
```

Atuo como **pentester** e **bug hunter**, com ampla experiência na identificação e exploração
de vulnerabilidades em aplicações **web** e **mobile**. Minha atuação em programas de bug bounty
resultou na descoberta e reporte de diversas falhas críticas — e no registro de **6 CVEs** com
impacto real (RCE, XSS armazenado, path traversal e bypass de autenticação).

> 📖 Publico writeups e análises técnicas no meu blog: **[fernandobortotti.github.io/artigos](https://fernandobortotti.github.io/artigos/)**

---

## `>` CVE_DATABASE // exploits publicados

<div align="center">

Pesquisa de segurança no **pgAdmin 4** — 2 vulnerabilidades **CRITICAL** com execução remota de código.

</div>

| CVE | Vulnerabilidade | Tipo | CVSS |
|:---|:---|:---:|:---:|
| [CVE-2026-12046](https://www.cve.org/CVERecord?id=CVE-2026-12046) | Unauthenticated pickle deserialization → **RCE** | `CWE-306 / 502` | ![](https://img.shields.io/badge/9.5-CRITICAL-ff003c?style=flat-square&labelColor=0d0221) |
| [CVE-2026-12048](https://www.cve.org/CVERecord?id=CVE-2026-12048) | Stored XSS via `html-react-parser` | `CWE-79` | ![](https://img.shields.io/badge/9.3-CRITICAL-ff003c?style=flat-square&labelColor=0d0221) |
| [CVE-2026-7819](https://www.cve.org/CVERecord?id=CVE-2026-7819) | Symlink path traversal → arbitrary file write | `CWE-61 / 22` | ![](https://img.shields.io/badge/8.1-HIGH-ff6b00?style=flat-square&labelColor=0d0221) |
| [CVE-2026-7818](https://www.cve.org/CVERecord?id=CVE-2026-7818) | Unsafe deserialization → **RCE** | `CWE-502` | ![](https://img.shields.io/badge/7.3-HIGH-ff6b00?style=flat-square&labelColor=0d0221) |
| [CVE-2026-7820](https://www.cve.org/CVERecord?id=CVE-2026-7820) | Account-lockout bypass (Flask-Security) | `CWE-307` | ![](https://img.shields.io/badge/6.9-MEDIUM-ffd000?style=flat-square&labelColor=0d0221) |
| [CVE-2026-12047](https://www.cve.org/CVERecord?id=CVE-2026-12047) | HTML injection em endpoints de cloud | `CWE-79 / 116` | ![](https://img.shields.io/badge/4.8-MEDIUM-ffd000?style=flat-square&labelColor=0d0221) |

<div align="center">
  <a href="https://www.cve.org/CVERecord/SearchResults?query=bortotti">
    <img src="https://img.shields.io/badge/%E2%86%92_ver_todos_os_CVEs-cve.org-00fff5?style=for-the-badge&labelColor=0d0221" />
  </a>
</div>

---

## `>` ARSENAL // ferramentas & táticas

<div align="center">

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white&labelColor=0d0221)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-00549E?style=for-the-badge&logo=owasp&logoColor=white&labelColor=0d0221)
![Nmap](https://img.shields.io/badge/Nmap-004880?style=for-the-badge&logo=gnometerminal&logoColor=00fff5&labelColor=0d0221)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white&labelColor=0d0221)
![SQLmap](https://img.shields.io/badge/SQLmap-c1121f?style=for-the-badge&logo=databricks&logoColor=white&labelColor=0d0221)
![ffuf](https://img.shields.io/badge/ffuf-9d00ff?style=for-the-badge&logo=fastapi&logoColor=white&labelColor=0d0221)
![AWS](https://img.shields.io/badge/AWS_Cloud_Sec-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=0d0221)
![Custom Tooling](https://img.shields.io/badge/Custom_Tooling-ff003c?style=for-the-badge&logo=hackthebox&logoColor=white&labelColor=0d0221)

</div>

| Domínio | Táticas |
|:---|:---|
| **Web AppSec** | Interceptação e análise de tráfego HTTP, exploração de OWASP Top 10, fuzzing e descoberta de conteúdo (ffuf), automação de SQLi (SQLmap) |
| **Recon & Exploit** | Mapeamento de rede e enumeração de serviços (Nmap), desenvolvimento e execução de exploits (Metasploit) |
| **Cloud Security** | Exploração e hardening de ambientes AWS, enumeração de buckets S3, abuso de APIs |
| **Tooling próprio** | Ferramentas customizadas em Python para enumeração e exploração automatizada |

---

## `>` STATS // telemetria

<div align="center">

  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=fernandobortotti&show_icons=true&theme=synthwave&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d0221&title_color=00fff5&icon_color=ff003c&text_color=ffffff"/>
  <img height="180em" src="https://github-readme-streak-stats.herokuapp.com?user=fernandobortotti&theme=synthwave&hide_border=true&background=0d0221&stroke=ff003c&ring=00fff5&fire=ff003c&currStreakLabel=00fff5"/>

</div>

<div align="center">

### `>` STACK

<img alt="Python" height="42" src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg?raw=true">&nbsp;&nbsp;
<img alt="JavaScript" height="42" src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg?raw=true">&nbsp;&nbsp;
<img alt="TypeScript" height="42" src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg?raw=true">&nbsp;&nbsp;
<img alt="Node.js" height="42" src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original.svg?raw=true">&nbsp;&nbsp;
<img alt="React" height="42" src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg?raw=true">&nbsp;&nbsp;
<img alt="HTML5" height="42" src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg?raw=true">&nbsp;&nbsp;
<img alt="AWS" height="42" src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg?raw=true">&nbsp;&nbsp;
<img alt="Linux" height="42" src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg?raw=true">

</div>

---

## `>` CONTACT // uplink

<div align="center">

<a href="https://fernandobortotti.github.io/artigos/"><img src="https://img.shields.io/badge/BLOG-artigos-00fff5?style=for-the-badge&logo=githubpages&logoColor=white&labelColor=0d0221" /></a>
<a href="https://www.cve.org/CVERecord/SearchResults?query=bortotti"><img src="https://img.shields.io/badge/CVEs-cve.org-ff003c?style=for-the-badge&logo=commonworkflowlanguage&logoColor=white&labelColor=0d0221" /></a>
<a href="https://github.com/fernandobortotti"><img src="https://img.shields.io/badge/GitHub-fernandobortotti-9d00ff?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0221" /></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00fff5,50:ff003c,100:0d0221&height=120&section=footer&text=%2F%2F%20stay%20curious%20//%20break%20things%20//%20report%20responsibly&fontColor=00fff5&fontSize=14&fontAlignY=70" alt="footer"/>

</div>
