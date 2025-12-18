# Subfracture Plugins

**Official Claude Code plugins from Subfracture**

## Installation

### Add the Marketplace

**From GitHub** (after publishing):
```bash
/plugin marketplace add subfracture/subfracture-plugins
```

**From Local Directory** (for testing):
```bash
/plugin marketplace add /path/to/subfracture-plugins
```

### Install Plugins

```bash
# List available plugins
/plugin search @subfracture-plugins

# Install BWD
/plugin install bwd-brand-world-design@subfracture-plugins
```

## Available Plugins

### BWD: Brand World Design

Transform brand strategy into a journey through Seven Chambers governed by Hermetic principles.

**Commands:**
- `/brand-init` — Start a brand journey
- `/quick-position [brand]` — Quick FOR/ONLY/BECAUSE positioning
- `/pits` — Problem-Insight-Truth-Solution creative strategy

**Features:**
- 7 Guardian agents (Weaver, Visionary, Architect, Resonant, Navigator, Bard, Skeptic)
- FOR/ONLY/BECAUSE positioning framework
- PITS creative strategy framework
- 9 artifact templates
- 3 journey tracks (Quick, Full, Enterprise)

---

## For Developers

### Marketplace Structure

```
subfracture-plugins/
├── .claude-plugin/
│   └── marketplace.json      # Marketplace manifest
├── bwd-brand-world-design/   # BWD plugin
│   ├── .claude-plugin/
│   │   └── plugin.json
│   ├── agents/
│   ├── commands/
│   ├── skills/
│   └── README.md
└── README.md
```

### Adding New Plugins

1. Create plugin directory with `.claude-plugin/plugin.json`
2. Add entry to `marketplace.json` plugins array
3. Commit and push

---

*A Subfracture creation*
