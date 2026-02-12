# UX/UI Mastery Plugin for Claude Code

**v3.0.0** | 19 Skills | 55 References | 10 Commands | 300K+ Words

The definitive UX/UI design mastery plugin. Not just theory — production code, cognitive science, real case studies, and Figma-to-code workflows. Built on NNG Group methodology, 25+ Laws of UX, 50+ cognitive biases, and cutting-edge 2025-2026 research.

## Installation

### Quick Install (Recommended)

The plugin is already installed if it lives at `~/.claude/plugins/ux-ui-mastery/`. Claude Code automatically discovers plugins in this directory.

To verify it's active, start Claude Code and try any command:

```bash
claude
# Then type: /ux-audit
```

### Manual Install

1. **Clone or copy** the plugin into your Claude Code plugins directory:

```bash
mkdir -p ~/.claude/plugins
cp -r ux-ui-mastery ~/.claude/plugins/
```

2. **Verify the plugin structure**:

```bash
ls ~/.claude/plugins/ux-ui-mastery/.claude-plugin/plugin.json
# Should exist and show version 3.0.0
```

3. **Restart Claude Code** to pick up the new plugin.

### Install from Git

```bash
cd ~/.claude/plugins
git clone https://github.com/YOUR_USERNAME/ux-ui-mastery.git
```

### Verify Installation

Run any of the 10 commands to confirm the plugin is loaded:

```
/ux-audit          — Audit against NNG heuristics
/design-review     — Full design review
/accessibility-check — WCAG 2.2 compliance check
/cognitive-check   — Cognitive psychology audit
/component-build   — Build production component
/design-critique   — Structured design critique
/figma-to-code     — Generate code from Figma spec
/generate-design-tokens — W3C design token system
/ai-ux-audit       — AI feature trust/safety audit
/ux-metrics-plan   — HEART framework metrics plan
```

You can also test skill activation by asking Claude about any trigger topic (e.g., "cognitive load", "Fitts's Law", "design tokens", "Gestalt principles"). The relevant skill and references will load automatically.

### Requirements

- Claude Code CLI (latest version)
- No external dependencies — the plugin is pure markdown

## What's New in v3.0

v3.0 transforms the plugin from "excellent theory reference" into "the only UX/UI tool you'll ever need":

- **Code that ships**: 40+ production React/TypeScript, SwiftUI, and CSS components with full state matrices
- **Cognitive psychology foundations**: 25+ Laws of UX, 50+ cognitive biases, neurodesign science, attention and memory frameworks
- **Real case studies**: 10 product deep-dives (Stripe, Linear, Notion, Figma, Airbnb) + 10 redesign failure analyses
- **Figma MCP flywheel**: Design-to-code pipeline powered by MCP, Code Connect, and Style Dictionary
- **Platform current**: iOS 26 Liquid Glass, Material 3 Expressive, modern CSS (container queries, :has(), anchor positioning)
- **Agentic AI patterns**: Control/consent/accountability triad, multi-agent orchestration UX, hallucination guardrails
- **7 new skills**: Cognitive psychology, component code, design critique, Figma workflows, performance states, cross-cultural i18n, ambient/calm technology
- **4 new commands**: `/component-build`, `/design-critique`, `/figma-to-code`, `/cognitive-check`

## What This Plugin Does

This plugin transforms Claude into an elite UX/UI design advisor and builder capable of:

- **Building** production-ready components with full state matrices, accessibility, and design tokens
- **Auditing** interfaces against cognitive psychology principles, Laws of UX, and 50+ biases
- **Evaluating** designs against Nielsen's 10 usability heuristics with severity ratings
- **Critiquing** designs using structured methodology (Liz Lerman, 30/60/90 framework)
- **Generating** code from Figma specifications via the MCP design-to-code flywheel
- **Designing** for mobile, desktop, web, wearable, IoT, spatial computing, and AI-native platforms
- **Building** design token systems following the W3C stable specification (October 2025)
- **Auditing** accessibility against WCAG 2.2 standards with WCAG 3.0 preparation
- **Reviewing** visual design, typography, color, and layout systems
- **Advising** on interaction design, motion, haptics, and emotional design
- **Guiding** ethical design decisions, dark pattern avoidance, and sustainable UX
- **Architecting** agentic AI, generative UI, RAG interfaces, and AI safety guardrails
- **Measuring** UX outcomes with HEART framework, SUS, A/B testing, and AI-specific metrics
- **Supporting** cross-cultural design with i18n patterns, RTL, and cultural dimension mapping
- **Designing** ambient, calm, and zero-UI experiences for screenless contexts

## Skills (19 Domains)

### Core Foundations
| Skill | Focus Area |
|-------|-----------|
| **Cognitive Psychology UX** | Laws of UX (25+), Gestalt principles, cognitive biases (50+), mental models, attention, memory, neurodesign |
| **NNG UX Heuristics** | Nielsen's 10 heuristics with modern 2025+ interpretation |
| **UX Research Methods** | Research methodology, testing protocols, AI-augmented research, synthesis frameworks |
| **UX Metrics & Measurement** | HEART framework, SUS, UEQ, task-based metrics, A/B testing, AI-specific metrics |

### Implementation
| Skill | Focus Area |
|-------|-----------|
| **Component Patterns & Code** | Production React/TypeScript, SwiftUI, CSS components with state matrices and accessibility |
| **Design Systems Architecture** | Design tokens (W3C 2025.10), component libraries, governance, DesignOps, multi-brand |
| **Figma Design Tool Workflows** | Figma mastery, MCP design-to-code, Code Connect, Dev Mode, Style Dictionary pipeline |
| **UI Visual Design System** | Typography, color theory, spacing, visual hierarchy, modern CSS |

### Platform & Context
| Skill | Focus Area |
|-------|-----------|
| **Mobile UX Design** | Mobile-first, touch, gesture, iOS 26 Liquid Glass, Material 3 Expressive, wearable, IoT |
| **Desktop App Design** | Enterprise dashboards, data-dense interfaces, keyboard-first, data visualization |
| **Cross-Cultural i18n UX** | Internationalization, RTL, CJK, Hofstede's dimensions, cultural adaptation |
| **Performance States Patterns** | Loading, skeleton, optimistic UI, notifications, empty/error/onboarding states |

### Interaction & Experience
| Skill | Focus Area |
|-------|-----------|
| **Interaction & Motion Design** | Animation, micro-interactions, haptic feedback, emotional design |
| **Accessibility & Inclusive Design** | WCAG 2.2, WCAG 3.0 preview, ARIA, cognitive accessibility, AI-adaptive patterns |
| **Design Critique & Case Studies** | Critique methodology, product deep-dives, redesign failure analysis |
| **UX Ethics & Content Strategy** | Dark patterns, regulatory landscape, privacy UX, microcopy patterns, sustainable UX |

### Emerging Technology
| Skill | Focus Area |
|-------|-----------|
| **Agentic AI & Generative UX** | Multi-agent orchestration, generative UI, RAG interfaces, hallucination guardrails, conversational AI |
| **AI, Spatial & Voice UX** | AI interfaces, AR/VR, voice, multimodal |
| **Ambient Calm & Zero UI** | Calm technology, screenless interfaces, proactive intelligence, ambient computing |

## Commands (10)

| Command | Purpose |
|---------|---------|
| `/ux-audit` | Audit UI against NNG heuristics with severity ratings |
| `/design-review` | Full design review scoring all domains |
| `/accessibility-check` | Deep WCAG 2.2 compliance check with specific fixes |
| `/generate-design-tokens` | Generate a complete W3C design token system |
| `/ai-ux-audit` | Audit AI features for trust, safety, usability, and accessibility |
| `/ux-metrics-plan` | Generate a UX metrics plan using the HEART framework |
| `/component-build` | Build production component with state matrix, a11y, tokens, and platform code |
| `/design-critique` | Structured critique using Liz Lerman process with 10-dimension scoring |
| `/figma-to-code` | Generate production code from Figma design specification |
| `/cognitive-check` | Audit against Laws of UX, Gestalt principles, and cognitive biases |

## Design Philosophy

This plugin embeds principles from the world's most influential designers:

- **Don Norman** — Affordances, emotional design, human-centered design
- **Dieter Rams** — "Less, but better" — systematic minimalism
- **Jony Ive** — Invisible design, where the interface disappears
- **Luke Wroblewski** — Mobile-first, form design mastery
- **Julie Zhuo** — Design leadership, scaling design quality
- **Edward Tufte** — Data visualization, information density with clarity
- **Jakob Nielsen** — Usability heuristics, evidence-based design
- **Daniel Kahneman** — Peak-End Rule, cognitive biases, behavioral economics
- **Amber Case** — Calm technology, designing for peripheral attention

## Architecture

The plugin uses progressive disclosure — only the relevant skill and references are loaded based on the user's query, keeping context lean while providing deep expertise on demand.

```
ux-ui-mastery/
├── .claude-plugin/plugin.json       # Plugin manifest (v3.0.0)
├── marketplace.json                 # Marketplace metadata
├── skills/                          # 19 skill domains
│   ├── cognitive-psychology-ux/     # Laws of UX, biases, neurodesign
│   │   ├── SKILL.md
│   │   └── references/
│   │       ├── laws-of-ux-encyclopedia.md
│   │       ├── cognitive-biases-design-patterns.md
│   │       └── neurodesign-engagement-science.md
│   ├── component-patterns-code/     # Production component code
│   │   ├── SKILL.md
│   │   └── references/
│   │       ├── react-component-cookbook.md
│   │       ├── swiftui-component-cookbook.md
│   │       └── css-modern-patterns.md
│   ├── design-critique-case-studies/ # Critique + case studies
│   │   ├── SKILL.md
│   │   └── references/
│   │       ├── critique-methodology.md
│   │       ├── product-deep-dives.md
│   │       └── redesign-failure-analysis.md
│   ├── figma-design-tool-workflows/ # Figma MCP + design-to-code
│   │   ├── SKILL.md
│   │   └── references/
│   │       ├── figma-mastery-workflows.md
│   │       ├── figma-mcp-ai-flywheel.md
│   │       └── design-to-code-pipeline.md
│   ├── performance-states-patterns/ # Loading, errors, notifications
│   │   ├── SKILL.md
│   │   └── references/
│   │       ├── perceived-performance-patterns.md
│   │       ├── notification-system-design.md
│   │       └── empty-error-onboarding-states.md
│   ├── cross-cultural-i18n-ux/     # i18n, RTL, cultural dimensions
│   │   ├── SKILL.md
│   │   └── references/
│   │       ├── internationalization-patterns.md
│   │       └── cultural-ux-dimensions.md
│   ├── ambient-calm-zero-ui/       # Calm technology, ambient computing
│   │   ├── SKILL.md
│   │   └── references/
│   │       └── calm-technology-principles.md
│   ├── nng-ux-heuristics/          # Nielsen's 10 heuristics
│   ├── ux-research-methods/        # Research methodology
│   ├── mobile-ux-design/           # Mobile, iOS 26, M3 Expressive
│   ├── desktop-app-design/         # Desktop, data visualization
│   ├── ui-visual-design-system/    # Visual design systems
│   ├── accessibility-inclusive-design/ # WCAG 2.2 + 3.0
│   ├── interaction-motion-design/  # Animation, haptics
│   ├── ai-spatial-voice-ux/        # AI, AR/VR, voice
│   ├── design-systems-architecture/ # Design tokens, governance
│   ├── ux-ethics-content-strategy/ # Ethics, microcopy
│   ├── agentic-ai-generative-ux/  # Agentic AI, generative UI
│   └── ux-metrics-measurement/     # UX metrics, HEART
├── commands/                        # 10 executable commands
│   ├── ux-audit.md
│   ├── design-review.md
│   ├── accessibility-check.md
│   ├── generate-design-tokens.md
│   ├── ai-ux-audit.md
│   ├── ux-metrics-plan.md
│   ├── component-build.md          # NEW
│   ├── design-critique.md          # NEW
│   ├── figma-to-code.md            # NEW
│   └── cognitive-check.md          # NEW
└── README.md
```

## Knowledge Base

Over **300,000 words** of structured UX/UI expertise:
- 19 core skill files (~2,000 words each)
- 55 deep reference files (~3,000-6,500 words each)
- 10 executable command templates
- 40+ production code examples (React/TypeScript, SwiftUI, CSS)
- 18+ real-world case studies and failure analyses
- 25+ Laws of UX with formulas and anti-patterns
- 50+ cognitive biases with ethical annotations

## Research Sources

This plugin's knowledge is grounded in authoritative research:

- **Cognitive Psychology**: Kahneman (Peak-End Rule), Sweller (Cognitive Load Theory), Cowan (Working Memory), Iyengar (Choice Overload), Fitts, Hick, Miller, Gestalt school
- **arXiv Papers**: UX 3.0 Paradigm Framework, GenAI for UX Research, EvAlignUX, Emotion-Aware Interaction Design, Survey of GenAI UI Design, Generative Interfaces for LLMs, Healthcare AI Patterns, Agentic AI Design Workflows, LLM Hallucination Detection
- **ACM CHI 2025**: Designing UIs with AI, Screen Reader Users + AI Coding Tools, Multi-Agent Generative AI, AI Literacy in Design
- **NNG Group 2025-2026**: State of UX 2026, UX Reckoning 2025, AI Literacy, Generative UI, Outcome-Oriented Design, DesignOps 101, iOS 26 Liquid Glass usability critique, "AI Slop" quality gates
- **W3C Specifications**: WCAG 3.0 April 2026 Working Draft, Design Tokens 2025.10 Stable Release, WAI-ARIA Authoring Practices
- **Platform**: Apple WWDC 2025 (iOS 26 Liquid Glass), Google I/O 2025 (Material 3 Expressive), Figma Config 2025 (MCP, Code Connect)
- **Industry**: Smashing Magazine Feb 2026 (Agentic UX), Microsoft Copilot Framework, OpenAI Apps SDK, Sparkbox Design System ROI, Amber Case (Calm Technology), Liz Lerman (Critical Response Process)
- **Case Studies**: Stripe, Linear, Notion, Airbnb, Figma, Arc Browser, Duolingo, Vercel, plus failure analyses of Snapchat 2018, Windows 8, Digg v4, Sonos 2024, and more
