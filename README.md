<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<style>
  @media print { .no-print { display: none !important; } }
  @page { margin: 12mm 14mm; size: A4; }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    font-family: 'Segoe UI', Arial, Helvetica, sans-serif;
    font-size: 8.2pt;
    line-height: 1.35;
    color: #1a1a1a;
    width: 210mm;
    min-height: 297mm;
    padding: 12mm 14mm;
    background: #fff;
  }
  h1 { font-size: 16pt; font-weight: 700; color: #111; margin-bottom: 1px; }
  .contact { font-size: 8pt; color: #444; margin-bottom: 8px; }
  .contact span { margin-right: 6px; }
  .divider { border: none; border-top: 1.5px solid #111; margin: 5px 0; }
  h2 {
    font-size: 8.5pt;
    text-transform: uppercase;
    letter-spacing: 1.2px;
    color: #111;
    margin-bottom: 3px;
    font-weight: 700;
  }
  .section { margin-bottom: 6px; }
  .summary { text-align: justify; }
  .skills-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 2px 14px; }
  .skill-item b { font-weight: 600; }
  .job { margin-bottom: 4px; }
  .job-header { display: flex; justify-content: space-between; align-items: baseline; }
  .job-title { font-weight: 700; font-size: 8.4pt; }
  .job-date { font-size: 7.8pt; color: #555; white-space: nowrap; }
  .job-company { font-size: 7.8pt; color: #555; font-style: italic; }
  .job ul { padding-left: 12px; margin-top: 1px; }
  .job li { margin-bottom: 0.5px; }
  .certs-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 1px 14px; }
  .cert-item { font-size: 7.8pt; }
  .cert-item::before { content: "• "; }
  .langs { font-size: 8pt; }
</style>
</head>
<body>

<button class="no-print" onclick="window.print()" style="position:fixed;top:12px;right:14px;background:#111;color:#fff;border:none;padding:8px 18px;border-radius:6px;font-size:10pt;cursor:pointer;z-index:999;font-family:inherit;">Salvar PDF</button>

<h1>Pedro Paulo Andrade Tannús</h1>
<div class="contact">
  <span>Uberlândia – MG | 25 anos</span>
  <span>•</span>
  <span>(34) 99216-1111</span>
  <span>•</span>
  <span>pedropaulotannus29@gmail.com</span>
</div>

<hr class="divider">

<div class="section">
  <h2>Resumo</h2>
  <p class="summary">Profissional multidisciplinar na interseção entre Engenharia de Software, Cibersegurança e Negócios. Experiência no ciclo completo de desenvolvimento (Java/Spring Boot, JavaScript, Python, AWS, Docker), com forte foco em SecOps e automação de processos. Bagagem sólida em gestão comercial — já liderou equipes e gerenciou contratos de médio e grande porte em nível nacional. Vivência internacional (EUA, Europa e Oriente Médio) e inglês fluente.</p>
</div>

<hr class="divider">

<div class="section">
  <h2>Competências Técnicas</h2>
  <div class="skills-grid">
    <div class="skill-item"><b>Cibersegurança & SecOps</b> — Identificação e mitigação de vulnerabilidades, troubleshooting, forense, remoção de malwares, hardening e Secure by Design.</div>
    <div class="skill-item"><b>Cloud & DevOps</b> — AWS (EC2, RDS, S3, SNS, API Gateway), Git, Docker, Linux, pipelines de deploy. Monitoramento e logging (Prometheus, Grafana).</div>
    <div class="skill-item"><b>Desenvolvimento Full Stack</b> — JavaScript, Java/Spring Boot, Python, PHP, HTML/CSS. API-First, REST APIs, JSON. SQL (MySQL, PostgreSQL) e NoSQL.</div>
    <div class="skill-item"><b>Automação & Integrações</b> — Fluxos com n8n e Python, Webhooks, HTTP, agentes de IA para decisão automatizada.</div>
  </div>
  <div style="margin-top:2px;"><b>Design & Produto</b> — Figma, Adobe (Photoshop, Illustrator, InDesign), prototipação de alta fidelidade, Design Systems, pesquisa de UX.</div>
</div>

<hr class="divider">

<div class="section">
  <h2>Experiência Profissional</h2>

  <div class="job">
    <div class="job-header">
      <span class="job-title">Analista de Sistemas e Automação</span>
      <span class="job-date">2026 – Atual</span>
    </div>
    <div class="job-company">BRK Comércio e Vestuário — Uberlândia/MG</div>
    <ul>
      <li>Gerenciou infraestrutura em nuvem (AWS) com foco em proteção e integridade de dados.</li>
      <li>Arquitetou integrações com n8n e Python conectando múltiplos sistemas e APIs, reduzindo falhas operacionais.</li>
      <li>Desenvolveu interfaces Full Stack para validação de regras de negócio antes do deploy.</li>
    </ul>
  </div>

  <div class="job">
    <div class="job-header">
      <span class="job-title">Product Manager e Designer Sênior</span>
      <span class="job-date">2024 – 2025</span>
    </div>
    <div class="job-company">Mundo dos Ferros / Robusfer — Palmas/TO</div>
    <ul>
      <li>Definiu roadmap de produtos alinhando diretoria, fornecedores e equipes de desenvolvimento.</li>
      <li>Liderou pesquisa de UX e design de UI, garantindo consistência visual em todos os canais da marca.</li>
      <li>Conduziu negociações de importação com fornecedores chineses e homologação junto a órgãos reguladores.</li>
    </ul>
  </div>

  <div class="job">
    <div class="job-header">
      <span class="job-title">Sócio-proprietário e Gerente Comercial</span>
      <span class="job-date">2023</span>
    </div>
    <div class="job-company">Baluarte Design Company — Uberlândia/MG</div>
    <ul>
      <li>Estruturou planejamento estratégico e operação da empresa; liderou equipes comercial e administrativa.</li>
      <li>Conduziu fechamento de contratos de alto ticket e campanhas de marketing digital.</li>
    </ul>
  </div>

  <div class="job">
    <div class="job-header">
      <span class="job-title">Gerente Comercial</span>
      <span class="job-date">2020 – 2022</span>
    </div>
    <div class="job-company">CONEL Construtora — Uberlândia/MG</div>
    <ul>
      <li>Gerenciou equipe de três engenheiros com foco em performance e metas no setor de construção civil.</li>
      <li>Estruturou estratégia de vendas e conduziu prospecção com grandes empresas em nível nacional.</li>
    </ul>
  </div>

  <div class="job">
    <div class="job-header">
      <span class="job-title">Jovem Aprendiz</span>
      <span class="job-date">2018 – 2019</span>
    </div>
    <div class="job-company">Policard / Up Brasil — Uberlândia/MG</div>
    <ul>
      <li>Atuou na análise e otimização de fluxos operacionais e comerciais.</li>
    </ul>
  </div>
</div>

<hr class="divider">

<div class="section">
  <h2>Formação</h2>
  <p>Direito (trancado) – ESAMC, Uberlândia/MG — 2023</p>
</div>

<hr class="divider">

<div class="section">
  <h2>Certificações Relevantes</h2>
  <div class="certs-grid">
    <div class="cert-item">Cisco Cybersecurity Complete (120h)</div>
    <div class="cert-item">Microsserviços com Spring Boot – Alura (80h)</div>
    <div class="cert-item">Preparatório CompTIA Security+ (40h)</div>
    <div class="cert-item">Python: Análise de Dados e Backend (57,5h)</div>
    <div class="cert-item">Preparatório AWS Solutions Architect Associate (30h)</div>
    <div class="cert-item">n8n Certified Workflow Creator (15h)</div>
    <div class="cert-item">Docker Mastery: Kubernetes e Swarm (21h)</div>
    <div class="cert-item">UI/UX and Product Design: UI Master Course (287h)</div>
  </div>
</div>

<hr class="divider">

<div class="section">
  <h2>Idiomas</h2>
  <p class="langs"><b>Português:</b> Nativo &nbsp;|&nbsp; <b>Inglês:</b> Fluente</p>
</div>

</body>
</html><img width="100%" src="./space-banner.svg"/>

<div align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&color=00F9F0&size=42&center=true&vCenter=true&width=1000&lines=Olá,+eu+sou+o+Pedro!+👋🏻;Desenvolvedor+e+Especialista+em+Automação;Criador+de+Soluções+Inovadoras" alt="Typing SVG" /></a>
</div>

## 🚀 Sobre Mim

Profissional multidisciplinar na interseção entre **Engenharia de Software, Cibersegurança e Negócios**. Experiência no ciclo completo de desenvolvimento e com forte foco em SecOps e automação de processos. Vivência com infraestrutura em nuvem, gestão comercial e liderança de equipes.

## 💻 Linguagens Principais Usadas:

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## ⚙️ Linguagens e Ferramentas que já trabalhei:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-%23EA4F4F.svg?style=for-the-badge&logo=n8n&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-%23000000.svg?style=for-the-badge&logo=security&logoColor=white)

## 📘 Estatísticas do GitHub:

<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=pedropauloat-sys&show_icons=true&theme=dark&rank_icon=github&icon_color=00F9F0&text_color=FFFFFF&title_color=00F9F0&bg_color=050a15"
    media="(prefers-color-scheme: dark)"
  />
  <img src="https://github-readme-stats.vercel.app/api?username=pedropauloat-sys&show_icons=true&theme=dark&rank_icon=github&icon_color=00F9F0&text_color=FFFFFF&title_color=00F9F0&bg_color=050a15" />
</picture>

## 🏆 Projeto Destaque:

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=pedropauloat-sys&repo=chatwoot-participating-inbox&theme=dark&bg_color=050a15&title_color=00F9F0&icon_color=00F9F0&text_color=FFFFFF)](https://github.com/pedropauloat-sys/chatwoot-participating-inbox)

## ✉️ Contatos:

[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-paulo-andrade-tannus/)
[![E-mail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pedropaulotannus29@gmail.com)
