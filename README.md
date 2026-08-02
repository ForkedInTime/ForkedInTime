<img src="assets/banner.png" alt="ForkedInTime — Telecom, contact center, agentic AI" width="100%">

In March 2026 the FCC accelerated copper retirement. Wire center by wire center, on a
31-day clock, the network your elevator phones, fire panels and PRI trunks still ride on
is being switched off.

I have run those trunks — POTS, T1, PRI, SS7. I also evaluate the agentic AI replacing the
people who answered them. Most practitioners know one end of that migration; the whole job
lives in between, and that gap is what [KuberEva](https://kubereva.ai) exists for.

The repos below are the engineering half of the same instinct: make software run where it
wasn't meant to.

## Building

**[RustyClaw](https://github.com/ForkedInTime/RustyClaw)** · Rust · Apache-2.0

The Claude Code experience in one 19 MB binary. It indexes your codebase, routes each task to the cheapest
model that can handle it, and runs agents in parallel. No Node, no Python, no `node_modules` — and it runs
offline against Ollama when you want it to.

**[KeeperFX — Tux Edition](https://github.com/ForkedInTime/keeperfx-linux-alpha)** · C · GPL-2.0

Dungeon Keeper, native on Linux. No Wine, no Proton, no DOSBox — one AppImage that finds your original game
files and plays. Unofficial, community-maintained, and continuously re-synced with the upstream KeeperFX
team's work.

**[KeeperFX Launcher, Linux fork](https://github.com/ForkedInTime/keeperfx-launcher-qt-linux)** · C++

The KeeperFX team's settings launcher, patched to drive the native engine instead of a Wine prefix and to
install the Tux Edition alpha.

## Contributed upstream

**[rainlizard/Unearth](https://github.com/rainlizard/Unearth/pull/119)** — taught the Dungeon Keeper
map editor to launch the native Linux KeeperFX engine directly instead of going through Wine. Merged.

## Working in

**Practice** — SIP · SBC · SS7 · PRI · CCaaS · conversational and agentic AI

**Code** — Rust · C · C++ · Python · TypeScript · Shell, mostly on Linux

## Elsewhere

[kubereva.ai](https://kubereva.ai) · [@Hugeyeti](https://x.com/Hugeyeti)
