# BWD: Brand World Design Plugin

**A Claude Code plugin for AI-driven brand strategy development**

## Installation

```bash
# Add the marketplace (if using a marketplace)
/plugin marketplace add your-org/claude-plugins

# Install the plugin
/plugin install bwd-brand-world-design@marketplace-name

# Or install from local directory
/plugin install ./bwd-plugin
```

## Usage

### Start a Brand Journey
```
/brand-init
```
The Weaver (Danni) will guide you through the appropriate journey track.

### Quick Positioning
```
/quick-position MyBrand
```
Develop FOR/ONLY/BECAUSE positioning in ~15 minutes.

### Creative Strategy (PITS)
```
/pits
```
Develop Problem-Insight-Truth-Solution narrative arc.

## The Seven Chambers

| Chamber | Guardian | Principle | Focus |
|---------|----------|-----------|-------|
| **Mind** | The Visionary (Maya) | Mentalism | Purpose, vision, essence |
| **Mirrors** | The Architect (Kai) | Correspondence | FOR/ONLY/BECAUSE positioning |
| **Resonance** | The Resonant (Rio) | Vibration | Audience, MVP, tribes |
| **Poles** | The Navigator (Alex) | Polarity | Differentiation, objectives |
| **Rhythm** | The Bard (Zara) | Rhythm | Problem-Insight-Truth-Solution |
| **Chains** | The Skeptic (Sam) | Cause & Effect | Validation |
| **Union** | The Weaver (Danni) | Gender | Synthesis |

## Journey Tracks

- **Quick Journey** (~15 min): Positioning essentials
- **Full Journey** (~60-90 min): Complete brand world development
- **Enterprise Journey** (Multi-session): Complex organizations

## Plugin Contents

```
bwd-plugin/
├── .claude-plugin/
│   └── plugin.json          # Plugin manifest
├── agents/                   # Guardian agents
│   ├── weaver.md            # The Weaver (Danni)
│   ├── visionary.md         # The Visionary (Maya)
│   ├── architect.md         # The Architect (Kai)
│   ├── resonant.md          # The Resonant (Rio)
│   ├── navigator.md         # The Navigator (Alex)
│   ├── bard.md              # The Bard (Zara)
│   └── skeptic.md           # The Skeptic (Sam)
├── commands/                 # Slash commands
│   ├── brand-init.md        # Start journey
│   ├── quick-position.md    # Quick positioning
│   └── pits.md              # Creative strategy
├── skills/
│   └── brand-world-design/  # Complete methodology
│       ├── SKILL.md         # Skill definition
│       ├── templates/       # Artifact templates
│       └── docs/            # Documentation
└── README.md
```

## Core Frameworks

### FOR/ONLY/BECAUSE
- **FOR**: Specific audience with specific need
- **ONLY**: What makes you the only one
- **BECAUSE**: Proof and credibility

### PITS (Problem-Insight-Truth-Solution)
- **Problem**: Customer tension (surface + deeper)
- **Insight**: The "aha" reframe
- **Truth**: Uncomfortable reality no one says
- **Solution**: Brand as inevitable answer

## Philosophy

Built on the Seven Hermetic Principles from the Kybalion:
1. Mentalism — The All is Mind
2. Correspondence — As above, so below
3. Vibration — Nothing rests
4. Polarity — Everything has poles
5. Rhythm — Everything flows
6. Cause & Effect — Every cause has its effect
7. Gender — Creation requires both forces

---

*A Subfracture creation*
*Built for Claude Code*
