# 月村つかさ / Tsukasa

[English](./README.en.md)

**プロダクトエンジニア — Web / macOS / 互換性レイヤー**

> **2027年入社に向けて就職活動中です。** 新卒・既卒エンジニア採用で、Web／クライアントを軸に、自社プロダクトの継続改善に関われる環境を志望しています。

利用者に届かない原因を調べ、設計・実装・検証・公開後の改善まで進めています。

現在は、Windows向けビジュアルノベルをApple Silicon Macで動作させる **Orrery** と、その調査過程を公開する **Zennでの技術発信**を中心に活動しています。

GitHubとZennでは、ペンネームの「月村つかさ」を使用しています。

---

## Orrery — WindowsビジュアルノベルをApple Silicon Macへ

Orreryは、既存のWine構成では動作しないWindows向けビジュアルノベルを、Apple Silicon Mac上で動かすための互換性プロジェクトです。

アプリを起動するだけでなく、描画・動画再生・ウィンドウ制御・32/64-bit境界などの不具合を観測し、Wine、DirectX、Rosetta 2、Metalまで原因を切り分けています。修正は再現手順と検証結果を残し、公開可能な知見をZennとCase Noteへ還元しています。

- **[swingby-wine](https://github.com/tsukasa-art/swingby-wine)** — Wine 10.0を基底とするフォーク。CでmacOS/Rosetta向け互換性修正を管理
- **[swingby-dxvk](https://github.com/tsukasa-art/swingby-dxvk)** — DXVK 2.4.1を基底とするフォーク。MoltenVK/Apple Silicon向け互換性修正を管理
- **[melammu-vn](https://github.com/tsukasa-art/melammu-vn)** — ローカルライブラリUIと汎用エンジン判定を示す、SwiftUI製の公開版
- **[Orrery overview](https://tsukasa-art.com/projects/orrery/)** — プロジェクト全体像と公開Case Note
- **[Zenn連載](https://zenn.dev/tsukasa_art/articles/mac-eroge-compat-part1)** — 調査、失敗、修正、検証の記録

`melammu-vn`は、非公開の開発本体から公開可能な範囲を切り出したsource-only版です。ゲームデータ、認証情報、配布権限を確認できないランタイム、タイトル固有の証拠は含みません。

---

## Zenn — 調査を再利用できる知識へ

**[zenn.dev/tsukasa_art](https://zenn.dev/tsukasa_art)**

Orreryで得た知見を中心に、発生した現象、立てた仮説、検証方法、失敗した経路、最終的な判断を公開しています。完成後の結論だけでなく、どの証拠から方針を変えたかまで残すことで、他の開発者が追試できる形を目指しています。

---

## 利用者へ届けたプロダクト

### [JAN Sync](https://github.com/tsukasa-art/jan-sync)

店頭でJANコードを読み取り、IndexedDBへ保存し、バーコード生成とCSV/TSV出力までローカルで行うオフラインPWAです。小売現場の作業を、通信状態に依存せず完結させるために設計しました。

**[Live demo](https://jan-sync.pages.dev/)**

### [Salon Register Demo](https://github.com/tsukasa-art/salon-register-demo)

美容サロン向けレジシステムの公開デモです。実運用データや内部コードを含めず、メニュー選択、会計、IndexedDBによるローカル保存など、利用者向けの操作体験を確認できる形に分離しています。

**[Live demo](https://salon-register-demo.pages.dev/)**

---

## ライブラリとデスクトップアプリ

### [zenpix](https://github.com/tsukasa-art/zenpix)

制約のある実行環境向けのC製画像処理エンジンです。JPEG / PNG / WebP / AVIFなどのデコード、Lanczos-3リサイズ、AVIF / WebPエンコードを提供し、Node.js・Bun・Deno・WebAssemblyから利用できます。

**[npm](https://www.npmjs.com/package/zenpix)** · **[Docs](https://zenpix.tsukasa-art.com)**

### [Teinte](https://github.com/tsukasa-art/teinte)

画像の支配色、配色、WCAGコントラスト、EXIFなどをローカルで分析するTauriデスクトップアプリです。Vue 3 / TypeScriptのUIとRustの解析処理を分離し、複数OSのCIとリリース手順を整備しています。

---

## 開発で重視していること

- 推測より先に、ログ・再現手順・実機挙動を確認する
- 技術選定を、利用者体験・運用性・再現性まで含めて判断する
- AIエージェントを利用しても、公開範囲、レビュー、検証、最終判断は人間が担う
- 変更理由、解決した問題、検証結果を後から追える形で残す

**Languages:** TypeScript / JavaScript / C / Rust / Swift

**Frameworks & UI:** React / React Router v7 / Next.js / Astro / Vue / SolidJS / Svelte / SvelteKit / SwiftUI / Tauri

**プロダクト・アプリケーション実装:** Ruby on Railsによる再構築プロトタイプ / PWA・オフラインファースト / CMS・リッチテキストエディタ（Tiptap）/ 認証・セッション管理（Oslo / Better Auth）/ PostgreSQL・Cloudflare D1 / Wine / macOS / Cloudflare

---

## Contact

採用・開発に関するご連絡は、[ポートフォリオサイト](https://tsukasa-art.com/)上部の「Contact」からお願いします。

**[Zenn](https://zenn.dev/tsukasa_art)** · **[X @tsukasaartcom](https://x.com/tsukasaartcom)**
