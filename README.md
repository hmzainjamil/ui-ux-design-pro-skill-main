# ui-ux-design-pro-skill-main

> **Professional interface design, wired into Claude** — wireframes, design systems, component specs, and accessibility audits from a single skill

<div align="center">

[![Stars](https://img.shields.io/github/stars/hmzainjamil/ui-ux-design-pro-skill-main?style=for-the-badge&color=FFD700&labelColor=555)](https://github.com/hmzainjamil/ui-ux-design-pro-skill-main/stargazers)
[![Forks](https://img.shields.io/github/forks/hmzainjamil/ui-ux-design-pro-skill-main?style=for-the-badge&color=00BFFF&labelColor=555)](https://github.com/hmzainjamil/ui-ux-design-pro-skill-main/network)
[![Issues](https://img.shields.io/github/issues/hmzainjamil/ui-ux-design-pro-skill-main?style=for-the-badge&color=FF6347&labelColor=555)](https://github.com/hmzainjamil/ui-ux-design-pro-skill-main/issues)
[![PRs](https://img.shields.io/github/issues-pr/hmzainjamil/ui-ux-design-pro-skill-main?style=for-the-badge&color=32CD32&labelColor=555)](https://github.com/hmzainjamil/ui-ux-design-pro-skill-main/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/hmzainjamil/ui-ux-design-pro-skill-main?style=for-the-badge&color=9370DB&labelColor=555)](https://github.com/hmzainjamil/ui-ux-design-pro-skill-main/commits)

</div>

<div align="center">

![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-FF6B35?labelColor=555&style=flat)
![UI/UX](https://img.shields.io/badge/UI%2FUX-Professional-E91E63?labelColor=555&style=flat)
![Wireframes](https://img.shields.io/badge/Wireframes-ASCII%2FHTML-607D8B?labelColor=555&style=flat)
![Design Systems](https://img.shields.io/badge/Design_Systems-Bootstrap-9C27B0?labelColor=555&style=flat)
![WCAG](https://img.shields.io/badge/WCAG-2.1_AA-4CAF50?labelColor=555&style=flat)
![Figma](https://img.shields.io/badge/Figma-Token_Export-F24E1E?labelColor=555&style=flat)

</div>

---

## Why This Exists

Good UI/UX is a competitive moat. Bad UI/UX kills conversions, frustrates users, and drives churn. The gap between "AI-generated UI" and "professionally designed UI" used to be enormous.

This skill closes that gap.

`ui-ux-design-pro` is a Claude Code skill that transforms Claude into a professional interface designer — capable of producing wireframes, design system specifications, component documentation, user flow diagrams, and accessibility audits that match the quality of dedicated design tools and senior designers.

It's distinct from `ui-ux-pro-max` in focus: this skill emphasizes the **design process and documentation** — wireframes, flows, specs — while pro-max emphasizes component code generation.

---

## At a Glance

| Property | Detail |
|---|---|
| **Skill type** | Claude Code skill (SKILL.md) |
| **Primary focus** | Design process, wireframes, flows, specs |
| **Wireframe formats** | ASCII wireframes, HTML prototypes, Markdown specs |
| **Design system output** | Color palette, typography scale, spacing system, component spec |
| **User flows** | ASCII flow diagrams, decision trees, happy/sad paths |
| **Accessibility** | WCAG 2.1 AA audit, contrast checker, ARIA spec |
| **Component docs** | Props, states, variants, usage guidelines |
| **Handoff format** | Developer-ready spec with measurements and tokens |
| **UX research** | Persona templates, journey maps, usability heuristics |
| **Responsive** | Breakpoint-aware designs for mobile/tablet/desktop |
| **Animation spec** | Motion principles, duration, easing values |
| **Critique mode** | Structured UX critique against Nielsen's 10 heuristics |

---

## 🧠 CONCEPTS

| Concept | Definition |
|---|---|
| **Wireframe** | Low-fidelity layout showing structure without visual design |
| **Design System** | Shared vocabulary of components, tokens, and patterns |
| **User Flow** | Sequence of steps a user takes to complete a task |
| **Information Architecture** | Structural organization of content and navigation |
| **Heuristic Evaluation** | Expert review against Nielsen's 10 usability principles |
| **Persona** | Fictional user archetype based on research data |
| **Journey Map** | Timeline of user touchpoints, thoughts, and emotions |
| **Prototype** | Interactive or static simulation of the final product |
| **Handoff Spec** | Developer documentation: measurements, tokens, states |
| **Component State** | Default, hover, focus, active, disabled, error, loading |
| **Content Hierarchy** | Primary, secondary, tertiary information levels |
| **Progressive Disclosure** | Show only what's needed; reveal complexity on demand |

### 🔥 Hot

- **ASCII wireframes** — instant low-fi layouts without any tool dependency
- **Nielsen heuristic audit** — structured 10-point UX critique on any interface
- **Journey map generation** — full user journey from awareness to retention
- **Handoff spec** — developer-ready documentation with exact token values

---

## ⚙️ HOW IT WORKS

```
Design brief → Parse: type, audience, constraints, goals
       ↓
Information Architecture → Content hierarchy → Navigation structure
       ↓
Wireframe generation (ASCII or HTML)
       ↓
Design system specification (colors, type, spacing, components)
       ↓
User flow documentation → Happy path → Edge cases
       ↓
Accessibility audit → WCAG check → ARIA spec
       ↓
Developer handoff spec (measurements, tokens, states)
```

The skill loads a knowledge base covering:
- **UX methodology**: Double Diamond, Jobs-to-be-Done, Design Thinking
- **Visual design**: Gestalt, color theory, typography, grid systems
- **Interaction design**: Affordances, feedback, error recovery
- **Research methods**: Usability testing, card sorting, tree testing
- **Heuristics**: Nielsen's 10, Shneiderman's 8 Golden Rules

---

## 🚀 INSTALL

### Clone into Claude skills

```bash
git clone https://github.com/hmzainjamil/ui-ux-design-pro-skill-main.git \
  ~/.claude/skills/ui-ux-design-pro
```

### Manual install

```bash
mkdir -p ~/.claude/skills/ui-ux-design-pro
curl -sL https://raw.githubusercontent.com/hmzainjamil/ui-ux-design-pro-skill-main/main/SKILL.md \
  -o ~/.claude/skills/ui-ux-design-pro/SKILL.md
```

### Claude Code skill installer

```bash
claude skill install hmzainjamil/ui-ux-design-pro-skill-main
```

No additional dependencies required — all output is text-based (ASCII, Markdown, HTML). Optional for HTML prototypes:

```bash
npm install -D tailwindcss  # for styled HTML wireframes
```

---

## 📟 USAGE

### Wireframe a page

```
/ui-ux-design-pro wireframe a SaaS onboarding flow: email signup, company setup, invite team, first feature
```

### Design system bootstrap

```
/ui-ux-design-pro create a design system for a healthcare app: trust, clarity, accessibility as core values
```

### User flow documentation

```
/ui-ux-design-pro document the user flow for checkout: cart → address → payment → confirmation → post-purchase
```

### Component specification

```
/ui-ux-design-pro spec a data table component: sorting, filtering, pagination, row selection, bulk actions
```

### Heuristic evaluation

```
/ui-ux-design-pro run a Nielsen heuristic audit on [paste interface description or screenshot URL]
```

### Developer handoff

```
/ui-ux-design-pro generate handoff spec for a navigation component with mobile hamburger menu
```

### Persona creation

```
/ui-ux-design-pro create 3 user personas for a B2B project management tool targeting teams of 5-50
```

---

## ⚙️ CONFIGURATION

| Config key | Default | Options | Description |
|---|---|---|---|
| `wireframe_format` | `ascii` | `ascii`, `html`, `markdown` | Wireframe output format |
| `fidelity` | `low` | `low`, `mid`, `high` | Design fidelity level |
| `accessibility` | `wcag-aa` | `wcag-a`, `wcag-aa`, `wcag-aaa` | Accessibility standard |
| `design_methodology` | `double-diamond` | `double-diamond`, `design-thinking`, `lean-ux` | UX process framework |
| `include_flows` | `true` | `true`, `false` | Include user flows with designs |
| `include_states` | `true` | `true`, `false` | Document all component states |
| `handoff_format` | `markdown` | `markdown`, `notion`, `confluence` | Handoff doc format |
| `persona_count` | `3` | `1-5` | Number of personas to generate |
| `heuristics` | `nielsen` | `nielsen`, `shneiderman`, `both` | Heuristic evaluation framework |
| `annotation_style` | `inline` | `inline`, `sidebar`, `legend` | How to annotate wireframes |
| `responsive` | `all` | `mobile`, `tablet`, `desktop`, `all` | Target breakpoints |
| `critique_depth` | `standard` | `quick`, `standard`, `deep` | How thorough the UX critique |

---

## 💡 TIPS AND TRICKS

### Wireframing

> **Start with content, not layout** — list all elements that must appear on the page before drawing any boxes. Layout follows content needs.

> **ASCII first, always** — ASCII wireframes take 2 minutes and surface 80% of layout problems. Skip to HTML only when ASCII can't represent the complexity.

> **Annotate decisions, not elements** — "Search bar (800ms debounce, 3-char minimum)" is useful. "Search bar" is not.

### Design Systems

> **Name tokens by role, not value** — `--color-action-primary` not `--color-blue-500`. Values change; roles don't.

> **Document the why** — design decisions without rationale get overridden. "Primary: #1A56DB — chosen for 4.5:1 on white and brand alignment" survives team changes.

> **Start with 4 component states** — every interactive component needs default, hover, focus, and disabled before anything else.

### Handoff

> **Measure from baseline** — all spacing measurements to the text baseline, not the cap height or bounding box.

> **Export at 1x, document at 2x** — handoff images at 1x CSS pixels; note "2x for retina" in spec.

> **State matrix over prose** — a table of (trigger × state × visual change) communicates faster than paragraphs.

---

## 🔧 TROUBLESHOOTING

| Issue | Cause | Fix |
|---|---|---|
| Wireframe too generic | Not enough context | Provide user goals, constraints, existing patterns |
| Design system too minimal | Default low fidelity | Set `fidelity: high` for detailed spec |
| Flow missing edge cases | Happy-path-only prompt | Ask explicitly: "include error states and edge cases" |
| Component states incomplete | States not requested | Add "document all states" to prompt |
| WCAG audit too shallow | Default critique depth | Set `critique_depth: deep` |
| Handoff missing measurements | No spec request | End prompt with "generate developer handoff spec" |
| Persona too generic | No user research context | Provide: industry, user job title, pain points, goals |
| ASCII wireframe misaligned | Font rendering | View in monospace font (Courier, Monaco, Fira Code) |
| HTML wireframe unstyled | Missing Tailwind | Add `<script src="https://cdn.tailwindcss.com"></script>` |
| Heuristic audit too surface | Quick mode | Set `critique_depth: deep` for full 10-heuristic pass |

---

## 📊 ARCHITECTURE

```
ui-ux-design-pro-skill-main/
├── SKILL.md                        # Core skill definition
├── methodology/
│   ├── double-diamond.md           # UX process framework
│   ├── jobs-to-be-done.md          # JTBD methodology
│   └── design-thinking.md         # Design thinking process
├── knowledge/
│   ├── visual-design.md            # Color, type, grid, Gestalt
│   ├── interaction-design.md       # Affordances, feedback, flows
│   ├── accessibility.md            # WCAG 2.1, ARIA, keyboard nav
│   └── heuristics.md               # Nielsen + Shneiderman rules
├── templates/
│   ├── wireframe-ascii.tpl         # ASCII wireframe template
│   ├── design-system.tpl           # Design system doc template
│   ├── user-flow.tpl               # Flow diagram template
│   ├── persona.tpl                 # User persona template
│   ├── journey-map.tpl             # Journey map template
│   └── handoff-spec.tpl            # Developer handoff template
├── examples/
│   ├── saas-onboarding/            # Full onboarding wireframes
│   └── dashboard-design-system/   # Complete design system example
└── README.md
```

---

## 🗺️ ROADMAP

| Feature | Status | ETA |
|---|---|---|
| ASCII wireframe generation | ✅ Done | — |
| Nielsen heuristic evaluation | ✅ Done | — |
| Design system specification | ✅ Done | — |
| User flow documentation | ✅ Done | — |
| Developer handoff spec | ✅ Done | — |
| HTML prototype generation | 🔄 In progress | Q3 2025 |
| Interactive prototype (Framer) | 📋 Planned | Q4 2025 |
| Figma file generation via API | 📋 Planned | Q4 2025 |
| A/B test variant design | 📋 Planned | Q4 2025 |
| Usability test script generator | 📋 Planned | Q1 2026 |
| Design critique AI agent | 📋 Planned | Q1 2026 |
| WCAG 2.2 AAA support | 📋 Planned | Q2 2026 |

---

## ☠️ STARTUPS / BUSINESSES

**Design without a designer:**

| Need | Traditional | With this skill |
|---|---|---|
| App wireframes | Hire UX designer ($150/hr) | 30 min with skill |
| Design system | 2-week design sprint | Bootstrapped in hours |
| Component spec for devs | Designer-dev sync meetings | Automated handoff doc |
| UX audit of existing app | Consulting engagement ($5k+) | `/ui-ux-design-pro audit` |
| User persona research | Research agency ($10k+) | Evidence-based personas in minutes |
| Journey map workshop | Half-day facilitation | Generated in 10 minutes |

**Best for:**
- Pre-seed/seed startups without a designer
- Engineering-led teams that want design rigor
- Agencies documenting design decisions for clients
- Product teams doing rapid iteration

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hmzainjamil/ui-ux-design-pro-skill-main&type=Date)](https://star-history.com/#hmzainjamil/ui-ux-design-pro-skill-main&Date)

---

<div align="center">

Built by [HMZ](https://github.com/hmzainjamil) · Professional UI/UX design for Claude Code · PRs welcome

</div>
