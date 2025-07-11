# SuperClaude Technical Writing Commands Reference v0.0.1

## Table of Contents
- [Quick Start](#quick-start)
- [Universal Flags (Available on ALL Commands)](#universal-flags-available-on-all-commands)
- [Technical Writer Persona](#technical-writer-persona)
- [Complete Command Reference](#complete-command-reference)
- [Flag Combinations & Best Practices](#flag-combinations--best-practices)

---

## Quick Start

**Basic Usage**: `/command [flags] [arguments]`

**Example Commands**:
```bash
/analyze --code --motherduck --sequential              # Code analysis with data validation
/build --docs --context7 --puppeteer                   # Documentation build with testing
/explain --code --step-by-step --context7              # Code explanation with standards
/validate --sql --performance --motherduck             # SQL validation and optimization
/test --documentation --accessibility --puppeteer      # Documentation testing
/design --api --sequential --think-hard                # API design with deep analysis
```

---

## Universal Flags (Available on ALL Commands)

### 🧠 Thinking Depth Control
| Flag | Description | Token Usage |
|------|-------------|-------------|
| `--think` | Multi-dimensional analysis with expanded context | ~4K tokens |
| `--think-hard` | Strategic-level depth analysis | ~10K tokens |
| `--ultrathink` | Critical analysis with maximum depth | ~32K tokens |

### 📦 Token Optimization
| Flag | Alias | Description |
|------|-------|-------------|
| `--uc` | `--ultracompressed` | Activate UltraCompressed mode (huge token reduction) |

### 🔧 MCP Server Control
| Flag | Description |
|------|-------------|
| `--motherduck` | Enable MotherDuck for data analytics & SQL validation |
| `--puppeteer` | Enable Puppeteer for testing & automation |
| `--sequential` | Enable Sequential thinking analysis |
| `--context7` | Enable Context7 for documentation standards |
| `--all-mcp` | Enable all MCP servers for maximum capability |
| `--no-mcp` | Disable all MCP servers (native tools only) |

### 🔍 Analysis & Quality Control
| Flag | Description |
|------|-------------|
| `--technical-audit` | Enable comprehensive technical quality checking |

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
| `--coverage` | Generate comprehensive analysis coverage |
| `--strict` | Zero-tolerance mode with enhanced validation |

### 📊 Technical Writing Specific Flags
| Flag | Description |
|------|-------------|
| `--step-by-step` | Detailed step-by-step explanations |
| `--keywords` | Include keyword definitions and breakdowns |
| `--accessibility` | Focus on accessibility compliance |
| `--progressive` | Progressive complexity building |

---

## Technical Writer Persona

The technical writer persona is automatically activated for all commands, providing:

| Focus Area | Capabilities |
|------------|-------------|
| **Documentation Excellence** | Clear, progressive explanations with keyword definitions |
| **Code Explanation** | Code → Keywords → Steps → Context structure |
| **User-Centered Design** | Audience-first approach with accessibility focus |
| **Quality Assurance** | Technical accuracy and usability validation |

---

## Complete Command Reference

### 🔍 Analysis Commands (2)

#### `/analyze` - Technical Analysis
Comprehensive analysis of code, architecture, documentation, and system performance.

**Command-Specific Flags:**
- `--code` - Code quality, structure, and security analysis
- `--architecture` - System design patterns and relationships
- `--documentation` - Content clarity, accuracy, and completeness
- `--performance` - System bottlenecks and optimization
- `--security` - Vulnerability assessment and best practices
- `--dependencies` - Package analysis and compatibility

**Examples:**
```bash
/analyze --code --motherduck --security                # Code analysis with data validation
/analyze --architecture --sequential --think-hard      # Deep architectural analysis
/analyze --documentation --context7 --accessibility    # Documentation quality review
```

#### `/explain` - Code and Concept Explanation
Clear, progressive explanations of code, technical concepts, and systems.

**Command-Specific Flags:**
- `--code` - Code breakdown with syntax and structure
- `--concept` - Technical concept explanation
- `--architecture` - System architecture explanation
- `--api` - API functionality and documentation
- `--algorithm` - Algorithm analysis and breakdown
- `--database` - Database schema and query explanation

**Depth Levels:**
- `--basic` - Fundamental concepts and simple examples
- `--intermediate` - Detailed analysis with practical examples
- `--advanced` - Comprehensive deep-dive analysis
- `--expert` - Complete technical analysis with edge cases

**Examples:**
```bash
/explain --code --step-by-step --keywords              # Code explanation with structure
/explain --concept --progressive --context7            # Technical concept breakdown
/explain --api --documentation --motherduck            # API explanation with data
```

### 🔨 Build Commands (2)

#### `/build` - Technical Documentation and Projects
Build technical documentation, code projects, and development environments.

**Command-Specific Flags:**
- `--docs` - Technical documentation sites and references
- `--project` - Code project setup and development environment
- `--api` - API documentation and specifications

**Documentation Types:**
- `--api-docs` - OpenAPI specs and SDK documentation
- `--user-guides` - Step-by-step tutorials and getting started
- `--developer-docs` - Architecture and development documentation
- `--technical-specs` - System requirements and specifications

**Examples:**
```bash
/build --docs --context7 --puppeteer                  # Documentation with testing
/build --api --sequential --motherduck                # API documentation with analysis
/build --project --technical-specs --think-hard       # Complete project setup
```

#### `/design` - Technical Architecture and System Design
Design technical architecture, APIs, and system components.

**Command-Specific Flags:**
- `--api` - REST, GraphQL, or RPC API design
- `--architecture` - System architecture and design patterns
- `--database` - Database schema and data modeling
- `--documentation` - Documentation architecture and organization
- `--security` - Security architecture and protocols
- `--performance` - Performance optimization and monitoring

**Examples:**
```bash
/design --api --sequential --openapi                  # API design with analysis
/design --architecture --think-hard --scalability     # System architecture design
/design --database --motherduck --optimization        # Database design with analysis
```

### 🧪 Testing & Validation Commands (2)

#### `/test` - Comprehensive Testing Framework
Create and run tests for code, documentation, and systems.

**Command-Specific Flags:**
- `--unit` - Unit testing and code coverage
- `--integration` - Integration testing across components
- `--e2e` - End-to-end testing with user scenarios
- `--performance` - Performance testing and benchmarking
- `--security` - Security testing and vulnerability assessment
- `--accessibility` - Accessibility compliance testing
- `--documentation` - Documentation accuracy and usability testing

**Examples:**
```bash
/test --unit --coverage --motherduck                  # Unit testing with coverage
/test --documentation --accessibility --puppeteer     # Documentation testing
/test --performance --load --sequential               # Performance testing
```

#### `/validate` - Technical Validation
Validate code quality, data integrity, and system performance.

**Command-Specific Flags:**
- `--sql` - SQL query validation and optimization
- `--code` - Code quality and best practices validation
- `--documentation` - Documentation quality and accuracy
- `--api` - API functionality and security validation
- `--data` - Data quality and integrity validation
- `--performance` - System performance validation

**Examples:**
```bash
/validate --sql --performance --motherduck            # SQL validation with optimization
/validate --documentation --accessibility --context7  # Documentation validation
/validate --api --security --puppeteer               # API security validation
```

### 📝 Documentation Commands (2)

#### `/document` - Professional Documentation Creation
Create comprehensive technical documentation in multiple formats.

**Command-Specific Flags:**
- `--api` - API documentation generation
- `--user` - End-user documentation and guides
- `--developer` - Developer documentation and guides
- `--architecture` - System architecture documentation

**Formats:**
- `--markdown` - Markdown format (default)
- `--html` - HTML documentation
- `--pdf` - PDF output
- `--interactive` - Interactive documentation

**Examples:**
```bash
/document --api --openapi --interactive               # Interactive API documentation
/document --user --step-by-step --accessibility       # User guide with accessibility
/document --architecture --diagrams --comprehensive   # Architecture documentation
```

#### `/review` - Code and Documentation Review
Comprehensive review of code, documentation, and technical content.

**Command-Specific Flags:**
- `--code` - Code quality and structure review
- `--documentation` - Documentation quality and accuracy
- `--security` - Security review and vulnerability assessment
- `--performance` - Performance review and optimization
- `--accessibility` - Accessibility compliance review

**Examples:**
```bash
/review --code --security --best-practices            # Code security review
/review --documentation --accessibility --usability   # Documentation quality review
/review --performance --optimization --motherduck     # Performance review
```

### 🔧 Utility Commands (9)

#### `/improve` - Code and Documentation Optimization
Evidence-based improvements with measurable outcomes.

**Command-Specific Flags:**
- `--code` - Code optimization and refactoring
- `--documentation` - Documentation clarity and structure
- `--performance` - Performance optimization
- `--accessibility` - Accessibility improvements

#### `/scan` - Security and Quality Scanning
Comprehensive security and quality auditing.

**Command-Specific Flags:**
- `--security` - Security vulnerability scanning
- `--quality` - Code and documentation quality validation
- `--performance` - Performance audit and analysis

#### `/troubleshoot` - Technical Problem Solving
Systematic debugging and problem resolution.

**Command-Specific Flags:**
- `--code` - Code debugging and issue resolution
- `--performance` - Performance troubleshooting
- `--security` - Security issue investigation

#### `/deploy` - System Deployment
Safe deployment with monitoring capabilities.

#### `/migrate` - Data and System Migrations
Safe migrations with validation and backup.

#### `/cleanup` - Code and Documentation Maintenance
Professional cleanup and maintenance operations.

#### `/git` - Version Control Operations
Professional Git operations for code and documentation.

#### `/estimate` - Project Planning and Estimation
Professional estimation for technical projects.

#### `/task` - Task Management
Task creation, tracking, and management.

---

## Flag Combinations & Best Practices

### 🚀 Professional Technical Writing Workflows

**API Documentation Creation**
```bash
/design --api --sequential --openapi                  # API design with analysis
/build --api --docs --context7 --puppeteer           # Documentation build with testing
/test --api --documentation --accessibility           # API testing and validation
/validate --api --security --performance              # API validation
```

**Code Documentation Workflow**
```bash
/analyze --code --architecture --security             # Code analysis
/explain --code --step-by-step --keywords             # Code explanation
/document --developer --comprehensive --interactive    # Developer documentation
/test --documentation --usability --puppeteer         # Documentation testing
```

**Technical Architecture Design**
```bash
/analyze --architecture --performance --scalability   # Architecture analysis
/design --architecture --think-hard --sequential      # Architecture design
/document --architecture --diagrams --comprehensive   # Architecture documentation
/validate --architecture --security --performance     # Architecture validation
```

**Database Documentation**
```bash
/analyze --database --performance --motherduck        # Database analysis
/design --database --optimization --sequential        # Database design
/document --database --schema --queries               # Database documentation
/validate --sql --performance --motherduck           # SQL validation
```

### 💡 Best Practices

1. **Always validate technical operations**
   ```bash
   /validate --code --security --performance
   /test --documentation --accessibility --usability
   ```

2. **Use progressive explanations for complex topics**
   ```bash
   /explain --concept --progressive --step-by-step
   /document --user --tutorial --accessibility
   ```

3. **Combine MCP servers for maximum capability**
   ```bash
   /build --docs --context7 --puppeteer --motherduck
   /analyze --code --sequential --motherduck
   ```

4. **Use deep thinking for complex technical tasks**
   ```bash
   /analyze --architecture --think-hard
   /design --api --ultrathink --sequential
   ```

### 🎯 Quick Reference

**Code Analysis**: Use `--motherduck` for data validation
**Documentation**: Use `--context7` for standards compliance
**Testing**: Use `--puppeteer` for browser automation and testing
**Complex Analysis**: Use `--sequential` for multi-step thinking
**Accessibility**: Always include `--accessibility` for user-facing content
**Token Saving**: Add `--uc` for 70% reduction

### 📊 Technical Writing Specific Combinations

**Code Explanation with Documentation**
```bash
/explain --code --step-by-step --keywords --context7
```

**API Documentation with Testing**
```bash
/build --api --docs --context7 --puppeteer --validate
```

**Technical Content Validation**
```bash
/validate --documentation --accessibility --usability --context7
```

**Database Analysis and Documentation**
```bash
/analyze --database --motherduck --performance --sequential
```

**Security Review with Documentation**
```bash
/review --security --comprehensive --document --best-practices
```

---

**SuperClaude v0.0.1 Technical Writing Edition** - 19 technical commands | Technical writer persona | MCP integration (MotherDuck, Puppeteer, Sequential, Context7) | Documentation excellence methodology