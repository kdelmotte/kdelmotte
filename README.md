### Hey, I'm Kevin.

I'm a product manager who builds things. These repos aren't side projects, they're tools I use every single day to work faster.

**[Mumble](https://github.com/kdelmotte/Mumble)** — Hold Fn, talk, release. Mumble transcribes your speech via Groq Whisper, detects the app you're in (email? Slack? VS Code?), and formats the output to match the context. Menu bar app, zero dependencies, signed and notarized.

**[TypoFixr](https://github.com/kdelmotte/TypoFixr)** — Cmd+Shift+D (or the shortcut of your choice) in any text field on macOS. Fixes typos and grammar while preserving your voice, no rewrites, just corrections. Parallel sentence chunking under the hood, to make it lightning fast.

**Why I build:** I think the best PMs understand the medium they're working in. Both apps are wired into Groq's inference APIs, Whisper large-v3 for transcription, reasoning models with tuned token budgets and temperature-zero determinism for text correction. I care about the details that make AI feel invisible: context-aware prompt routing, adaptive reasoning effort based on input complexity, and hallucination filtering on silent audio. These started as scratching my own itch and turned into real, shipped software, code-signed, notarized, and distributed via DMG.

I'm always looking for the next piece of daily friction to automate. If you try either app, I'd love to hear what you think, open an issue or reach out!
