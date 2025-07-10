# SuperClaude – Marketing Framework for Claude Code

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-0.0.1-blue.svg)](https://github.com/NomenAK/SuperClaude)
[![GitHub issues](https://img.shields.io/github/issues/NomenAK/SuperClaude)](https://github.com/NomenAK/SuperClaude/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/NomenAK/SuperClaude/blob/master/CONTRIBUTING.md)

**A configuration framework that enhances Claude Code with specialized marketing personas, campaign workflows, and data-driven methodologies.**

## 🚀 Version 0.0.1 - Marketing Edition

SuperClaude v2 Marketing Edition introduces specialized marketing capabilities:

- **⚡ Streamlined Architecture**: @include reference system for configuration management
- **🎭 Marketing Personas**: 7 specialized personas integrated into the flag system (`--persona-product-marketer`, `--persona-growth-marketer`, etc.)
- **📊 MCP Integration**: MotherDuck, HubSpot, Google Analytics, and Puppeteer for data-driven marketing
- **🔧 Modular Design**: Template system for adding new marketing workflows
- **🎯 Unified Experience**: Consistent flag behavior across all marketing commands

See [ROADMAP.md](ROADMAP.md) for future development ideas and contribution opportunities.

## 🎯 Background

Claude Code provides powerful capabilities but can benefit from:
- **Specialized expertise** for different marketing domains
- **Token efficiency** for complex campaigns  
- **Evidence-based approaches** to marketing
- **Context preservation** during campaign analysis sessions
- **Data-driven decision making** for marketing optimization

## ✨ SuperClaude Marketing Features

SuperClaude enhances Claude Code with:
- **14 Marketing Commands** covering the complete marketing lifecycle
- **7 Marketing Personas** for domain-specific approaches
- **Token Optimization** with compression options
- **Evidence-Based Methodology** requiring data validation
- **MCP Integration** with MotherDuck, HubSpot, Google Analytics, Puppeteer
- **Campaign Checkpoint Support** for safe experimentation
- **Brand Compliance** enforcement throughout all operations

## 🚀 Installation

### Enhanced Installer v0.0.1
The installer provides various options:

```bash
git clone https://github.com/NomenAK/SuperClaude.git
cd SuperClaude

# Basic installation
./install.sh                           # Default: ~/.claude/

# Advanced options
./install.sh --dir /opt/claude        # Custom location
./install.sh --update                 # Update existing installation
./install.sh --dry-run --verbose      # Preview changes with details
./install.sh --force                  # Skip confirmations (automation)
./install.sh --log install.log        # Log all operations
```

**v0.0.1 Installer Features:**
- 🔄 **Update Mode**: Preserves customizations while updating
- 👁️ **Dry Run**: Preview changes before applying
- 💾 **Smart Backups**: Automatic backup with timestamping
- 🧹 **Clean Updates**: Removes obsolete files
- 🖥️ **Platform Detection**: Works with Linux, macOS, WSL
- 📊 **Progress Tracking**: Installation feedback

Zero dependencies. Installs to `~/.claude/` by default.

**Note:** After installation, all configuration files are located in `~/.claude/` (your home directory), not in the project directory.

## 💡 Core Marketing Capabilities

### 🧠 **Marketing Personas (As Flags!)**
Switch between different marketing approaches with persona flags:

```bash
/analyze --campaign --persona-growth-marketer     # Growth-focused analysis
/build --content --persona-content-creator       # Creative content development  
/test --ab-test --persona-growth-marketer        # A/B testing optimization
/validate --sql --persona-sql-auditor           # Data validation approach
```

**v0.0.1 Update**: All 7 marketing personas are now universal flags, available on every command for consistent access to specialized approaches.

### ⚡ **14 Marketing Commands**
Complete marketing lifecycle coverage:

**Campaign & Strategy Commands**
```bash
/build --campaign --motherduck --magic    # Data-driven campaign development
/analyze --competitive --seq              # Strategic competitive analysis
/test --ab-test --pup --coverage         # A/B testing with validation
```

**Content & Brand Commands**
```bash
/build --content --magic --hubspot       # Personalized content creation
/review --brand --consistency            # Brand compliance review
/document --user-guide --interactive     # User documentation
```

**Analytics & Optimization Commands**
```bash
/analyze --funnel --motherduck           # Conversion funnel analysis
/validate --sql --performance           # Data quality validation
/improve --conversion --iterate          # Performance optimization
```

### 🎛️ **MCP Integration for Marketing**
- **MotherDuck**: DuckDB cloud analytics for data analysis and SQL validation
- **HubSpot**: CRM integration for customer insights and campaign attribution
- **Google Analytics**: Web analytics for performance tracking and user behavior
- **Puppeteer**: Browser automation for A/B testing and landing page optimization

**⚠️ Important:** SuperClaude does not include MCP servers. You need to install them separately in Claude Code's MCP settings to use MCP-related flags (--motherduck, --hubspot, --google-analytics, --pup).

### 📊 **Token Efficiency**
SuperClaude's @include template system helps manage token usage:
- **UltraCompressed mode** option for token reduction
- **Template references** for configuration management
- **Caching mechanisms** to avoid redundancy
- **Context-aware compression** options

## 🎮 Example Marketing Workflows

### Product Launch Campaign
```bash
/analyze --market --competitive --persona-product-marketer    # Market research
/build --strategy --positioning --seq                        # Strategic planning
/build --campaign --multi-channel --magic --hubspot         # Campaign development
/test --landing-page --conversion --pup                     # Performance testing
```

### Brand Consistency Audit
```bash
/analyze --brand --compliance --persona-brand-strategist     # Brand analysis
/review --content --brand --consistency                     # Content review
/validate --guidelines --strict                             # Compliance validation
/improve --brand --alignment --iterate                      # Brand optimization
```

### Growth Optimization Campaign
```bash
/analyze --funnel --conversion --motherduck                 # Funnel analysis
/test --ab-test --statistical --pup                        # A/B testing
/improve --conversion --data-driven --persona-growth-marketer # Optimization
/validate --performance --roi --motherduck                 # Results validation
```

### Content Marketing Strategy
```bash
/analyze --audience --segmentation --hubspot               # Audience research
/build --content-calendar --seo --persona-content-creator # Content planning
/test --content --engagement --google-analytics           # Performance testing
/document --style-guide --brand --persona-editor         # Brand guidelines
```

## 🎭 Available Marketing Personas

| Persona | Focus Area | Tools | Use Cases |
|---------|-----------|-------|-----------|
| **product-marketer** | Market positioning | MotherDuck, HubSpot, Sequential | Go-to-market strategy |
| **growth-marketer** | Conversion optimization | MotherDuck, Google Analytics, Puppeteer | A/B testing, growth experiments |
| **content-creator** | Creative content | Magic, MotherDuck, Google Analytics | Multi-channel content |
| **technical-writer** | Documentation | Sequential, Context7, Puppeteer | User guides, API docs |
| **editor** | Content quality | Sequential, Context7 | Brand compliance, style |
| **brand-strategist** | Brand strategy | Sequential, Context7, HubSpot | Brand positioning, narrative |
| **sql-auditor** | Data validation | MotherDuck, Sequential | SQL validation, analytics |

## 🛠️ Configuration Options

### Data Analysis Control
```bash
# Standard analysis
/analyze --campaign --motherduck

# Deeper analysis  
/analyze --competitive --think-hard

# Maximum depth
/analyze --market --ultrathink
```

### Brand Compliance
```bash
# Enable brand compliance checking
/review --brand --strict

# Validate against brand guidelines
/validate --brand --compliance --zero-tolerance

# Audit brand consistency
/analyze --brand --comprehensive --persona-brand-strategist
```

### Token Management
```bash
# Standard mode
/build --campaign --magic

# With compression
/analyze --funnel --uc

# Native tools only
/validate --sql --no-mcp
```

### Evidence-Based Marketing
SuperClaude enforces:
- Data sources for all performance claims
- Analytics validation for campaign metrics
- Statistical significance for A/B testing
- Brand compliance for all content
- ROI tracking for campaign spend

## 📋 Command Categories

### Campaign & Strategy (4 Commands)
- `/build` - Campaign and content builder
- `/analyze` - Multi-dimensional marketing analysis
- `/design` - Brand and campaign strategy
- `/test` - A/B testing and optimization framework

### Content & Brand (3 Commands)
- `/review` - Content and brand compliance review
- `/document` - Marketing documentation creation
- `/improve` - Content and campaign optimization

### Analytics & Data (4 Commands)
- `/validate` - Data quality and SQL validation
- `/scan` - Performance and compliance auditing
- `/estimate` - Campaign planning and budgeting
- `/troubleshoot` - Marketing analytics debugging

### Operations (4 Commands)
- `/deploy` - Campaign launch and management
- `/migrate` - Platform and data migrations
- `/cleanup` - Campaign and asset maintenance
- `/git` - Version control for marketing assets

## 🔧 Technical Architecture v2

SuperClaude v2's marketing architecture enables extensibility:

**🏗️ Modular Configuration**
- **CLAUDE.md** – Core marketing configuration with @include references
- **.claude/shared/** – Centralized marketing YAML templates
- **commands/shared/** – Reusable marketing command patterns
- **@include System** – Template engine for configuration

**🎯 Unified Marketing Command System**
- **14 Commands** – Complete marketing lifecycle coverage
- **Flag Inheritance** – Universal flags on all commands
- **Persona Integration** – 7 marketing personas as flags
- **Template Validation** – Reference integrity checking

**📦 Architecture Benefits**
- **Single Source of Truth** – Centralized marketing updates
- **Easy Extension** – Add new marketing commands/flags
- **Consistent Behavior** – Unified flag handling
- **Reduced Duplication** – Template-based configuration

**✅ Quality Features**
- **Evidence-Based Approach** – Data validation required
- **MCP Integration** – Marketing tool orchestration
- **Error Recovery** – Graceful failure handling
- **Structured Output** – Organized campaign documentation

## 📊 Comparison

| Aspect | Standard Claude Code | SuperClaude Marketing |
|--------|---------------------|----------------------|
| **Expertise** | General responses | 7 specialized marketing personas |
| **Commands** | Manual instructions | 14 marketing workflow commands |
| **Context** | Session-based | Campaign checkpoint support |
| **Tokens** | Standard usage | Compression options |
| **Approach** | General purpose | Evidence-based marketing |
| **Documentation** | As needed | Systematic campaign documentation |
| **Quality** | Variable | Brand compliance validation |
| **Integration** | Basic tools | Marketing MCP orchestration |

## 🎯 Suitability

**Good fit for:**
- ✅ Marketing teams wanting consistent AI assistance
- ✅ Campaigns needing specialized approaches
- ✅ Evidence-based marketing practices
- ✅ Token-conscious workflows
- ✅ Data-driven marketing teams
- ✅ Brand compliance requirements

**May not suit:**
- ❌ Purely manual marketing workflows
- ❌ Minimal configuration preferences
- ❌ Ad-hoc marketing styles
- ❌ Single-channel focus

## 🚦 Getting Started

1. **Install SuperClaude**
   ```bash
   git clone https://github.com/NomenAK/SuperClaude.git && cd SuperClaude && ./install.sh
   ```

2. **Validate Installation**
   ```bash
   /load                                    # Load marketing context
   /analyze --campaign --think              # Test analysis
   /analyze --brand --persona-brand-strategist  # Try personas
   ```

3. **Example Marketing Workflow**
   ```bash
   /analyze --market --competitive        # Market research
   /build --campaign --strategy          # Campaign development
   /test --ab-test --conversion          # Performance testing
   /deploy --campaign --monitor          # Campaign launch
   ```

## 🛟 Support

- **Installation Help**: Run `./install.sh --help`
- **Command Details**: Check `~/.claude/commands/`
- **Contributing**: See [CONTRIBUTING.md](CONTRIBUTING.md)
- **Issues**: [GitHub Issues](https://github.com/NomenAK/SuperClaude/issues)

## 🤝 Community

SuperClaude welcomes contributions:
- **New Personas** for specialized marketing workflows
- **Commands** for marketing-specific operations  
- **Patterns** for marketing best practices
- **Integrations** for marketing productivity tools

Join the community: [Discussions](https://github.com/NomenAK/SuperClaude/discussions)

## 📈 Version 0.0.1 Marketing Changes

**🎯 Marketing Architecture:**
- **Marketing Configuration**: Complete marketing-focused configuration system
- **Token Efficiency**: Compression options maintained
- **Command System**: 18 marketing-specific commands
- **Persona System**: 7 marketing personas as flags
- **MCP Integration**: MotherDuck, HubSpot, Google Analytics, Puppeteer
- **Brand Compliance**: Zero-tolerance brand violation detection

**📊 Marketing Framework Details:**
- **Commands**: 14 specialized marketing commands
- **Personas**: 7 marketing cognitive approaches
- **MCP Servers**: 4 marketing tool integrations
- **Methodology**: Evidence-based marketing approach
- **Usage**: By marketing teams and agencies

## 🎉 Enhance Your Marketing

SuperClaude provides a structured approach to using Claude Code with specialized marketing commands, personas, and campaign patterns.

---

*SuperClaude v0.0.1 – Marketing framework for Claude Code*

[⭐ Star on GitHub](https://github.com/NomenAK/SuperClaude) | [💬 Discussions](https://github.com/NomenAK/SuperClaude/discussions) | [🐛 Report Issues](https://github.com/NomenAK/SuperClaude/issues)