<div align="center">

  <!-- Banner (opcional) -->
  <img src="assets/banner.png" alt="Banner do perfil" width="100%" />

  <h1>Olá, eu sou <strong>Arthur Aparecido dos santos custódio</strong> 👋</h1>
  <p>Desenvolvedor • Web •</p>

  <!-- Badges -->
  <a href="mailto:arthurapcraft2@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contato-informational?style=for-the-badge&logo=gmail" alt="Email Badge">
  </a>
  <a href="https://www.linkedin.com/in/seu-usuario/">
    <img src="https://img.shields.io/badge/LinkedIn-Conectar-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn Badge">
  </a>
  <a href="https://seusite.dev">
    <img src="https://img.shields.io/badge/Portfólio-Online-success?style=for-the-badge&logo=vercel" alt="Portfolio Badge">
  </a>

</div>

---

## Sobre mim
- 🔭 Atualmente estudando em: **Instituto Proa e ensino medio**
- 🌱 Estudando: **Tecnologias** (ex.: HTML, CSS, Javacript)
- 💬 Pergunte-me sobre: **JavaScript, APIs REST, boas práticas**
- 🎯 Objetivo: **Contribuir com projetos e construir produtos úteis**

---

## Stack & Ferramentas

<!-- Ícones do Devicon (carregados via CDN) -->
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JS" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" height="40" />
</p>

---

## Galeria (Projetos / Arte em Pixel / Prints)

<!--
Coloque suas imagens em assets/ do seu repositório.
Ex.: assets/projeto1.png, assets/projeto2.gif, etc.
Use <img> para controlar tamanho e alinhar com tabelas.
-->

<!-- Grade 3 colunas -->
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/seu-usuario/projeto-1">
        <img src="assets/projeto1.png" alt="Projeto 1" width="250"><br>
        <sub><b>Projeto 1 — API REST</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/seu-usuario/projeto-2">
        <img src="assets/projeto2.gif" alt="Projeto 2" width="250"><br>
        <sub><b>Projeto 2 — App React</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/seu-usuario/projeto-3">
        <img src="assets/projeto3.png" alt="Projeto 3" width="250"><br>
        <sub><b>Projeto 3 — Pixel Art</b></sub>
      </a>
    </td>
  </tr>
</table>

---

## Destaques

- 🚀 **Nome do Projeto** — breve descrição do que faz e por que é legal.
- 🧩 **Biblioteca/Plugin** — o que resolve, link para repo.
- 🛠 **Snippet** favorito:
```js
// Exemplo: Hook para buscar dados com cache simples
import { useEffect, useState } from "react";

export function useFetch(url) {
  const [data, setData] = useState(null);
  useEffect(() => {
    let mounted = true;
    fetch(url).then(r => r.json()).then(d => mounted && setData(d));
    return () => { mounted = false; };
  }, [url]);
  return data;
}
