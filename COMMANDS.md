# SuperClaude Marketing Commands Reference v0.0.1

## Table of Contents
- [Quick Start](#quick-start)
- [Universal Flags (Available on ALL Commands)](#universal-flags-available-on-all-commands)
- [Marketing Personas as Flags](#marketing-personas-as-flags)
- [Complete Command Reference](#complete-command-reference)
- [Flag Combinations & Best Practices](#flag-combinations--best-practices)

---

## Quick Start

**Basic Usage**: `/command [flags] [arguments]`

**Example Commands**:
```bash
/analyze --campaign --motherduck --persona-growth-marketer    # Campaign performance analysis
/build --content --magic --hubspot --persona-content-creator # Content creation with CRM data
/test --ab-test --pup --statistical                         # A/B testing with automation
/validate --sql --performance --persona-sql-auditor         # Data validation and optimization
/review --brand --consistency --persona-editor              # Brand compliance review
/deploy --campaign --monitor --validate                     # Safe campaign launch
```

---

## Universal Flags (Available on ALL Commands)

### 🧠 Thinking Depth Control
| Flag | Description | Token Usage |
|------|-------------|-------------|
| `--think` | Multi-dimensional analysis with expanded context | ~4K tokens |
| `--think-hard` | Strategic-level depth analysis | ~10K tokens |
| `--ultrathink` | Critical market analysis with maximum depth | ~32K tokens |

### 📦 Token Optimization
| Flag | Alias | Description |
|------|-------|-------------|
| `--uc` | `--ultracompressed` | Activate UltraCompressed mode (huge token reduction) |

### 🔧 MCP Server Control
| Flag | Description |
|------|-------------|
| `--motherduck` | Enable MotherDuck for data analytics & SQL validation |
| `--hubspot` | Enable HubSpot for CRM & customer insights |
| `--google-analytics` | Enable Google Analytics for web metrics |
| `--seq` | Enable Sequential thinking analysis |
| `--magic` | Enable Magic for content generation & creative |
| `--pup` | Enable Puppeteer for A/B testing & automation |
| `--all-mcp` | Enable all MCP servers for maximum capability |
| `--no-mcp` | Disable all MCP servers (native tools only) |
| `--no-motherduck` | Disable MotherDuck specifically |
| `--no-seq` | Disable Sequential thinking specifically |
| `--no-magic` | Disable Magic content generation specifically |
| `--no-pup` | Disable Puppeteer specifically |

### 🔍 Analysis & Brand Compliance
| Flag | Description |
|------|-------------|
| `--brand-audit` | Enable comprehensive brand compliance checking |

### 📋 Planning & Execution
| Flag | Description |
|------|-------------|
| `--plan` | Show detailed execution plan before running |
| `--dry-run` | Preview changes without execution |
| `--watch` | Continuous monitoring with real-time feedback |
| `--interactive` | Step-by-step guided process |
| `--force` | Override safety checks (use with caution) |

### ✅ Quality & Validation
| Flag | Description |
|------|-------------|
| `--validate` | Enhanced pre-execution safety checks |
| `--brand` | Brand compliance-focused analysis and validation |
| `--coverage` | Generate comprehensive analysis coverage |
| `--strict` | Zero-tolerance mode with enhanced validation |

### 📊 Marketing-Specific Flags
| Flag | Description |
|------|-------------|
| `--ab-test` | A/B testing setup and analysis |
| `--campaign-launch` | Full campaign launch workflow |
| `--content-calendar` | Content calendar planning and execution |
| `--customer-journey` | Customer journey mapping and optimization |

---

## Marketing Personas as Flags

All marketing personas are now integrated as flags, available on every command:

| Persona Flag | Expertise | Best For |
|--------------|-----------|----------|
| `--persona-product-marketer` | Market positioning, competitive analysis | Go-to-market strategy, positioning |
| `--persona-growth-marketer` | A/B testing, conversion optimization | Growth experiments, funnel analysis |
| `--persona-content-creator` | Creative content, multi-channel | Social media, creative campaigns |
| `--persona-technical-writer` | Documentation, user guides | API docs, help content |
| `--persona-editor` | Content quality, brand compliance | Content review, style consistency |
| `--persona-brand-strategist` | Brand strategy, narrative | Brand positioning, voice guidelines |
| `--persona-sql-auditor` | Data validation, SQL optimization | Analytics validation, data quality |

---

## Complete Command Reference

### 🚀 Campaign & Strategy Commands (4)

#### `/analyze` - Multi-Dimensional Marketing Analysis
Comprehensive analysis of campaigns, audiences, competitors, and performance data.

**Command-Specific Flags:**
- `--campaign` - Campaign performance and optimization analysis
- `--brand` - Brand consistency and compliance analysis
- `--audience` - Customer segmentation and behavior analysis
- `--competitive` - Market positioning and competitive analysis
- `--content` - Content performance and engagement analysis
- `--funnel` - Conversion funnel analysis and optimization

**Examples:**
```bash
/analyze --campaign --motherduck --persona-growth-marketer    # Campaign performance analysis
/analyze --competitive --seq --persona-product-marketer      # Strategic competitive analysis
/analyze --funnel --conversion --motherduck                  # Conversion funnel analysis
```

#### `/build` - Marketing Campaign and Content Builder
Build comprehensive marketing campaigns, content, and strategies.

**Command-Specific Flags:**
- `--campaign` - Build complete marketing campaigns
- `--content` - Create engaging marketing content
- `--strategy` - Develop marketing strategy and positioning

**Campaign Types:**
- `--product-launch` - Product launch campaign development
- `--brand-awareness` - Brand awareness campaign creation
- `--lead-generation` - Lead generation campaign building
- `--customer-retention` - Customer retention campaign development

**Examples:**
```bash
/build --campaign --motherduck --magic --hubspot            # Data-driven campaign
/build --content --magic --persona-content-creator         # Creative content creation
/build --strategy --positioning --seq                      # Strategic planning
```

#### `/design` - Brand and Campaign Strategy
Strategic brand development and campaign architecture.

**Command-Specific Flags:**
- `--brand` - Brand strategy and identity development
- `--campaign` - Campaign architecture and strategy
- `--customer-journey` - Customer journey mapping
- `--messaging` - Messaging framework development

**Examples:**
```bash
/design --brand --narrative --persona-brand-strategist     # Brand strategy development
/design --customer-journey --touchpoints --hubspot        # Customer journey mapping
```

#### `/test` - A/B Testing and Optimization Framework
Comprehensive marketing testing and optimization.

**Command-Specific Flags:**
- `--ab-test` - A/B testing workflow with statistical analysis
- `--content` - Content performance testing
- `--campaign` - Campaign performance testing
- `--landing-page` - Landing page optimization testing
- `--email` - Email campaign testing
- `--conversion` - Conversion rate optimization testing

**Examples:**
```bash
/test --ab-test --pup --statistical --persona-growth-marketer  # A/B testing
/test --landing-page --conversion --pup                       # Landing page testing
/test --content --engagement --google-analytics               # Content testing
```

### 📝 Content & Brand Commands (3)

#### `/review` - Content and Brand Compliance Review
Comprehensive content review and brand compliance analysis.

**Command-Specific Flags:**
- `--brand` - Brand compliance and consistency review
- `--content` - Content quality and style review
- `--guidelines` - Brand guideline adherence check
- `--consistency` - Cross-platform consistency analysis

**Examples:**
```bash
/review --brand --consistency --persona-brand-strategist    # Brand compliance review
/review --content --quality --persona-editor               # Content quality review
```

#### `/document` - Marketing Documentation Creation
Professional marketing documentation in multiple formats.

**Command-Specific Flags:**
- `--brand-guidelines` - Brand guideline documentation
- `--content-calendar` - Content calendar documentation
- `--campaign-playbook` - Campaign playbook creation
- `--user-guide` - User-facing documentation

**Examples:**
```bash
/document --brand-guidelines --visual --persona-brand-strategist  # Brand guidelines
/document --user-guide --interactive --persona-technical-writer  # User documentation
```

#### `/improve` - Content and Campaign Optimization
Evidence-based improvements with measurable outcomes.

**Command-Specific Flags:**
- `--content` - Content optimization and enhancement
- `--campaign` - Campaign performance optimization
- `--conversion` - Conversion rate optimization
- `--brand` - Brand alignment and consistency improvements

**Examples:**
```bash
/improve --conversion --data-driven --persona-growth-marketer   # Conversion optimization
/improve --brand --alignment --persona-brand-strategist        # Brand optimization
```

### 📊 Analytics & Data Commands (4)

#### `/validate` - Data Quality and SQL Validation
Comprehensive data validation and SQL quality assurance.

**Command-Specific Flags:**
- `--sql` - SQL query validation and optimization
- `--data` - Data quality and accuracy validation
- `--performance` - Query performance optimization
- `--analytics` - Analytics setup and validation

**Examples:**
```bash
/validate --sql --performance --persona-sql-auditor        # SQL validation
/validate --analytics --tracking --google-analytics       # Analytics validation
```

#### `/scan` - Performance and Compliance Auditing
Comprehensive auditing of marketing performance and compliance.

**Command-Specific Flags:**
- `--performance` - Campaign and content performance audit
- `--compliance` - Brand and legal compliance scanning
- `--quality` - Content and campaign quality validation

**Examples:**
```bash
/scan --performance --comprehensive --motherduck           # Performance audit
/scan --compliance --brand --strict                       # Compliance audit
```

#### `/estimate` - Campaign Planning and Budgeting
Professional estimation for marketing campaigns and projects.

**Command-Specific Flags:**
- `--campaign` - Campaign budget and timeline estimation
- `--roi` - ROI projection and analysis
- `--resources` - Resource requirement planning

**Examples:**
```bash
/estimate --campaign --detailed --roi --motherduck         # Campaign estimation
/estimate --resources --timeline --complexity              # Resource planning
```

#### `/troubleshoot` - Marketing Analytics Debugging
Systematic debugging of marketing analytics and campaign issues.

**Command-Specific Flags:**
- `--analytics` - Analytics tracking and data issues
- `--campaign` - Campaign performance troubleshooting
- `--attribution` - Marketing attribution debugging

**Examples:**
```bash
/troubleshoot --analytics --investigate --motherduck       # Analytics debugging
/troubleshoot --campaign --performance --seq               # Campaign troubleshooting
```

### ⚙️ Operations Commands (4)

#### `/deploy` - Campaign Launch and Management
Safe campaign deployment with monitoring capabilities.

**Command-Specific Flags:**
- `--campaign` - Campaign launch and deployment
- `--content` - Content publishing and distribution
- `--monitor` - Post-launch monitoring setup

**Examples:**
```bash
/deploy --campaign --monitor --validate                    # Safe campaign launch
/deploy --content --multi-channel --schedule              # Content deployment
```

#### `/migrate` - Platform and Data Migrations
Safe migrations of marketing platforms and data.

**Command-Specific Flags:**
- `--platform` - Marketing platform migrations
- `--data` - Customer and campaign data migrations
- `--content` - Content and asset migrations

**Examples:**
```bash
/migrate --platform --backup --validate                   # Platform migration
/migrate --data --hubspot --motherduck                   # Data migration
```

#### `/cleanup` - Campaign and Asset Maintenance
Professional cleanup of marketing assets and campaigns.

**Command-Specific Flags:**
- `--campaigns` - Clean up old campaigns and assets
- `--content` - Remove outdated content and files
- `--data` - Clean up marketing data and analytics

**Examples:**
```bash
/cleanup --campaigns --dry-run                           # Preview campaign cleanup
/cleanup --content --assets --validate                   # Content cleanup
```

#### `/git` - Version Control for Marketing Assets
Professional Git operations for marketing asset management.

**Command-Specific Flags:**
- `--assets` - Marketing asset version control
- `--campaigns` - Campaign version management
- `--content` - Content version control

**Examples:**
```bash
/git --checkpoint "before campaign launch"               # Safety checkpoint
/git --commit --validate --assets                       # Commit marketing assets
```

---

## Flag Combinations & Best Practices

### 🚀 Professional Marketing Workflows

**Product Launch Campaign**
```bash
/analyze --market --competitive --persona-product-marketer
/build --campaign --product-launch --magic --hubspot
/test --landing-page --conversion --pup
/deploy --campaign --monitor --validate
```

**Brand Consistency Audit**
```bash
/analyze --brand --compliance --persona-brand-strategist
/review --brand --consistency --strict
/improve --brand --alignment --iterate
/validate --guidelines --zero-tolerance
```

**Growth Optimization Campaign**
```bash
/analyze --funnel --conversion --motherduck --persona-growth-marketer
/test --ab-test --statistical --pup
/improve --conversion --data-driven --iterate
/validate --performance --roi
```

**Content Marketing Strategy**
```bash
/analyze --audience --segmentation --hubspot --persona-content-creator
/build --content-calendar --seo --magic
/test --content --engagement --google-analytics
/document --style-guide --brand
```

### 💡 Best Practices

1. **Always validate risky operations**
   ```bash
   /deploy --campaign --validate --plan
   /migrate --data --dry-run --backup
   ```

2. **Use personas for specialized expertise**
   ```bash
   /analyze --campaign --persona-growth-marketer
   /review --brand --persona-brand-strategist
   ```

3. **Combine MCP servers for maximum capability**
   ```bash
   /build --campaign --motherduck --hubspot --magic
   /test --ab-test --pup --google-analytics
   ```

4. **Progressive thinking for complex marketing tasks**
   ```bash
   /analyze --competitive --think
   /build --strategy --think-hard
   /analyze --market --ultrathink
   ```

### 🎯 Quick Reference

**High-Risk Operations**: Always use `--validate` or `--dry-run`
**Data Analysis Tasks**: Enable `--motherduck` for analytics
**Customer Research**: Use `--hubspot` for CRM insights
**Content Creation**: Enable `--magic` for creative generation
**A/B Testing**: Use `--pup` for browser automation
**Web Analytics**: Enable `--google-analytics` for metrics
**Token Saving**: Add `--uc` for 70% reduction

### 📊 Marketing-Specific Combinations

**Campaign Performance Analysis**
```bash
/analyze --campaign --motherduck --google-analytics --persona-growth-marketer
```

**Brand Compliance Review**
```bash
/review --brand --consistency --strict --persona-brand-strategist
```

**Content Creation Workflow**
```bash
/build --content --magic --hubspot --persona-content-creator
```

**Data Validation Process**
```bash
/validate --sql --performance --motherduck --persona-sql-auditor
```

**A/B Testing Campaign**
```bash
/test --ab-test --pup --statistical --persona-growth-marketer
```

---

**SuperClaude v0.0.1 Marketing Edition** - 14 marketing commands | 7 marketing personas | Advanced MCP integration | Evidence-based marketing methodology