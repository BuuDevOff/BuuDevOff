<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="BuuDevOff, IT enthusiast and software developer / architect: native tools, web platforms, game tooling" src="assets/header-dark.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.youtube.com/@BuuDevOff"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-16121f?style=flat-square&logo=youtube&logoColor=FF2E88"></a>
  <a href="https://instagram.com/buudevoff"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-16121f?style=flat-square&logo=instagram&logoColor=FF2E88"></a>
  <a href="https://github.com/BuuDevOff?tab=repositories"><img alt="Repositories" src="https://img.shields.io/badge/Repositories-16121f?style=flat-square&logo=github&logoColor=FF2E88"></a>
</p>

## About me

I'm **Buu** (BuuDevOff), an IT enthusiast and software developer / architect. I wrote my first lines of code at **7**, making games in Lua and JavaScript on Garry's Mod, and never stopped. Today I build **fast native tools in Rust** and **full-stack web platforms in TypeScript**, often for gaming communities.

- 🦀 **Now:** shipping [BTMS](https://github.com/BuuDevOff/BTMS) and building **BuuDevOff.fr**, my own platform, in Rust and Next.js
- 🧠 **Into:** clean architecture, real-time systems, GPU rendering and local AI (LLMs, RAG, MCP)
- 📚 **Learning daily:** IT, code and project management
- 🎮 **Off-screen:** gaming and exploring new places

## Featured open source

### 🔍 [BUIT](https://github.com/BuuDevOff/buit) · Buu Undercover Intelligence Toolkit

<a href="https://github.com/BuuDevOff/buit"><img alt="BUIT, Buu Undercover Intelligence Toolkit" src="assets/buit.jpg" width="100%"></a>

A fast **OSINT toolkit written in Rust** for security researchers. More than 25 reconnaissance modules (username and email lookups, subdomain enumeration, IP analysis and more) in a single command-line tool, released for Windows, macOS and Linux.

<p>
  <a href="https://github.com/BuuDevOff/buit/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/BuuDevOff/buit?style=flat-square&logo=github&label=stars&color=FF2E88&labelColor=16121f"></a>
  <a href="https://github.com/BuuDevOff/buit/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/BuuDevOff/buit/total?style=flat-square&label=downloads&color=7C3AED&labelColor=16121f"></a>
  <a href="https://github.com/BuuDevOff/buit/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/BuuDevOff/buit?style=flat-square&label=release&color=7C3AED&labelColor=16121f"></a>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-16121f?style=flat-square&logo=rust&logoColor=white">
  <img alt="License: MIT" src="https://img.shields.io/github/license/BuuDevOff/buit?style=flat-square&color=16121f">
</p>

### 🗺️ [BTMS](https://github.com/BuuDevOff/BTMS) · Buu's Tiles Map Scanner

<a href="https://github.com/BuuDevOff/BTMS"><img alt="BTMS, Buu's Tiles Map Scanner" src="assets/btms.jpg" width="100%"></a>

Turns the **whole GTA V map into web map tiles**, straight from the game files on disk, with a FiveM server's unprotected map resources drawn on top. Offline and read-only, **GPU-accelerated through wgpu** (DirectX 12 or Vulkan) with a CPU fallback, re-renders only what changed, and writes a viewer page ready to upload. Comes with an installer and a local interface in 7 languages.

<p>
  <a href="https://github.com/BuuDevOff/BTMS/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/BuuDevOff/BTMS?style=flat-square&label=release&color=FF2E88&labelColor=16121f"></a>
  <a href="https://github.com/BuuDevOff/BTMS/actions/workflows/ci.yml"><img alt="CI" src="https://img.shields.io/github/actions/workflow/status/BuuDevOff/BTMS/ci.yml?branch=main&style=flat-square&label=CI&labelColor=16121f"></a>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-16121f?style=flat-square&logo=rust&logoColor=white">
  <img alt="WebGPU" src="https://img.shields.io/badge/wgpu-16121f?style=flat-square&logo=webgpu&logoColor=white">
  <img alt="License: GPL-3.0" src="https://img.shields.io/github/license/BuuDevOff/BTMS?style=flat-square&color=16121f">
</p>

### 🤝 Contributions

- [**Deformation-Addon**](https://github.com/Ty4a925/Deformation-Addon/pull/2): added the French translation (merged). A Garry's Mod addon in Lua, where it all started for me.

## Selected private work

Most of my day-to-day work lives in private repositories, built for teams and communities. A few highlights:

- **Community platforms** · *2026 · 500+ commits*<br>
  Two full-stack apps for Garry's Mod roleplay communities. React, Vite and Tailwind on the front end; Node and Express with binary RPC over WebSocket (MessagePack), Prisma, Discord OAuth2 and a Discord bot on the back end. The latest one adds a local LLM assistant (llama.cpp) with hybrid RAG, meeting transcription, an MCP server and Web Push.
- **Multi-bot Discord manager** · *2024 – 2025 · 400+ commits*<br>
  Runs many Discord bots from one place: TypeScript, discord.js 14, TypeORM and MySQL, AES-256 encrypted token storage, bitwise permissions, and an Angular 19 PWA dashboard.
- **BuuDevOff.fr** · *2026 · in progress*<br>
  My personal brand and agency platform: a Rust monorepo (axum, tokio) with a hexagonal core, an in-process event bus and SurrealDB live queries, a Next.js front end in English, French and Dutch, shipped with Docker Compose, Caddy and GitHub Actions.
- **FiveM roleplay framework** · *2023*<br>
  A custom TypeScript framework for a GTA V roleplay server.

## Tech stack

<p align="center">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-16121f?style=for-the-badge&logo=rust&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-16121f?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-16121f?style=for-the-badge&logo=javascript&logoColor=white">
  <img alt="Lua" src="https://img.shields.io/badge/Lua-16121f?style=for-the-badge&logo=lua&logoColor=white">
  <img alt="C#" src="https://img.shields.io/badge/C%23-16121f?style=for-the-badge&logo=dotnet&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-16121f?style=for-the-badge&logo=python&logoColor=white">
  <img alt="PHP" src="https://img.shields.io/badge/PHP-16121f?style=for-the-badge&logo=php&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-16121f?style=for-the-badge&logo=openjdk&logoColor=white">
  <br>
  <img alt="React" src="https://img.shields.io/badge/React-16121f?style=for-the-badge&logo=react&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-16121f?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img alt="Angular" src="https://img.shields.io/badge/Angular-16121f?style=for-the-badge&logo=angular&logoColor=white">
  <img alt="Vite" src="https://img.shields.io/badge/Vite-16121f?style=for-the-badge&logo=vite&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-16121f?style=for-the-badge&logo=tailwindcss&logoColor=white">
  <img alt="Three.js" src="https://img.shields.io/badge/Three.js-16121f?style=for-the-badge&logo=threedotjs&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-16121f?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img alt="Express" src="https://img.shields.io/badge/Express-16121f?style=for-the-badge&logo=express&logoColor=white">
  <br>
  <img alt="Tokio" src="https://img.shields.io/badge/Tokio-16121f?style=for-the-badge&logo=tokio&logoColor=white">
  <img alt="wgpu" src="https://img.shields.io/badge/wgpu-16121f?style=for-the-badge&logo=webgpu&logoColor=white">
  <img alt="SurrealDB" src="https://img.shields.io/badge/SurrealDB-16121f?style=for-the-badge&logo=surrealdb&logoColor=white">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-16121f?style=for-the-badge&logo=mysql&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-16121f?style=for-the-badge&logo=sqlite&logoColor=white">
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-16121f?style=for-the-badge&logo=prisma&logoColor=white">
  <img alt="TypeORM" src="https://img.shields.io/badge/TypeORM-16121f?style=for-the-badge&logo=typeorm&logoColor=white">
  <img alt="discord.js" src="https://img.shields.io/badge/discord.js-16121f?style=for-the-badge&logo=discorddotjs&logoColor=white">
  <br>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-16121f?style=for-the-badge&logo=docker&logoColor=white">
  <img alt="Caddy" src="https://img.shields.io/badge/Caddy-16121f?style=for-the-badge&logo=caddy&logoColor=white">
  <img alt="Nginx" src="https://img.shields.io/badge/Nginx-16121f?style=for-the-badge&logo=nginx&logoColor=white">
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-16121f?style=for-the-badge&logo=cloudflare&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-16121f?style=for-the-badge&logo=githubactions&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-16121f?style=for-the-badge&logo=linux&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-16121f?style=for-the-badge&logo=git&logoColor=white">
</p>

## GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=BuuDevOff&hide_border=true&background=00000000&ring=FF2E88&fire=FF2E88&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=FF2E88&sideLabels=D9D4E7&dates=9A93AD&stroke=3B3550">
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=BuuDevOff&hide_border=true&background=00000000&ring=D1146A&fire=D1146A&currStreakNum=14101F&sideNums=14101F&currStreakLabel=D1146A&sideLabels=3B3550&dates=5B5670&stroke=E9E3F1">
    <img alt="GitHub contribution streak" src="https://streak-stats.demolab.com?user=BuuDevOff&hide_border=true&background=00000000&ring=FF2E88&fire=FF2E88&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=FF2E88&sideLabels=D9D4E7&dates=9A93AD&stroke=3B3550">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/BuuDevOff/BuuDevOff/output/snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/BuuDevOff/BuuDevOff/output/snake-light.svg">
    <img alt="Contribution graph eaten by a snake" src="https://raw.githubusercontent.com/BuuDevOff/BuuDevOff/output/snake-dark.svg" width="100%">
  </picture>
</p>

---

<p align="center">
  If one of my tools helped you, a ⭐ on its repository goes a long way.
  <br><br>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=BuuDevOff&label=Profile%20views&color=FF2E88&style=flat-square">
</p>
