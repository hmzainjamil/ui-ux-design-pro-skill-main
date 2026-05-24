# ui-ux-design-pro-skill-main

> **Professional interface design, wired into Claude** — wireframes, design systems, component specs, and accessibility audits from a single skill

<div align="center">

[![Stars](https://img.shields.io/github/stars/hmzainjamil/ui-ux-design-pro-skill-main?style=flat&color=FFD700&labelColor=555)](https://github.com/hmzainjamil/ui-ux-design-pro-skill-main/stargazers)
[![Forks](https://img.shields.io/github/forks/hmzainjamil/ui-ux-design-pro-skill-main?style=flat&color=00BFFF&labelColor=555)](https://github.com/hmzainjamil/ui-ux-design-pro-skill-main/network)
[![Issues](https://img.shields.io/github/issues/hmzainjamil/ui-ux-design-pro-skill-main?style=flat&color=FF6347&labelColor=555)](https://github.com/hmzainjamil/ui-ux-design-pro-skill-main/issues)
[![PRs](https://img.shields.io/github/issues-pr/hmzainjamil/ui-ux-design-pro-skill-main?style=flat&color=32CD32&labelColor=555)](https://github.com/hmzainjamil/ui-ux-design-pro-skill-main/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/hmzainjamil/ui-ux-design-pro-skill-main?style=flat&color=9370DB&labelColor=555)](https://github.com/hmzainjamil/ui-ux-design-pro-skill-main/commits)

</div>

<div align="center">

![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-FF6B35?labelColor=555&style=flat)
![UI/UX](https://img.shields.io/badge/UI%2FUX-Professional-E91E63?labelColor=555&style=flat)
![Wireframes](https://img.shields.io/badge/Wireframes-ASCII%2FHTML-607D8B?labelColor=555&style=flat)
![Design Systems](https://img.shields.io/badge/Design_Systems-Tokens-9C27B0?labelColor=555&style=flat)
![WCAG](https://img.shields.io/badge/WCAG-2.1_AA-4CAF50?labelColor=555&style=flat)
![Figma](https://img.shields.io/badge/Figma-Token_Export-F24E1E?labelColor=555&style=flat)

</div>

---

## Why This Exists

Good UI/UX is a competitive moat. Bad UI/UX kills conversions, frustrates users, and drives churn. The gap between "AI-generated UI" and "professionally designed UI" used to be enormous.

This skill closes that gap.

`ui-ux-design-pro` transforms Claude into a professional interface designer — wireframes, design system specifications, component documentation, user flow diagrams, and accessibility audits that match the quality of dedicated design tools and senior designers.

Distinct from `ui-ux-pro-max`: this skill emphasizes the **design process and documentation** — wireframes, flows, specs — while pro-max targets component code generation.

---

## ☠️ STARTUPS / BUSINESSES

If you're shipping product without a defined design process: **you're bleeding conversion rate and user trust every day.** Investors can see the difference between product built with design intent and product that looks like a dev made it at 2am. This skill is the difference between a Series A deck that impresses and one that gets passed.

- **SaaS founders** — generate design specs before the first line of code
- **Agency owners** — deliver client wireframes in 10 minutes, not 10 hours
- **Freelancers** — charge design-rate for work that took you engineer-rate time
- **Product teams** — document design decisions that survive team changes

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
| **Card Sorting** | User research method to test navigation/IA assumptions |
| **Affinity Diagram** | Clustering user research insights by theme |
| **Red Route** | Critical user path — must work flawlessly every time |
| **Design Debt** | Accumulated inconsistency that slows future design work |

---

### 🔥 Hot

```bash
# Load skill and generate wireframe
claude ui-ux-design-pro "wireframe a SaaS dashboard with sidebar nav"

# Run Nielsen heuristic audit on existing UI
claude ui-ux-design-pro "audit this interface against Nielsen's 10 heuristics: [paste HTML/description]"

# Generate full design system spec
claude ui-ux-design-pro "create design system tokens for a fintech app — primary blue, minimal, trustworthy"

# Generate user journey map
claude ui-ux-design-pro "journey map: B2B user onboarding from signup to first value moment"

# WCAG audit
claude ui-ux-design-pro "wcag audit this component — flag all AA failures with remediation"

# Component spec for dev handoff
claude ui-ux-design-pro "spec: dropdown select component with search, multi-select, async load states"
```

---

## Installation

```bash
# Clone to your Claude Code skills directory
git clone https://github.com/hmzainjamil/ui-ux-design-pro-skill-main ~/.claude/skills/ui-ux-design-pro

# Verify SKILL.md exists
ls ~/.claude/skills/ui-ux-design-pro/SKILL.md

# Activate in Claude Code (one-time)
# Add to ~/.claude/CLAUDE.md:
echo "auto-load: ui-ux-design-pro" >> ~/.claude/CLAUDE.md
```

---

## Skill Capabilities

### Wireframing Engine

| Output Type | Format | Use Case |
|---|---|---|
| Low-fi wireframe | ASCII art | Quick ideation, stakeholder alignment |
| Mid-fi wireframe | HTML + basic CSS | Clickable prototype, dev reference |
| Flow diagram | ASCII/Mermaid | User journey, decision tree |
| Component map | Markdown tree | Site architecture, feature mapping |
| Responsive layout | CSS Grid spec | Multi-breakpoint documentation |

### Design System Generator

| Token Type | Output | Example |
|---|---|---|
| Color | HEX + CSS var | `--color-primary: #2563EB` |
| Typography | Scale + line-height | `h1: 2.25rem / 1.25` |
| Spacing | 4px/8px grid | `--space-4: 1rem` |
| Border radius | Scale | `--radius-sm: 0.25rem` |
| Shadow | Elevation levels | `--shadow-md: 0 4px 6px -1px` |
| Motion | Duration + easing | `--duration-fast: 150ms ease-out` |

### Accessibility Audit

| WCAG Criterion | Check | Auto-fix |
|---|---|---|
| 1.4.3 Contrast (AA) | 4.5:1 normal, 3:1 large | Suggest compliant colors |
| 2.1.1 Keyboard | All interactive focusable | Add tabindex/ARIA patterns |
| 2.4.3 Focus Order | Logical DOM sequence | Flag out-of-order elements |
| 3.3.1 Error ID | Error messages descriptive | Generate aria-describedby spec |
| 4.1.2 Name/Role/Value | All controls labeled | Generate aria-label spec |

---

## Command Reference

| Command | What it does |
|---|---|
| `wireframe [description]` | Generate ASCII wireframe for described layout |
| `design-system [brand brief]` | Full token spec: color, type, space, motion |
| `audit [component]` | Nielsen heuristic + WCAG audit |
| `user-flow [task]` | ASCII flow diagram with decision branches |
| `persona [user type]` | Research-backed persona template |
| `journey-map [scenario]` | Full touchpoint journey with emotions |
| `component-spec [name]` | Props, states, variants, usage rules |
| `critique [description]` | Structured design critique with recommendations |
| `handoff [design]` | Developer-ready spec with all measurements |
| `responsive-spec [layout]` | Breakpoint behavior documentation |
| `animation-spec [interaction]` | Duration, easing, keyframe specification |
| `ia-diagram [app name]` | Information architecture tree |

---

## ■ Tips

> **Wireframe → Spec → Code pipeline**
> Always run: wireframe first → get stakeholder alignment → then component spec → then code.
> Skipping wireframe = 3x rework rate.
> Source: [Don't Make Me Think — Krug](https://www.sensible.com/dmmt.html)

> **Design tokens are the contract between design and engineering**
> Generate tokens with this skill, commit them as `tokens.json`, reference in Tailwind config.
> Source: [Design Tokens W3C Spec](https://tr.designtokens.org/format/)

> **WCAG AA is the legal floor in most jurisdictions**
> US ADA, EU EN 301 549, UK Equality Act all reference WCAG 2.1 AA.
> Run audit before every client delivery.
> Source: [W3C WCAG 2.1](https://www.w3.org/WAI/WCAG21/quickref/)

> **Nielsen's #1 heuristic violation: missing system status**
> 70% of UI frustration traces to users not knowing what the system is doing.
> Source: [Nielsen Norman Group](https://www.nngroup.com/articles/ten-usability-heuristics/)

---

## Design Process Workflow

```
1. BRIEF         → Extract requirements, constraints, users
2. WIREFRAME     → ASCII low-fi, get alignment fast
3. FLOW          → Map all user paths, edge cases
4. DESIGN SYSTEM → Tokens, palette, type, spacing
5. COMPONENT SPEC → States, props, variants
6. ACCESSIBILITY → WCAG audit, ARIA spec
7. HANDOFF       → Dev-ready spec with measurements
8. CRITIQUE      → Heuristic review before ship
```

---

## Comparison: Design Tools

| Capability | This Skill | Figma | Sketch | Adobe XD |
|---|---|---|---|---|
| Wireframing | ✅ ASCII/HTML | ✅ Visual | ✅ Visual | ✅ Visual |
| Design tokens | ✅ JSON/CSS | ✅ Plugin | ❌ Limited | ❌ Limited |
| WCAG audit | ✅ Auto | Plugin | Plugin | Plugin |
| Journey maps | ✅ Auto | Manual | Manual | Manual |
| Dev handoff | ✅ Markdown | ✅ Inspect | ✅ Inspect | ✅ Spec |
| Persona gen | ✅ Auto | ❌ | ❌ | ❌ |
| Cost | Free | $15+/mo | $99/yr | $55/mo |
| Works in terminal | ✅ | ❌ | ❌ | ❌ |

---

## Nielsen's 10 Heuristics — Audit Checklist

| # | Heuristic | What to check |
|---|---|---|
| 1 | Visibility of system status | Loading states, progress, confirmations |
| 2 | Match real world | Labels use user language, not system jargon |
| 3 | User control | Undo, back, cancel on every action |
| 4 | Consistency | Same patterns used throughout |
| 5 | Error prevention | Confirm dialogs, input constraints |
| 6 | Recognition > recall | Icons labeled, options visible |
| 7 | Flexibility | Shortcuts for power users |
| 8 | Aesthetic minimalism | No irrelevant info competing for attention |
| 9 | Error recovery | Clear error messages with fix instructions |
| 10 | Help & docs | Searchable, task-focused help |

---

## Responsive Breakpoint Reference

| Breakpoint | Width | Tailwind | Use case |
|---|---|---|---|
| xs | < 640px | default | Mobile first |
| sm | ≥ 640px | `sm:` | Large mobile |
| md | ≥ 768px | `md:` | Tablet |
| lg | ≥ 1024px | `lg:` | Desktop |
| xl | ≥ 1280px | `xl:` | Wide desktop |
| 2xl | ≥ 1536px | `2xl:` | Ultra-wide |

---

## Troubleshooting

| Issue | Cause | Fix |
|---|---|---|
| Skill not loading | SKILL.md not in correct path | Check `~/.claude/skills/ui-ux-design-pro/SKILL.md` |
| Wireframe too abstract | Not enough context given | Provide: layout type, user goal, key content |
| WCAG audit missing items | Partial component description | Provide full HTML or detailed component spec |
| Design tokens generic | No brand brief | Provide: primary color, brand adjectives, target industry |
| Journey map too short | Single user type | Specify: user segment, task, start/end points |

---

## Example Outputs

### ASCII Wireframe — SaaS Dashboard
```
+------------------------------------------+
| LOGO    Nav: Dashboard | Reports | Settings|
+--------+---------------------------------+
|        |  +-----------+  +-----------+  |
| SIDEBAR|  | KPI Card  |  | KPI Card  |  |
|  Menu  |  | $42,000   |  |  1,234    |  |
|  Item 1|  | +12% MoM  |  |  users    |  |
|  Item 2|  +-----------+  +-----------+  |
|  Item 3|                                 |
|        |  +---------------------------+  |
|        |  |   Chart: Revenue trend    |  |
|        |  |   [line graph area]       |  |
|        |  +---------------------------+  |
+--------+---------------------------------+
```

---

## File Structure

```
ui-ux-design-pro/
├── SKILL.md           # Core skill definition
├── patterns/
│   ├── wireframes.md  # ASCII wireframe patterns
│   ├── flows.md       # Flow diagram templates
│   └── tokens.md      # Design token schemas
├── audits/
│   ├── wcag.md        # WCAG 2.1 AA checklist
│   └── heuristics.md  # Nielsen 10 heuristics
└── templates/
    ├── persona.md     # Persona template
    ├── journey.md     # Journey map template
    └── handoff.md     # Dev handoff template
```

---

## Related Skills

| Skill | When to use |
|---|---|
| `ui-ux-pro-max` | Component code generation (React/Tailwind) |
| `canvas-design` | Visual design generation with Canvas |
| `figma-automation` | Push designs to Figma programmatically |
| `accessibility-wcag` | Deep WCAG compliance auditing |
| `design-patterns` | Software design patterns for UI logic |

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hmzainjamil/ui-ux-design-pro-skill-main&type=Date)](https://star-history.com/#hmzainjamil/ui-ux-design-pro-skill-main&Date)

---

<div align="center">

Built by [hmzainjamil](https://github.com/hmzainjamil) · Part of the [DigiMinds AI Agency](https://github.com/hmzainjamil) toolkit

</div>

---

## Advanced Patterns

### Design Token Pipeline

```
1. Generate tokens via skill
2. Save to tokens.json (W3C DTCG format)
3. Transform via Style Dictionary → Tailwind config + CSS vars
4. Commit tokens to repo
5. Reference in components via CSS vars or Tailwind classes
6. Update tokens in one place → all components update
```

### Component Documentation Standard

Every component spec should include:

| Section | Content |
|---|---|
| **Overview** | Purpose, when to use, when NOT to use |
| **Anatomy** | Visual breakdown of sub-parts |
| **Props** | Name, type, default, required, description |
| **States** | Every visual state with trigger condition |
| **Variants** | Size/style/color variants with use cases |
| **Accessibility** | ARIA roles, keyboard interactions, focus behavior |
| **Do/Don't** | Visual examples of correct and incorrect usage |
| **Examples** | 3–5 real usage examples in context |

---

## Color Science

### Contrast Ratio Calculation

```
Relative luminance: L = 0.2126R + 0.7152G + 0.0722B
Contrast ratio = (L1 + 0.05) / (L2 + 0.05)
AA text: >= 4.5:1
AA large text (18pt+ or 14pt bold): >= 3:1
AAA text: >= 7:1
```

### Palette Generation Strategy

| Step | Action |
|---|---|
| 1 | Pick brand primary (hue from brand brief) |
| 2 | Generate 10-shade scale (50→900) via HSL lightness |
| 3 | Verify 500-shade passes AA on white background |
| 4 | Generate semantic aliases (primary, secondary, success, error) |
| 5 | Add neutral grays (slate, zinc, stone) |
| 6 | Generate dark mode semantic layer |

---

## Typography Scale

| Token | Size | Line Height | Usage |
|---|---|---|---|
| `text-xs` | 0.75rem (12px) | 1rem | Labels, captions |
| `text-sm` | 0.875rem (14px) | 1.25rem | Secondary text, metadata |
| `text-base` | 1rem (16px) | 1.5rem | Body text |
| `text-lg` | 1.125rem (18px) | 1.75rem | Lead paragraph |
| `text-xl` | 1.25rem (20px) | 1.75rem | Section intro |
| `text-2xl` | 1.5rem (24px) | 2rem | Card headings |
| `text-3xl` | 1.875rem (30px) | 2.25rem | Page headings |
| `text-4xl` | 2.25rem (36px) | 2.5rem | Hero heading |

---

## UX Research Templates

### Persona Template

```markdown
## Persona: [Name]
**Role:** [Job title, company type]
**Age:** [Range]  **Tech comfort:** [Low/Med/High]

### Goals
- Primary: [Main task they want to accomplish]
- Secondary: [Supporting goals]

### Pain Points
- [Current frustration 1]
- [Current frustration 2]

### Behaviors
- Uses [tools] daily
- Makes decisions based on [criteria]
- Avoids [things]

### Quote
"[Characteristic statement in their voice]"
```

### Usability Test Script

```markdown
## Task: [Task name]
**Success criteria:** [Observable outcome]
**Max time:** [X minutes]

### Setup
"I'm going to ask you to do something on this interface. Think out loud."

### Task prompt
"[Natural language task statement — no UI hints]"

### Observe
- [ ] Found entry point?
- [ ] Completed task?
- [ ] Made errors?
- [ ] Recovered from errors?
- [ ] Time to complete?
```

---

## Integration with Design Tools

| Tool | Integration method | What to sync |
|---|---|---|
| Figma | Figma Tokens plugin + JSON export | Design tokens |
| Storybook | Generate `.stories.tsx` | Component states |
| Zeplin | Design spec export | Measurements, assets |
| Notion | Markdown export | Documentation |
| Linear | Link component to issue | Design decisions |

