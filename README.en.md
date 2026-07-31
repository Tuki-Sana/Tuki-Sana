# Tsukasa / 月村つかさ

[日本語](./README.md)

**Product engineer — Web / macOS / compatibility layers**

> **Open to software engineering roles in Japan starting in 2027.** I am seeking new-graduate or early-career opportunities on product teams where I can contribute to continuous improvement, primarily through web and client engineering.

I investigate why a useful experience fails to reach its users, then work through design, implementation, verification, and post-release improvement.

My current focus is **Orrery**, a compatibility project for running Windows visual novels on Apple Silicon Macs, and the **technical writing on Zenn** that turns its investigation process into reproducible knowledge.

I publish technical work under the pen name Tsukasa / 月村つかさ.

---

## Orrery — Windows visual novels on Apple Silicon Macs

Orrery investigates application failures across Wine, DirectX, Rosetta 2, and Metal. The work covers rendering, media playback, window behavior, and 32/64-bit boundaries, with reproducible cases and verification notes kept alongside the fixes.

- **[swingby-wine](https://github.com/tsukasa-art/swingby-wine)** — Wine 10.0-based fork carrying macOS/Rosetta compatibility work in C
- **[swingby-dxvk](https://github.com/tsukasa-art/swingby-dxvk)** — DXVK 2.4.1-based fork carrying MoltenVK/Apple Silicon compatibility work
- **[melammu-vn](https://github.com/tsukasa-art/melammu-vn)** — public SwiftUI source for a local library UI and generic engine inspection
- **[Orrery overview](https://tsukasa-art.com/projects/orrery/)** — project overview and public case notes
- **[Zenn series](https://zenn.dev/tsukasa_art/articles/mac-eroge-compat-part1)** — investigation, failed approaches, fixes, and verification in Japanese

`melammu-vn` is a source-only public subset of the private development tree. It excludes game data, credentials, title-specific evidence, and runtime components whose redistribution status has not been confirmed.

---

## Technical writing — turning investigations into reproducible knowledge

**[zenn.dev/tsukasa_art](https://zenn.dev/tsukasa_art)**

I publish the phenomena I observed, hypotheses I tested, failed approaches, verification methods, and final decisions from Orrery. My goal is to make the reasoning reproducible for other developers, not just present the final result.

---

## Product delivery

- **[JAN Sync](https://github.com/tsukasa-art/jan-sync)** — offline-first retail PWA for JAN scanning, local storage, barcode generation, and CSV/TSV export. **[Live demo](https://jan-sync.pages.dev/)**
- **[Salon Register Demo](https://github.com/tsukasa-art/salon-register-demo)** — public demo of a salon register workflow, separated from private operational data and proprietary source code. **[Live demo](https://salon-register-demo.pages.dev/)**
- **[zenpix](https://github.com/tsukasa-art/zenpix)** — C image-processing engine for constrained environments, available to Node.js, Bun, Deno, and WebAssembly. **[npm](https://www.npmjs.com/package/zenpix)** · **[Docs](https://zenpix.tsukasa-art.com)**
- **[Teinte](https://github.com/tsukasa-art/teinte)** — local-first color-analysis desktop app built with Vue, TypeScript, Rust, and Tauri

---

## How I work

- Observe logs, reproduction steps, and behavior before settling on a hypothesis
- Evaluate technical choices through user experience, operations, and reproducibility
- Use AI agents with explicit review, verification, publication boundaries, and human accountability
- Describe solved problems and verifiable outcomes instead of activity counts

**Languages:** TypeScript / JavaScript / C / Rust / Swift

**Frameworks & UI:** React / React Router v7 / Next.js / Astro / Vue / SolidJS / Svelte / SvelteKit / SwiftUI / Tauri

**Product & application experience:** Ruby on Rails rebuild prototype / offline-first PWAs / CMS and rich-text editing with Tiptap / authentication and session management with Oslo and Better Auth / PostgreSQL and Cloudflare D1 / Wine / macOS / Cloudflare

---

## Contact

For recruiting or development inquiries, please use the “Contact” button on my [portfolio website](https://tsukasa-art.com/).

**[Zenn](https://zenn.dev/tsukasa_art)** · **[X @tsukasaartcom](https://x.com/tsukasaartcom)**
