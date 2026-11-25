# Rohan Gupta

Building systems software, developer tooling, and backend applications in **TypeScript, Python, C/Win32, and Node.js**.

---

### Featured Projects

* **[REWIND](https://github.com/strangedoctor073-alt/Rewind)** — Local-first Windows activity time machine, app-level undo, and browser interaction recorder.
  * Native Win32 FFI (`Koffi`, GDI `PrintWindow`, process tracking) with null-byte sanitization and terminal `SIGTSTP` exclusion.
  * Embedded SQLite timeline in WAL mode with FTS5 search; 20-second atomic auto-saves (`.tmp` → `.wal`).
  * AES-256-GCM + PBKDF2 (600k rounds) encrypted vaults and DPAPI key protection.
  * 284 passing tests across 41 Vitest suites.

* **[AI PR Reviewer](https://github.com/strangedoctor073-alt/ai-pr-reviewer)** — GitHub Action for automated pull request review with deterministic fallback.
  * Multi-provider AI support (Claude, OpenAI, Gemini, Ollama) with automated failover.
  * In-process static AST/regex rule fallback (`mode: "static"`) for free CI plumbing runs and zero-cost testing.
  * Defensive nonce-fenced prompt isolation to prevent prompt-injection attacks from untrusted diffs.
  * Safe unified-diff line anchoring and pre-flight token/secret scrubbing.

---

### Tech Stack

* **Languages:** TypeScript, JavaScript, Python, C/Win32, SQL
* **Tools & Platforms:** Node.js, Electron, FastAPI, SQLite, GitHub Actions, Docker, Chrome Extensions (MV3), Vitest

---

### Links

* **Portfolio:** [portfolio-website-virid-three-71.vercel.app](https://portfolio-website-virid-three-71.vercel.app/)
* **Email:** [strangedoctor073@gmail.com](mailto:strangedoctor073@gmail.com)
* **GitHub:** [@strangedoctor073-alt](https://github.com/strangedoctor073-alt)
