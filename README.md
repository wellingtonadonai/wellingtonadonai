<!--
Banner / Header SVG + HTML for GitHub README
Save as `banner.svg` or `banner.html` and upload to your repository (e.g. in assets/).
Usage in README.md:

```md
![Banner](assets/banner.svg)
```

Dimensions: 1200x320 (adjustable)
Colors: dark navy -> teal gradient, accents in green
Font: system (fallback), uses SVG styling so it will render on GitHub
-->

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Banner - Wellington Oliveira</title>
</head>
<body>
<!-- SVG banner (1200x320) -->
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="320" viewBox="0 0 1200 320">
  <defs>
    <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0%" stop-color="#0f1724" />
      <stop offset="55%" stop-color="#072F2F" />
      <stop offset="100%" stop-color="#004E66" />
    </linearGradient>
    <filter id="softShadow" x="-50%" y="-50%" width="200%" height="200%">
      <feDropShadow dx="0" dy="8" stdDeviation="18" flood-color="#000" flood-opacity="0.45" />
    </filter>
  </defs>

  <!-- background -->
  <rect width="1200" height="320" rx="16" fill="url(#g1)" />

  <!-- left accent shape -->
  <path d="M0 0 L420 0 C520 0 480 160 420 320 L0 320 Z" fill="#001F27" opacity="0.12" />

  <!-- subtle grid lines -->
  <g opacity="0.06" stroke="#ffffff" stroke-width="1">
    <line x1="200" y1="20" x2="200" y2="300" />
    <line x1="240" y1="20" x2="240" y2="300" />
    <line x1="280" y1="20" x2="280" y2="300" />
  </g>

  <!-- Text: Name -->
  <g transform="translate(60,70)">
    <text x="0" y="0" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial" font-size="40" font-weight="700" fill="#ffffff">Wellington Oliveira</text>
    <text x="0" y="52" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial" font-size="18" fill="#B9E5D4">Desenvolvedor Back-End Java • Spring Boot • Microsserviços</text>

    <!-- tagline -->
    <text x="0" y="92" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial" font-size="14" fill="#9FCFD6">Transformando ideias em APIs escaláveis e código com qualidade</text>

    <!-- CTAs / chips -->
    <g transform="translate(0,118)">
      <rect x="0" y="0" rx="8" ry="8" width="170" height="34" fill="#052A26" stroke="#14B8A6" />
      <text x="22" y="22" font-size="12" fill="#14B8A6">Java • Spring Boot</text>

      <rect x="190" y="0" rx="8" ry="8" width="160" height="34" fill="#052A26" stroke="#60A5FA" />
      <text x="210" y="22" font-size="12" fill="#60A5FA">APIs • Microsserviços</text>

      <rect x="370" y="0" rx="8" ry="8" width="150" height="34" fill="#052A26" stroke="#10B981" />
      <text x="392" y="22" font-size="12" fill="#10B981">CI/CD • Docker</text>
    </g>
  </g>

  <!-- Right: tech icons (stylized) -->
  <g transform="translate(820,40)">
    <!-- Java cup (stylized) -->
    <g transform="translate(0,0)">
      <rect x="0" y="0" width="96" height="96" rx="12" fill="#021926" opacity="0.25" />
      <text x="48" y="56" font-size="18" text-anchor="middle" fill="#F7DF1E" font-family="monospace">☕</text>
      <text x="48" y="86" font-size="10" text-anchor="middle" fill="#BDEDE3">Java</text>
    </g>

    <!-- Spring leaf -->
    <g transform="translate(120,0)">
      <rect x="0" y="0" width="96" height="96" rx="12" fill="#021926" opacity="0.22" />
      <text x="48" y="56" font-size="22" text-anchor="middle" fill="#6EE7B7">🌿</text>
      <text x="48" y="86" font-size="10" text-anchor="middle" fill="#BDEDE3">Spring</text>
    </g>

    <!-- Docker whale -->
    <g transform="translate(240,0)">
      <rect x="0" y="0" width="96" height="96" rx="12" fill="#021926" opacity="0.20" />
      <text x="48" y="56" font-size="22" text-anchor="middle">🐳</text>
      <text x="48" y="86" font-size="10" text-anchor="middle" fill="#BDEDE3">Docker</text>
    </g>
  </g>

  <!-- footer small text -->
  <text x="60" y="300" font-size="11" fill="#7FBCC0">Wellington • Back-End Java • github.com/wellingtonadonai</text>

</svg>

</body>
</html>

## 🚀 Principais Tecnologias

<div align="center">

### 🧩 Back-End
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/Microservices-000000?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/CI/CD-000000?style=for-the-badge&logo=githubactions&logoColor=white"/>

---

### 🗄️ Banco de Dados
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>

---

### 💡 Front-End & Ferramentas
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>

</div>

---

## 📊 Estatísticas no GitHub

<div align="center">
  <a href="https://github.com/wellingtonadonai">
    <img height="170em" src="https://github-readme-stats.vercel.app/api?username=wellingtonadonai&show_icons=true&theme=radical&include_all_commits=true&count_private=true&border_radius=10&border_color=4CAF50"/>
  </a>
  <a href="https://github.com/wellingtonadonai">
    <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=wellingtonadonai&layout=compact&langs_count=8&theme=radical&border_radius=10&border_color=4CAF50"/>
  </a>
</div>

---

<p align="center">
  <em>"Transformando desafios em código e ideias em soluções reais 🚀"</em>
</p>


## 🧪 Projetos em Destaque

<div align="center">

### 🟢 APIs e Microsserviços (Java & Spring Boot)

<a href="https://github.com/wellingtonadonai/usuario">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=wellingtonadonai&repo=usuario&theme=radical&border_color=4CAF50&border_radius=10" />
</a>
<a href="https://github.com/wellingtonadonai/dscatalogSpring">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=wellingtonadonai&repo=dscatalogSpring&theme=radical&border_color=4CAF50&border_radius=10" />
</a>

---

### 🧩 Projetos de Lógica e Estudos Java

<a href="https://github.com/wellingtonadonai/SimulacaodeContaBancaria-Java">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=wellingtonadonai&repo=SimulacaodeContaBancaria-Java&theme=tokyonight&border_color=00BFFF&border_radius=10" />
</a>
<a href="https://github.com/wellingtonadonai/SistemadeValidacao-ProcessoSeletivo">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=wellingtonadonai&repo=SistemadeValidacao-ProcessoSeletivo&theme=tokyonight&border_color=00BFFF&border_radius=10" />
</a>
<a href="https://github.com/wellingtonadonai/Jogo-Ping-Pong">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=wellingtonadonai&repo=Jogo-Ping-Pong&theme=tokyonight&border_color=00BFFF&border_radius=10" />
</a>

</div>

---

## 🛠️ Objetivo Profissional

🎯 **Desenvolvedor Back-End Java** focado em criar APIs REST escaláveis com **Spring Boot**, aplicando princípios de **Clean Code, SOLID e arquitetura de microsserviços**.

🚀 Busco oportunidades para **evoluir em projetos desafiadores**, contribuindo com código de qualidade e boas práticas de engenharia de software.

---


### 📬 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/wellingtonoliveira-dev/)
[![WhatsApp](https://img.shields.io/badge/Whatsapp-25D366?style=for-the-badge\&logo=whatsapp\&logoColor=white)](https://wa.me/5517992845056)

---

✨ *"Código é mais do que lógica — é a arte de transformar problemas em soluções."*
