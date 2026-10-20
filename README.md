<p>
  <img alt="Gleam" src="https://img.shields.io/badge/Gleam-FFAFF3?style=flat-square&logo=gleam&logoColor=000">
  <img alt="Erlang" src="https://img.shields.io/badge/Erlang-A90533?style=flat-square&logo=erlang&logoColor=fff">
  <img alt="Elixir" src="https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=fff">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=fff">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=fff">
  <img alt="Neovim" src="https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=fff">
</p>

Backend engineer in Tokyo. I mostly write Gleam these days, plus some Erlang and Elixir.
If the BEAM doesn't fit the job, I use Rust or Go.

I like trying new languages, runtimes and tools, even ones I probably don't need. I learn more
by building something small than by reading about it. Most of that stays as experiments; the
projects below are the ones I kept working on.

<details open>
<summary><b>Gleam</b></summary>

| | |
|---|---|
| [nori](https://github.com/qwexvf/nori) | OpenAPI codegen. Generates types, routes, clients, middleware and React Query/SWR hooks |
| [nori_asyncapi](https://github.com/qwexvf/nori_asyncapi) | AsyncAPI 3.x codegen. Generates a typed TypeScript client and Gleam server handlers |
| [mochi](https://github.com/qwexvf/mochi) | GraphQL server. Extra packages: [codegen](https://github.com/qwexvf/mochi_codegen), [transport](https://github.com/qwexvf/mochi_transport), [relay](https://github.com/qwexvf/mochi_relay), [upload](https://github.com/qwexvf/mochi_upload), [studio](https://github.com/qwexvf/mochi_studio) |
| [taffy](https://github.com/qwexvf/taffy) | YAML 1.2 parser written in pure Gleam 🍬 |

</details>

<details open>
<summary><b>Rust / Go</b></summary>

| | |
|---|---|
| [ripple](https://github.com/qwexvf/ripple) | Builds a call graph of your code (19 languages) to show what a change can break, what to look at first in a PR, and how services call each other. Use it as a CLI, an MCP server, or a daemon that reindexes on save |
| [aegis-cli](https://github.com/qwexvf/aegis-cli) | Supply-chain scanner. Works offline, scores packages by reading their AST, blocks installs with known CVEs (OSV), and outputs SBOMs. Parses 24 lockfile formats across 15 ecosystems |
| [sendup](https://github.com/qwexvf/sendup) | Puts a static HTML page on your own subdomain in about a second, on Cloudflare's free tier |
| [apm](https://github.com/qwexvf/apm) | Plugin manager for AI agent tools, with a lockfile so installs are reproducible |

</details>

<details open>
<summary><b>Neovim</b></summary>

| | |
|---|---|
| [aegis.nvim](https://github.com/qwexvf/aegis.nvim) | Checks the exact plugin commit with aegis before it gets cloned, updated, built or loaded |
| [pakku.nvim](https://github.com/qwexvf/pakku.nvim) | Plugin manager built on `vim.pack`. Feels like lazy.nvim, scans plugins for supply-chain issues, and warns when a repo was force-pushed |

</details>
