<div align="center">

# noon presenter

### Generate and edit beautiful documents and decks with AI — locally, on your own Claude account.

![macOS](https://img.shields.io/badge/macOS-Apple%20Silicon%20%26%20Intel-000?logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-10%20%26%2011-0078D6?logo=windows&logoColor=white)
![Access](https://img.shields.io/badge/access-invited%20collaborators-6E56CF)

**[⬇️ Download the latest version](https://github.com/fk-noon/noon-presenter-dist/releases/latest)**

</div>

---

**noon presenter** is an AI‑native studio for documents and presentations. Describe what you want — a board memo, an all‑hands deck, an investor update, a one‑pager — and it builds it in your house style. Open something you already have, **select any part, type a prompt, and watch Claude (Opus 4.8) rewrite it in place** — streaming, with a *Keep / Discard* review before anything sticks. It's like having a design‑literate co‑author for everything you write.

It runs **entirely on your own machine** against **your own Claude account**. Nothing is hosted, no data leaves your computer except the calls to Claude, and there's no shared key to hand out.

> [!IMPORTANT]
> **Access is limited to invited collaborators.** You're seeing this because you've been granted access — sign in to GitHub to download. This repository hosts the installers only; the application source code is private.

---

## ⬇️ Download & install

Grab the latest build from the **[Releases page](https://github.com/fk-noon/noon-presenter-dist/releases/latest)** and pick the file for your system:

| Your system | File to download |
|---|---|
| **macOS** — Apple Silicon (M1–M4) | `noon-presenter-<version>-arm64.dmg` |
| **macOS** — Intel | `noon-presenter-<version>-x64.dmg` |
| **Windows** 10 / 11 | `noon-presenter-<version>-x64.exe` |

> Not sure which Mac you have?  → Apple menu  → **About This Mac**. "Apple M1/M2/M3/M4…" means **Apple Silicon**; "Intel" means **Intel**.

**macOS**
1. Open the downloaded `.dmg`.
2. Drag **noon presenter** into your **Applications** folder.
3. Launch it from Applications. It opens straight away — the app is **code‑signed and notarized by Apple**, so there's no security warning.

**Windows**
1. Run the downloaded `.exe` installer.
2. If Windows SmartScreen appears, click **More info → Run anyway** (the app isn't Windows‑code‑signed yet).

That's it — no Node, no terminal, no dependencies to install. The app bundles everything it needs.

## 🔑 One‑time setup: sign in to Claude

noon presenter uses **your** Claude account to do its work, so it needs a Claude sign‑in. The easiest way:

1. Install **[Claude Code](https://www.anthropic.com/claude-code)** and run `claude` once to sign in (this bills your existing Claude subscription).
2. Open noon presenter — it picks up that sign‑in automatically. Done.

The app reads your local Claude Code session; **no API key to copy or manage**. (Advanced users can set an `ANTHROPIC_API_KEY` instead.) If no sign‑in is found, the app shows a friendly prompt with a link to get set up.

## 🔄 Getting new versions

When a new version ships, you'll be told where to grab it. To update:

1. Come back to the **[Releases page](https://github.com/fk-noon/noon-presenter-dist/releases/latest)** and download the newest installer.
2. **macOS:** open the `.dmg` and drag **noon presenter** into Applications, replacing the old one. **Windows:** run the new installer.
3. Your documents and settings are kept — they live in your user folder, not inside the app.

> Because access is restricted to invited collaborators, the app does **not** auto‑update — that's deliberate. Grabbing the latest from the Releases page takes a few seconds.

---

## ✨ What you can do

- **Generate from a prompt** — "a board memo on Q3 reforecast" or "an all‑hands deck on the new roadmap" → a complete, on‑brand document you can edit.
- **Edit in place** — select any element (or drag a box around an area), type what you want changed, and watch it rewrite live. Keep it or discard it.
- **Bring your own documents** — open an HTML file, or drop in a **PDF / Word‑style text** and have it reflowed into a memo, one‑pager, or slide deck.
- **Stay on brand** — a built‑in **design system** and **brand voice** keep every document consistent; load your own tokens, style guides, and gold‑standard examples.
- **Charts & tables that do the math** — describe the data ("set May orders to 70") and the figures recompute and re‑render, verified — not hallucinated.
- **Present** — full‑screen presentation mode for decks, with recording.
- **Export** — PDF, Word (`.docx`), Markdown, or a self‑contained HTML bundle.
- **Refine, undo, compare** — nudge any change ("shorter", "less hype"), full undo/redo, and a word‑level diff of what changed.
- **A chat assistant + reusable presets** — drive the whole document from a chat sidebar, or run one‑click team commands (Punchier · Tighten · Translate…).

Everything renders in a clean, dark‑first editor. Your documents keep their own look — the app never re‑themes what you're working on.

---

## 🔒 Privacy & how it works

noon presenter is a small local application: it runs a server on your own machine and opens the editor in its own window. Your documents are stored **locally**, and the only thing that leaves your computer is the request to **Claude** (Anthropic) to generate or transform content — billed to your own account. There's no noon presenter cloud, no telemetry, and no shared credentials.

---

## 🆘 Troubleshooting

- **"Transforms aren't working / it asks me to sign in."** Install [Claude Code](https://www.anthropic.com/claude-code) and run `claude` to sign in, then reopen the app.
- **macOS: "noon presenter is damaged / can't be opened."** This is almost always because the `.dmg` didn't finish downloading — re‑download from the [Releases page](https://github.com/fk-noon/noon-presenter-dist/releases/latest) and try again.
- **Windows: SmartScreen warning.** Click **More info → Run anyway**. The app is safe; it just isn't Windows‑code‑signed yet.
- **Something else?** Open an issue on this repository.

---

<div align="center">
<sub>Built with <a href="https://www.anthropic.com/claude">Claude</a> · macOS builds are signed &amp; notarized by Apple · Private distribution for invited collaborators</sub>
</div>
