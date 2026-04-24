# competitive-programming-templates

> Reusable starter templates for competitive programming across twelve languages. Clean scaffolds, consistent structure and fast setup for LeetCode, Codeforces and NeetCode.

<p align="center">
  <a href="https://isaacadjei.me">
    <img src="https://img.shields.io/badge/Portfolio-isaacadjei.me-000000?style=for-the-badge&logo=googlechrome&logoColor=06ffa5" alt="Portfolio badge" />
  </a>
  <a href="https://www.linkedin.com/in/isaacadjei">
    <img src="https://img.shields.io/badge/LinkedIn-Isaac_Adjei-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn badge" />
  </a>
  <a href="mailto:contact@zacess.com">
    <img src="https://img.shields.io/badge/Email-Contact-ff6f61?style=for-the-badge&logo=gmail&logoColor=white" alt="Email badge" />
  </a>
</p>

This repository contains reusable starter templates for solving competitive programming problems across multiple languages. Each template is a minimal, clean scaffold designed to remove setup friction and let you focus on problem solving from the first line.

**12 languages. One consistent structure. Zero setup overhead.**

---

## Overview

Templates are the foundation of a consistent competitive programming workflow. Rather than recreating boilerplate every session, each language folder provides a ready-to-use starting point that matches the structure used in the main competitive-programming repository.

Every template is kept intentionally minimal. No unnecessary abstractions, no framework-specific patterns and no generated noise. Just clean source files that are ready to copy and solve.

---

## Templates Purpose

Each language folder provides:

- a hello world reference file to verify the environment works
- a neutral starter entry file to begin solving from immediately
- a language-specific `.gitignore` for common generated output
- a local `README.md` with build or run instructions
- build placeholders where compiled languages require them

The goal is to reduce the time between opening a new problem and writing the first meaningful line of code.

---

## Supported Languages

<div align="center">

| <img src="https://techstack-generator.vercel.app/python-icon.svg" width="65" alt="Python icon" /> | <img src="https://techstack-generator.vercel.app/cpp-icon.svg" width="65" alt="C++ icon" /> | <img src="https://techstack-generator.vercel.app/java-icon.svg" width="65" alt="Java icon" /> | <img src="https://techstack-generator.vercel.app/js-icon.svg" width="65" alt="JavaScript icon" /> | <img src="https://techstack-generator.vercel.app/ts-icon.svg" width="65" alt="TypeScript icon" /> | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="65" alt="Go icon" /> |
| :-----------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------: |
|                                            **Python**                                             |                                           **C++**                                           |                                           **Java**                                            |                                          **JavaScript**                                           |                                          **TypeScript**                                           |                                                    **Go**                                                    |

| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" width="65" alt="Rust icon" /> | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="65" alt="C icon" /> | <img src="https://techstack-generator.vercel.app/csharp-icon.svg" width="65" alt="C sharp icon" /> | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" width="65" alt="Kotlin icon" /> | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/swift/swift-original.svg" width="65" alt="Swift icon" /> | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="65" alt="PHP icon" /> |
| :----------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------: |
|                                                      **Rust**                                                      |                                                   **C**                                                   |                                               **C#**                                               |                                                        **Kotlin**                                                        |                                                       **Swift**                                                       |                                                     **PHP**                                                     |

</div>

---

## Structure

<details>
<summary><b>Click to expand the directory tree</b></summary>

```text
competitive-programming-templates/
├── python/
│   ├── hello_world.py
│   ├── main.py
│   ├── .gitignore
│   └── README.md
├── cpp/
│   ├── hello_world.cpp
│   ├── main.cpp
│   ├── .gitignore
│   └── README.md
├── java/
│   ├── HelloWorld.java
│   ├── src/
│   │   └── Main.java
│   ├── .gitignore
│   └── README.md
├── javascript/
│   ├── hello_world.js
│   ├── main.js
│   ├── .gitignore
│   └── README.md
├── typescript/
│   ├── hello_world.ts
│   ├── main.ts
│   ├── .gitignore
│   └── README.md
├── go/
│   ├── hello_world.go
│   ├── main.go
│   ├── .gitignore
│   └── README.md
├── rust/
│   ├── main.rs
│   ├── .gitignore
│   └── README.md
├── c/
│   ├── hello_world.c
│   ├── main.c
│   ├── .gitignore
│   └── README.md
├── csharp/
│   ├── Program.cs
│   ├── .gitignore
│   └── README.md
├── kotlin/
│   ├── HelloWorld.kt
│   ├── Main.kt
│   ├── .gitignore
│   └── README.md
├── swift/
│   ├── hello_world.swift
│   ├── main.swift
│   ├── .gitignore
│   └── README.md
└── php/
    ├── hello_world.php
    ├── main.php
    ├── .gitignore
    └── README.md
```

</details>

---

## Usage

1. Navigate to the language folder that matches your target language.
2. Copy the contents into your solution folder or use `main.*` as your starting file.
3. Follow the language-specific `README.md` for build and run instructions.
4. Start solving.

Each `main.*` file is intentionally blank or minimal so it can be used as a neutral entry point without modification. The `hello_world.*` file confirms the language toolchain is working correctly.

---

## Why This Exists

- Removes repeated setup time across problems and sessions.
- Keeps template quality consistent across all twelve languages.
- Separates reusable scaffolding from the solved problem archive.
- Works with VS Code, JetBrains IDEs and terminal-only workflows.
- Mirrors the structure of the main competitive-programming repository for easy cross-reference.

---

<div align="center">

<br />

Made with 💻 by [Isaac Adjei (Zaccess)](https://zacess.com)

<br />

[![isaacadjei.me](https://img.shields.io/badge/isaacadjei.me-000000?style=for-the-badge)](https://isaacadjei.me)
[![zacess.com](https://img.shields.io/badge/zacess.com-000000?style=for-the-badge)](https://zacess.com)

<br />

</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=110&section=footer" alt="Footer banner" />
</p>
