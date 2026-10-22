# @red-cup-engineering/web-gui-services-section

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

The shared browser projection boundary for witnessed worlds.

This package owns presentation: an immutable JSON-like view, a material
language, accessible HTML, and a dependency-free isometric browser renderer.
It does not own game state, authentication, command admission, persistence, or
deployment. Consumers translate authoritative state into `WebGuiModel`; the
browser returns intents as `web-gui:action` DOM events or an optional POST.

Charge is structure, not a status color: unknown is porous, potential and
active are opposing veins, and stable/both is a hatched ceramic crack retaining
both witnesses. Only the rendered projection is ephemeral.

Keyboard: WASD/arrows pan, Q/E rotate, wheel zoom, 1–9 choose admitted moves,
and slash focuses speech.
