<h1 align="center">Hi, I'm Ayush 👋</h1>
<p align="center">
  🎓 Student by day · 🛠️ Open source contributor by night · Love messing with systems
</p>
<p align="center">
  <a href="https://x.com/chernobyll11"><img src="https://img.shields.io/badge/X-@chernobyll11-000000?style=flat&logo=x"></a>
  <a href="https://github.com/Ayush442842q"><img src="https://img.shields.io/badge/GitHub-Ayush442842q-181717?style=flat&logo=github"></a>
</p>

---

### About Me
- 🎓 Currently studying, and building things on the side
- 🌱 Contributing to open source projects I actually use
- 🦀 Learning to think in Rust, 🐍 shipping fast in Python, ⚡ scripting the web in TypeScript/JavaScript
- 🔧 I like tools that get out of your way — CLIs, GUIs for things that shouldn't need a browser, and anything that saves a few keystrokes

### 🔭 Currently Building
**[PenguinGit](https://github.com/Ayush442842q/Penguin-Git)** — a powerful, open-source Git GUI built exclusively for Linux. Visual commit graph, interactive rebasing, visual merge conflict resolution, and repo management, all without leaving the desktop.

**[PenguinGit Lens](https://github.com/labs-ayush/PenguinGit-lens)** — a lightweight, open-source VS Code extension and 100% free GitLens alternative. Inline blame, rich commit hover cards, a visual commit graph panel, and file revision history, powered by the local PenguinGit Engine daemon over JSON-RPC/MCP — with deep-link handoff into the PenguinGit desktop app for interactive rebase and 3-way merge conflict resolution.

### 🛠️ Projects Built
**[Claude-app-for-Fedora](https://github.com/Ayush442842q/Claude-app-for-Fedora)** - Repacked the Anthropic's official `.deb` package into `rpm` so fedora and other RPM based flavors.

### 🌱 Open Source Contributions

**Key contributions to [pnpm/pnpm](https://github.com/pnpm/pnpm):**

| PR | What it did |
|---|---|
| [#13714](https://github.com/pnpm/pnpm/pull/13714) | Fixed nondeterministic dependency resolution order in pacquet's Rust resolver |
| [#13604](https://github.com/pnpm/pnpm/pull/13604) | Enforced `dryRun: true` in the resolver for check-only installs, preventing silent `node_modules` mutation |
| [#13402](https://github.com/pnpm/pnpm/pull/13402) | Fixed `pnpm update --latest` leaving named-registry/JSR dependencies at old versions |
| [#13124](https://github.com/pnpm/pnpm/pull/13124) | Fixed `peerDependencies` incorrectly overriding real dependency version precedence |
| [#13541](https://github.com/pnpm/pnpm/pull/13541) | Preserved percent-encoded slashes in registry tarball URLs in lockfiles |
| [#13719](https://github.com/pnpm/pnpm/pull/13719) | Prevented `blockExoticSubdeps` from incorrectly remapping internal workspace `link:` dependencies |
| [#13411](https://github.com/pnpm/pnpm/pull/13411) | Fixed POSIX shell shims breaking when invoked via external symlinks |
| [#14013](https://github.com/pnpm/pnpm/pull/14013) | Prevented frozen installs from rewriting `packageManagerDependencies` in the lockfile |

<details>
<summary>See all merged PRs to pnpm/pnpm (24)</summary>

| PR | What it did |
|---|---|
| [#14013](https://github.com/pnpm/pnpm/pull/14013) | Prevented frozen installs from rewriting `packageManagerDependencies` in `pnpm-lock.yaml` |
| [#13998](https://github.com/pnpm/pnpm/pull/13998) | Fixed Windows code page query in `pacquet` by resolving `chcp.com` explicitly |
| [#13997](https://github.com/pnpm/pnpm/pull/13997) | Fixed `pnpm init` outputting caret ranges in `devEngines.packageManager.version`, breaking Corepack |
| [#13993](https://github.com/pnpm/pnpm/pull/13993) | Recognized dotted `--config.<key>=<value>` CLI overrides in pacquet (Rust CLI) |
| [#13938](https://github.com/pnpm/pnpm/pull/13938) | Cloned package manifests in `createVersionsOverrider` to prevent overrides cache pollution |
| [#13937](https://github.com/pnpm/pnpm/pull/13937) | Fixed `pnpm self-update` leaving stale `pnpm.ps1` shims on Windows |
| [#13917](https://github.com/pnpm/pnpm/pull/13917) | Cleaned up invalid/pending `allowBuilds` entries in `pnpm-workspace.yaml` during `pnpm rm` |
| [#13916](https://github.com/pnpm/pnpm/pull/13916) | Resolved mtime-tick collision in repeat-install fast path forcing full content checks |
| [#13738](https://github.com/pnpm/pnpm/pull/13738) | Resolved discrepancy between version-policy Evaluator runtime matcher and Normalizer |
| [#13737](https://github.com/pnpm/pnpm/pull/13737) | Normalized bare string array fields in `trustPolicyExclude`/`minimumReleaseAgeExclude` config |
| [#13724](https://github.com/pnpm/pnpm/pull/13724) | Prevented `pnpm prune --prod` in workspace root from deleting nested workspace symlinks |
| [#13719](https://github.com/pnpm/pnpm/pull/13719) | Prevented `blockExoticSubdeps` from remapping internal workspace `link:` dependencies |
| [#13714](https://github.com/pnpm/pnpm/pull/13714) | Fixed nondeterministic dependency resolution order in pacquet Rust resolver |
| [#13604](https://github.com/pnpm/pnpm/pull/13604) | Enforced `dryRun: true` in resolver for check-only installs to prevent modifying `node_modules` |
| [#13541](https://github.com/pnpm/pnpm/pull/13541) | Preserved percent-encoded slashes (`@scope%2fname`) in registry tarball URLs in lockfiles |
| [#13411](https://github.com/pnpm/pnpm/pull/13411) | Fixed POSIX shell shims (`binstubs`) breaking when invoked via external symlinks |
| [#13402](https://github.com/pnpm/pnpm/pull/13402) | Fixed `pnpm update --latest` leaving named-registry dependencies at old versions |
| [#13291](https://github.com/pnpm/pnpm/pull/13291) | Fixed `--dry-run` flag handling in `pnpm version -r`, pinned preview output to release plan |
| [#13290](https://github.com/pnpm/pnpm/pull/13290) | Prevented recording SSH URLs for Git deps when shorthand specifiers (`github:user/repo`) are used |
| [#13222](https://github.com/pnpm/pnpm/pull/13222) | Fixed human-readable text printing during `pnpm version -r --json` with no pending changes |
| [#13124](https://github.com/pnpm/pnpm/pull/13124) | Fixed `peerDependencies` spreading when computing current package specifiers |

*→ [See every PR (open, merged, and closed)](https://github.com/pnpm/pnpm/pulls?q=is%3Apr+author%3AAyush442842q)*

</details>

### Other Projects
| Project | Description |
|---|---|
| [Groq-Based-chatbot](https://github.com/Ayush442842q/Groq-Based-chatbot) | A chatbot built on top of Groq's inference speed |
| [perplexity-model-council](https://github.com/Ayush442842q/perplexity-model-council) | Experimenting with multi-model "council" style reasoning |
| [Python-tools](https://github.com/Ayush442842q/Python-tools) | A self-maintained Python toolkit |

### 🛠️ Tech I Reach For
<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black">
</p>

### 📊 GitHub Stats
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Ayush442842q&show_icons=true&theme=radical&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ayush442842q&layout=compact&theme=radical&hide_border=true" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Ayush442842q&theme=radical&hide_border=true" />
</p>

---

<p align="center"><i>Find me tinkering with terminals, Git internals, or whatever breaks next.</i></p>
