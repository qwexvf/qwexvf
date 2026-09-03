<p>
  <img alt="Gleam" src="https://img.shields.io/badge/Gleam-FFAFF3?style=flat-square&logo=gleam&logoColor=000">
  <img alt="Erlang" src="https://img.shields.io/badge/Erlang-A90533?style=flat-square&logo=erlang&logoColor=fff">
  <img alt="Elixir" src="https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=fff">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=fff">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=fff">
  <img alt="Neovim" src="https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=fff">
</p>

Backend engineer in Tokyo. BEAM person — Erlang, Elixir, and mostly **Gleam** these days.
When the BEAM is the wrong tool, Rust or Go.

Mostly I just like trying things. A new language, a new runtime, a tool I'm not sure I need —
I'd rather build something small with it than read about it. Most of those stay experiments.
The ones below stuck around: a GraphQL server for Gleam, codegen for specs, a job queue,
a code-intelligence engine, a supply-chain scanner.

<details open>
<summary><b>Gleam</b></summary>

| | |
|---|---|
| [nori](https://github.com/qwexvf/nori) | OpenAPI codegen — types, routes, clients, middleware, React Query/SWR hooks |
| [nori_asyncapi](https://github.com/qwexvf/nori_asyncapi) | AsyncAPI 3.x codegen — typed TypeScript client + Gleam server handlers |
| [mochi](https://github.com/qwexvf/mochi) | GraphQL engine. Satellites: [codegen](https://github.com/qwexvf/mochi_codegen), [transport](https://github.com/qwexvf/mochi_transport), [relay](https://github.com/qwexvf/mochi_relay), [upload](https://github.com/qwexvf/mochi_upload), [studio](https://github.com/qwexvf/mochi_studio) |
| [taffy](https://github.com/qwexvf/taffy) | Pure Gleam YAML 1.2 parser 🍬 |

</details>

<details open>
<summary><b>Rust / Go</b></summary>

| | |
|---|---|
| [ripple](https://github.com/qwexvf/ripple) | Code-intelligence engine — blast radius, PR review targeting, cross-service call graphs across 13 languages. CLI, MCP server, or file-watching daemon |
| [aegis-cli](https://github.com/qwexvf/aegis-cli) | Supply-chain scanner — offline-first, AST risk scoring, CVE/OSV gating, SBOM, 24 lockfile ecosystems |
| [sendup](https://github.com/qwexvf/sendup) | Static HTML to your own subdomain in ~1s, on Cloudflare's free tier |
| [apm](https://github.com/qwexvf/apm) | Lockfile-based reproducible plugin installs for AI agent tools |

</details>

<details open>
<summary><b>Neovim</b></summary>

| | |
|---|---|
| [aegis.nvim](https://github.com/qwexvf/aegis.nvim) | Gates plugin clone/update/build/load on an aegis verdict for that exact commit |
| [pakku.nvim](https://github.com/qwexvf/pakku.nvim) | Plugin manager on `vim.pack` — lazy.nvim DX, supply-chain scanning, force-push audit |

</details>
