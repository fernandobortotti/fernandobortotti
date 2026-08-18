<!-- ░▒▓ MATRIX RAIN HEADER ▓▒░ -->
<img width="100%" src="./matrix.svg" alt="matrix rain header"/>

<div align="center">

<!-- TYPING SVG -->
<a href="https://fernandobortotti.github.io/artigos/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00FF41&center=true&vCenter=true&width=680&lines=Wake+up...+the+system+has+you.;%3E+Breaking+what+others+build.;%3E+Web+%26+Mobile+Application+Security;%3E+Bug+Bounty+%2F%2F+Offensive+Security;%3E+6+CVEs+published+and+counting..." alt="Typing SVG" />
</a>

<!-- STATUS BADGES -->
<p>
  <img src="https://img.shields.io/badge/ROLE-RED_TEAM-00ff41?style=for-the-badge&labelColor=0d0208" />
  <img src="https://img.shields.io/badge/CVEs-6-00ff41?style=for-the-badge&labelColor=0d0208" />
  <img src="https://img.shields.io/badge/STATUS-HUNTING-008f11?style=for-the-badge&labelColor=0d0208" />
</p>

</div>

---

```console
root@matrix:~# whoami
```
```yaml
operator:      [ REDACTED ]
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
| [CVE-2026-12046](https://www.cve.org/CVERecord?id=CVE-2026-12046) | Unauthenticated pickle deserialization → **RCE** | `CWE-306 / 502` | ![](https://img.shields.io/badge/9.5-CRITICAL-a80000?style=flat-square&labelColor=0d0208) |
| [CVE-2026-12048](https://www.cve.org/CVERecord?id=CVE-2026-12048) | Stored XSS via `html-react-parser` | `CWE-79` | ![](https://img.shields.io/badge/9.3-CRITICAL-a80000?style=flat-square&labelColor=0d0208) |
| [CVE-2026-7819](https://www.cve.org/CVERecord?id=CVE-2026-7819) | Symlink path traversal → arbitrary file write | `CWE-61 / 22` | ![](https://img.shields.io/badge/8.1-HIGH-c1440e?style=flat-square&labelColor=0d0208) |
| [CVE-2026-7818](https://www.cve.org/CVERecord?id=CVE-2026-7818) | Unsafe deserialization → **RCE** | `CWE-502` | ![](https://img.shields.io/badge/7.3-HIGH-c1440e?style=flat-square&labelColor=0d0208) |
| [CVE-2026-7820](https://www.cve.org/CVERecord?id=CVE-2026-7820) | Account-lockout bypass (Flask-Security) | `CWE-307` | ![](https://img.shields.io/badge/6.9-MEDIUM-8a7500?style=flat-square&labelColor=0d0208) |
| [CVE-2026-12047](https://www.cve.org/CVERecord?id=CVE-2026-12047) | HTML injection em endpoints de cloud | `CWE-79 / 116` | ![](https://img.shields.io/badge/4.8-MEDIUM-8a7500?style=flat-square&labelColor=0d0208) |

<div align="center">
  <a href="https://www.cve.org/CVERecord/SearchResults?query=bortotti">
    <img src="https://img.shields.io/badge/%E2%86%92_ver_todos_os_CVEs-cve.org-00ff41?style=for-the-badge&labelColor=0d0208" />
  </a>
</div>

---

## `>` ARSENAL // ferramentas & táticas

<div align="center">

![Burp Suite](https://img.shields.io/badge/Burp_Suite-00ff41?style=for-the-badge&logo=burpsuite&logoColor=0d0208&labelColor=0d0208&color=008f11)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-00ff41?style=for-the-badge&logo=owasp&logoColor=00ff41&labelColor=0d0208&color=008f11)
![Nmap](https://img.shields.io/badge/Nmap-00ff41?style=for-the-badge&logo=gnometerminal&logoColor=00ff41&labelColor=0d0208&color=008f11)
![Metasploit](https://img.shields.io/badge/Metasploit-00ff41?style=for-the-badge&logo=metasploit&logoColor=00ff41&labelColor=0d0208&color=008f11)
![SQLmap](https://img.shields.io/badge/SQLmap-00ff41?style=for-the-badge&logo=databricks&logoColor=00ff41&labelColor=0d0208&color=008f11)
![ffuf](https://img.shields.io/badge/ffuf-00ff41?style=for-the-badge&logo=fastapi&logoColor=00ff41&labelColor=0d0208&color=008f11)
![AWS](https://img.shields.io/badge/AWS_Cloud_Sec-00ff41?style=for-the-badge&logo=amazonaws&logoColor=00ff41&labelColor=0d0208&color=008f11)
![Custom Tooling](https://img.shields.io/badge/Custom_Tooling-00ff41?style=for-the-badge&logo=hackthebox&logoColor=00ff41&labelColor=0d0208&color=008f11)

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

  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=fernandobortotti&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d0208&title_color=00ff41&icon_color=008f11&text_color=00ff41"/>
  <img height="180em" src="https://streak-stats.demolab.com?user=fernandobortotti&hide_border=true&background=0d0208&stroke=008f11&ring=00ff41&fire=00ff41&currStreakLabel=00ff41&sideLabels=00ff41&dates=008f11&currStreakNum=00ff41&sideNums=00ff41&excludeDaysLabel=008f11"/>

</div>

<div align="center">

### `>` STACK

<img alt="Python" height="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg">&nbsp;&nbsp;
<img alt="JavaScript" height="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg">&nbsp;&nbsp;
<img alt="TypeScript" height="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg">&nbsp;&nbsp;
<img alt="Node.js" height="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg">&nbsp;&nbsp;
<img alt="React" height="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg">&nbsp;&nbsp;
<img alt="HTML5" height="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg">&nbsp;&nbsp;
<img alt="AWS" height="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-original-wordmark.svg">&nbsp;&nbsp;
<img alt="Linux" height="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg">

</div>

---

## `>` CONTACT // uplink

<div align="center">

<a href="https://fernandobortotti.github.io/artigos/"><img src="https://img.shields.io/badge/BLOG-artigos-00ff41?style=for-the-badge&logo=githubpages&logoColor=0d0208&labelColor=00ff41&color=008f11" /></a>
<a href="https://www.cve.org/CVERecord/SearchResults?query=bortotti"><img src="https://img.shields.io/badge/CVEs-cve.org-00ff41?style=for-the-badge&logo=commonworkflowlanguage&logoColor=00ff41&labelColor=0d0208&color=008f11" /></a>
<a href="https://github.com/fernandobortotti"><img src="https://img.shields.io/badge/GitHub-fernandobortotti-00ff41?style=for-the-badge&logo=github&logoColor=00ff41&labelColor=0d0208&color=008f11" /></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff41,50:008f11,100:0d0208&height=120&section=footer&text=%2F%2F%20follow%20the%20white%20rabbit%20//%20break%20things%20//%20report%20responsibly&fontColor=00ff41&fontSize=14&fontAlignY=70" alt="footer"/>

</div>
