# Awesome Spec-Driven Development (SDD)

A curated list of tools, workflows, examples, and readings for AI-assisted Spec-Driven Development (SDD).

## What is Spec-Driven Development (SDD)?

How do I see it?

- **AI-era development framework**: Leverage AI to build software by telling AI agents to follow the specifications.
- **Spec before code**: Write specifications first, generate code next.
- **Align human and AI through spec**: Architecture, requirements, and interfaces are analyzed, designed, and codified into specifications. AI agents follow human-approved specifications as a source of truth.

How does the industry define it?

- [github/spec-kit](https://github.com/github/spec-kit#-what-is-spec-driven-development) - Code has been king for decades, but specs become new "king".
  > Specifications become executable, directly generating working implementations rather than just guiding them.
  > Intent-driven development where specifications define the "what" before the "how".
- [lean-spec.dev](https://www.lean-spec.dev/docs/guide/terminology/sdd-workflow) - Manage projects with specifications - simple, structured, and machine-readable.
  > Capture intent in a spec, let humans and AI execute from it, and keep the spec in sync.
- [acnlabs/MetaSpec](https://github.com/acnlabs/MetaSpec/blob/main/docs/spec-driven.md) - Specifications are the single source of truth for both humans and AI agents.
  > Spec-Driven is using structured specifications to drive workflows - from requirements to implementation. Define specs first, validate and generate, then execute. This ensures clarity, consistency, and enables AI agents to understand and assist throughout the process.
- [What Is Spec-Driven Development?](https://felipefontoura.com/articles/what-is-spec-driven-development/) - Code is a byproduct of the spec.
  > Spec-driven development (SDD) is a way of building software where you write and approve a structured specification (requirements, design, acceptance criteria, constraints, edge cases) before any code is generated, and that spec stays the source of truth the AI agent builds from.
- [Fission-AI/OpenSpec](https://github.com/Fission-AI/OpenSpec/blob/main/docs/overview.md) - You write specs, AI drafts the details. You propose changes, AI implements them.
- [IBM](https://www.ibm.com/think/topics/spec-driven-development) - A detailed specification of implementation details is authored and agreed upon before development begins.

## How to Adopt SDD?

**I want a toolkit that guides SDD:**

🔥 Popular toolkits:

- [github/spec-kit](https://github.com/github/spec-kit) ![stars](https://img.shields.io/github/stars/github/spec-kit.svg?style=flat&color=crimson&cacheSeconds=86400) - Specify → Plan → Tasks → Implement → Converge.
- [Fission-AI/OpenSpec](https://github.com/Fission-AI/OpenSpec) ![stars](https://img.shields.io/github/stars/Fission-AI/OpenSpec.svg?style=flat&color=darkorange&cacheSeconds=86400) - [OPSX workflow](https://github.com/Fission-AI/OpenSpec/blob/main/docs/opsx.md): Proposal → Specs → Design → Tasks → Implement.
- [open-gsd/gsd-core](https://github.com/open-gsd/gsd-core) ![stars](https://img.shields.io/github/stars/open-gsd/gsd-core.svg?style=flat&color=purple&cacheSeconds=86400) - Discuss → Plan → Execute → Verify → Ship. (GSD=Git. Ship. Done.) [Previous repository](https://github.com/gsd-build/get-shit-done)

More toolkits:

- [m0n0x41d/haft](https://github.com/m0n0x41d/haft) ![stars](https://img.shields.io/github/stars/m0n0x41d/haft.svg?style=flat&color=purple&cacheSeconds=86400) - FPF-style Harness + Spec. Specify → Think → Run → Govern.
- [Priivacy-ai/spec-kitty](https://github.com/Priivacy-ai/spec-kitty) ![stars](https://img.shields.io/github/stars/Priivacy-ai/spec-kitty.svg?style=flat&color=purple&cacheSeconds=86400) - Supports many agents, with Web UI. Spec → Plan → Tasks → Next → Review → Accept → Merge.
- [SpecPulse](https://github.com/specpulse/specpulse) ![stars](https://img.shields.io/github/stars/specpulse/specpulse.svg?style=flat&color=blue&cacheSeconds=86400) - Python SDD framework.
- [codervisor/leanspec](https://github.com/codervisor/leanspec) ![stars](https://img.shields.io/github/stars/codervisor/leanspec.svg?style=flat&color=blue&cacheSeconds=86400) - Recommends small (<300 lines) but focused specifications, with Web UI and desktop app.
- [sengac/fspec](https://github.com/sengac/fspec) ![stars](https://img.shields.io/github/stars/sengac/fspec.svg?style=flat&color=forestgreen&cacheSeconds=86400) - Spec-driven, multi-agent coding factory, with TUI.
- [davidlee/spec-driver](https://github.com/davidlee/spec-driver) ![stars](https://img.shields.io/github/stars/davidlee/spec-driver.svg?style=flat&color=forestgreen&cacheSeconds=86400) - Like spec-kit, with a nice TUI.
- [acnlabs/MetaSpec](https://github.com/acnlabs/MetaSpec) ![stars](https://img.shields.io/github/stars/acnlabs/MetaSpec.svg?style=flat&color=forestgreen&cacheSeconds=86400)
- [hffmnnj/goopspec](https://github.com/hffmnnj/goopspec) ![stars](https://img.shields.io/github/stars/hffmnnj/goopspec.svg?style=flat&color=forestgreen&cacheSeconds=86400) - Discuss → Plan → Execute → Accept.

**I want an agentic IDE with native SDD features:**

- [kirodotdev/Kiro](https://github.com/kirodotdev/Kiro) ![stars](https://img.shields.io/github/stars/kirodotdev/Kiro.svg?style=flat&color=purple&cacheSeconds=86400) - Supports feature/bugfix [specs](https://kiro.dev/docs/specs/) in workflow: Requirements → Design → Tasks. [Guide](https://github.com/jasonkneen/kiro) by Jason.

**I want skills/commands to help me with SDD:**

- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) ![stars](https://img.shields.io/github/stars/addyosmani/agent-skills.svg?style=flat&color=darkorange&cacheSeconds=86400) - Production-grade engineering skills for AI coding agents. [SDD skill](https://github.com/addyosmani/agent-skills/blob/main/skills/spec-driven-development/SKILL.md): Spec → Plan → Tasks → Implement.
- [gotalab/cc-sdd](https://github.com/gotalab/cc-sdd) ![stars](https://img.shields.io/github/stars/gotalab/cc-sdd.svg?style=flat&color=purple&cacheSeconds=86400) - Skill enhancing Kiro SDD.
- [zhu1090093659/spec_driven_develop](https://github.com/zhu1090093659/spec_driven_develop) ![stars](https://img.shields.io/github/stars/zhu1090093659/spec_driven_develop.svg?style=flat&color=blue&cacheSeconds=86400) - SDD workflow for AI Agents.
- [madebyaris/spec-kit-command-cursor](https://github.com/madebyaris/spec-kit-command-cursor) ![stars](https://img.shields.io/github/stars/madebyaris/spec-kit-command-cursor.svg?style=flat&color=blue&cacheSeconds=86400) - SDD workflow for Cursor IDE.
- [liatrio-labs/spec-driven-workflow](https://github.com/liatrio-labs/spec-driven-workflow) ![stars](https://img.shields.io/github/stars/liatrio-labs/spec-driven-workflow.svg?style=flat&color=forestgreen&cacheSeconds=86400) - SDD workflow skill: Spec → Tasks → Implement → Validate.

## Where to Learn SDD?

**Real-World Projects:**

Explicit SDD workflow:

- [zeromicro/go-zero](https://github.com/zeromicro/go-zero) ![stars](https://img.shields.io/github/stars/zeromicro/go-zero.svg?style=flat&color=darkorange&cacheSeconds=86400) - (Go) Web and RPC framework for microservices.
  - AI & SDD setup: [zeromicro/ai-context](https://github.com/zeromicro/ai-context)
- [ThinkInAIXYZ/deepchat](https://github.com/ThinkInAIXYZ/deepchat) ![stars](https://img.shields.io/github/stars/ThinkInAIXYZ/deepchat.svg?style=flat&color=purple&cacheSeconds=86400) - (TypeScript, Electron) AI chat desktop app.
  - SDD Instructions: [docs/spec-driven-dev.md](https://github.com/ThinkInAIXYZ/deepchat/blob/dev/docs/spec-driven-dev.md). Types of specs: architecture, features, and issues.

Spec-driven agents/skills:

- [ruvnet/RuView](https://github.com/ruvnet/RuView) ![stars](https://img.shields.io/github/stars/ruvnet/RuView.svg?style=flat&color=darkorange&cacheSeconds=86400) - (Rust) WiFi sensing platform, spatial intelligence.
  - SPARC agent: [agents/sparc](https://github.com/ruvnet/RuView/blob/main/.claude/agents/sparc), [skills/sparc-methodology/SKILL.md](https://github.com/ruvnet/RuView/blob/main/.claude/skills/sparc-methodology/SKILL.md)

Spec practices without a specific workflow:

- [bytedance/deer-flow](https://github.com/bytedance/deer-flow) ![stars](https://img.shields.io/github/stars/bytedance/deer-flow.svg?style=flat&color=darkorange&cacheSeconds=86400) - (Python) SuperAgent harness TUI.
  - Has plans/specs markdown files, but does not specify toolkit or workflow.
- [moeru-ai/airi](https://github.com/moeru-ai/airi) ![stars](https://img.shields.io/github/stars/moeru-ai/airi.svg?style=flat&color=darkorange&cacheSeconds=86400) - (TypeScript) Digital life creator.
  - Has plans/specs markdown files, but does not specify toolkit or workflow.

**Guides:**

- [Anioko/spec-driven-development](https://github.com/Anioko/spec-driven-development) ![stars](https://img.shields.io/github/stars/Anioko/spec-driven-development.svg?style=flat&color=gainsboro&cacheSeconds=86400)

## I Don't Like Working in the Terminal.

Toolkits mentioned above:

- [codervisor/leanspec](https://github.com/codervisor/leanspec)
- [Priivacy-ai/spec-kitty](https://github.com/Priivacy-ai/spec-kitty)

UI tools for SDD management:

- [rasimme/FlowBoard](https://github.com/rasimme/FlowBoard) ![stars](https://img.shields.io/github/stars/rasimme/FlowBoard.svg?style=flat&color=forestgreen&cacheSeconds=86400) - Project workspaces UI for AI agents.

More UI tools that are not built specifically for SDD:

- [BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban) ![stars](https://img.shields.io/github/stars/BloopAI/vibe-kanban.svg?style=flat&color=darkorange&cacheSeconds=86400) - Visualizes workspace with plans (specs), chats and code.

## Further Reading

- More curated spec-driven development lists: [curated-sdd-lists.md](curated-sdd-lists.md)
- Blogs:
  - [Understanding Spec-Driven-Development: Kiro, spec-kit, and Tessl](https://martinfowler.com/articles/exploring-gen-ai/sdd-3-tools.html)
  - [Spec-driven development: Using Markdown as a programming language when building with AI](https://github.blog/ai-and-ml/generative-ai/spec-driven-development-using-markdown-as-a-programming-language-when-building-with-ai/)
- Related methodologies:
  - [First Principles Framework (FPF)](https://github.com/ailev/FPF) - A standards-style pattern language for turning difficult engineering, research, management, and mixed human and AI work into explicit, reviewable, improvable reasoning.
  - Acceptance-driven development - [paul](https://github.com/ChristopherKahler/paul) ![stars](https://img.shields.io/github/stars/ChristopherKahler/paul.svg?style=flat&color=purple&cacheSeconds=86400) - Plan-Apply-Unify Loop, Structured AI-assisted development for Claude Code.
- Critical views: [anti-sdd.md](anti-sdd.md)
- GitHub topic: [#spec-driven-development](https://github.com/topics/spec-driven-development), [#spec-driven](https://github.com/topics/spec-driven).

## Contributing

Contributions welcome! Feel free to submit pull requests or open issues.
