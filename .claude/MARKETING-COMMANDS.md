# SuperClaude Marketing Copy Workflow Commands v0.1.0

## Table of Contents
- [Marketing Workflow Overview](#marketing-workflow-overview)
- [Marketing Command Reference](#marketing-command-reference)
- [Workflow Integration Examples](#workflow-integration-examples)
- [Best Practices](#best-practices)

---

## Marketing Workflow Overview

SuperClaude now includes a comprehensive 10-step marketing copy workflow:

1. **Research** (`/research`) - Web and internal document discovery
2. **Templates** (`/template`) - Content templates for different document types  
3. **Library** (`/library`) - Content library indexing and management
4. **Outline** (`/outline`) - Content outline generation
5. **Write** (`/write`) - Article writing with progressive development
6. **Refine** (`/refine`) - Content refinement against references
7. **Diagrams** (`/diagram`) - SVG diagram generation and placement
8. **Audit** (`/audit-code`) - Code snippet accuracy auditing
9. **Publish** (`/publish`) - Strapi CMS integration and publishing
10. **Analytics** (extends existing `/analyze`) - Performance tracking and optimization

---

## Marketing Command Reference

### 🔍 Research & Discovery Commands

#### `/research` - Content Research and Discovery
Comprehensive research tool for finding and analyzing web content and internal documents.

**Source Types:**
- `--web` - Search web for relevant content and trends
- `--internal` - Search internal document library and codebase  
- `--competitors` - Analyze competitor content and messaging
- `--industry` - Research industry trends and insights
- `--customers` - Research customer feedback and testimonials

**Research Depth:**
- `--surface` - Quick overview and key points
- `--deep` - Comprehensive analysis with detailed insights
- `--market-intel` - Strategic market intelligence gathering

**Examples:**
```bash
/research --web --industry --competitors --deep --sequential
/research --internal --technical --product --motherduck
/research --customers --case-studies --testimonials --think-hard
```

### 📝 Content Creation Commands

#### `/template` - Content Template System
Comprehensive template system for different marketing document types.

**Document Types:**
- `--memo` - Internal memos and briefings
- `--brief` - Marketing briefs and strategy documents
- `--blog` - Blog posts and thought leadership
- `--case-study` - Customer success stories
- `--whitepaper` - Technical whitepapers and guides
- `--press-release` - Press releases and announcements
- `--email` - Email campaigns and newsletters
- `--social` - Social media content and posts
- `--landing-page` - Landing page copy and content

**Content Style:**
- `--technical` - Technical audience focus
- `--executive` - Executive and decision-maker focus
- `--developer` - Developer and technical implementer focus
- `--customer` - End-user and customer focus

**Examples:**
```bash
/template --blog --technical --outline --examples --context7
/template --case-study --customer --sections --testimonials
/template --whitepaper --executive --comprehensive --think-hard
```

#### `/outline` - Content Outline Generation
Strategic content outline generation with progressive article development.

**Outline Types:**
- `--blog` - Blog post outline structure
- `--whitepaper` - Technical whitepaper outline
- `--case-study` - Customer success story outline
- `--tutorial` - Step-by-step tutorial outline
- `--announcement` - Product/feature announcement outline

**Content Strategy:**
- `--seo-focused` - SEO-optimized content structure
- `--engagement` - Engagement and conversion optimized
- `--thought-leadership` - Authority and expertise positioning
- `--technical-depth` - Deep technical content focus

**Examples:**
```bash
/outline --blog --detailed --seo-focused --sequential
/outline --whitepaper --comprehensive --technical-depth --think-hard
/outline --case-study --detailed --engagement --customer-focused
```

#### `/write` - Article Writing System
Progressive article writing system that builds on outlines and research.

**Writing Modes:**
- `--draft` - Initial draft generation
- `--sections` - Write specific sections
- `--expand` - Expand existing content
- `--refine` - Refine and improve existing draft

**Content Quality:**
- `--technical-accuracy` - Ensure technical correctness
- `--brand-voice` - Maintain consistent brand voice
- `--seo-optimized` - Include SEO best practices
- `--engagement` - Focus on reader engagement

**Integration Sources:**
- `--research` - Use research findings
- `--library` - Leverage existing content library
- `--examples` - Include code examples and snippets
- `--testimonials` - Add customer testimonials

**Examples:**
```bash
/write --draft --research --library --technical-accuracy
/write --sections --technical --examples --code-snippets
/write --refine --brand-voice --engagement --seo-optimized
```

### 📚 Content Management Commands

#### `/library` - Content Library Management
Comprehensive system for indexing, organizing, and leveraging existing content.

**Content Sources:**
- `--codebase` - Index code documentation and comments
- `--docs` - Technical documentation and API references
- `--blogs` - Existing blog posts and articles
- `--partners` - Partner blogs and collaborative content
- `--marketing` - Existing marketing materials and campaigns

**Indexing Operations:**
- `--scan` - Scan and index new content
- `--update` - Update existing content index
- `--search` - Search indexed content library
- `--analyze` - Analyze content gaps and opportunities
- `--extract` - Extract reusable content snippets

**Examples:**
```bash
/library --codebase --scan --technical --motherduck
/library --search --customers --case-studies --performance
/library --analyze --gaps --technical --developers --sequential
```

### 🔧 Quality & Enhancement Commands

#### `/refine` - Content Refinement System
Comprehensive content refinement against research findings and existing content.

**Refinement Types:**
- `--accuracy` - Verify technical accuracy and claims
- `--consistency` - Ensure brand voice and messaging consistency
- `--completeness` - Check content completeness against outline
- `--engagement` - Optimize for reader engagement
- `--conversion` - Optimize for conversion and action

**Reference Sources:**
- `--research` - Validate against research findings
- `--library` - Cross-reference with content library
- `--competitors` - Compare with competitive content
- `--best-practices` - Apply industry best practices
- `--brand-guidelines` - Ensure brand compliance

**Examples:**
```bash
/refine --accuracy --consistency --research --library --context7
/refine --seo --engagement --conversion --best-practices
/refine --brand-guidelines --accessibility --readability
```

#### `/audit-code` - Code Snippet Accuracy Auditor
Comprehensive code auditing system for marketing content code snippets.

**Audit Types:**
- `--syntax` - Syntax validation and error checking
- `--security` - Security vulnerability assessment
- `--performance` - Performance optimization review
- `--best-practices` - Industry best practices compliance
- `--compatibility` - Version and platform compatibility

**Programming Languages:**
- `--javascript` - JavaScript and Node.js code
- `--python` - Python code validation
- `--java` - Java code review
- `--go` - Go language validation
- `--sql` - SQL query validation
- `--bash` - Shell script validation
- `--api` - API endpoint and schema validation

**Examples:**
```bash
/audit-code --comprehensive --javascript --python --security
/audit-code --sql --motherduck --performance --best-practices
/audit-code --production-ready --security --performance --all-languages
```

### 🎨 Visual & Media Commands

#### `/diagram` - SVG Diagram Generation
Advanced SVG diagram generation with intelligent placement suggestions.

**Diagram Types:**
- `--architecture` - System architecture diagrams
- `--flow` - Process flow and workflow diagrams
- `--comparison` - Feature comparison charts
- `--timeline` - Project timeline and roadmap diagrams
- `--infographic` - Data visualization and infographics
- `--network` - Network topology and integration diagrams

**Visual Style:**
- `--minimal` - Clean, minimal design aesthetic
- `--technical` - Technical documentation style
- `--marketing` - Marketing-focused visual design
- `--branded` - Brand-consistent colors and styling
- `--interactive` - Interactive diagram elements

**Examples:**
```bash
/diagram --architecture --technical --detailed --placement
/diagram --flow --minimal --step-by-step --interactive
/diagram --comparison --marketing --branded --features
```

### 🚀 Publishing & Distribution Commands

#### `/publish` - Strapi CMS Integration
Comprehensive Strapi CMS integration for publishing refined marketing content.

**Content Types:**
- `--blog-post` - Blog post content type
- `--case-study` - Customer case study content type
- `--whitepaper` - Technical whitepaper content type
- `--press-release` - Press release content type
- `--landing-page` - Landing page content type

**Publishing Operations:**
- `--draft` - Save as draft in Strapi
- `--publish` - Publish content immediately
- `--schedule` - Schedule for future publication
- `--update` - Update existing content
- `--preview` - Generate preview URL

**Content Processing:**
- `--format` - Auto-format content for Strapi
- `--metadata` - Generate SEO metadata
- `--media` - Process and upload media files
- `--categories` - Auto-categorize content
- `--tags` - Generate relevant tags

**Examples:**
```bash
/publish --blog-post --publish --format --metadata --media
/publish --case-study --draft --categories --tags --seo
/publish --whitepaper --schedule --date "2024-02-01" --format
```

---

## Workflow Integration Examples

### Complete Blog Post Workflow
```bash
# 1. Research phase
/research --web --industry --competitors --deep --sequential

# 2. Create content template
/template --blog --technical --outline --examples --context7

# 3. Generate detailed outline
/outline --blog --detailed --seo-focused --engagement

# 4. Write initial draft
/write --draft --research --library --technical-accuracy

# 5. Generate supporting diagrams
/diagram --architecture --technical --placement --branded

# 6. Audit code snippets
/audit-code --comprehensive --javascript --python --security

# 7. Refine content quality
/refine --accuracy --consistency --seo --engagement --context7

# 8. Publish to Strapi
/publish --blog-post --publish --format --metadata --media
```

### Customer Case Study Creation
```bash
# 1. Research customer and industry
/research --customers --industry --case-studies --deep

# 2. Create case study template
/template --case-study --customer --sections --testimonials

# 3. Search library for supporting content
/library --search --customers --success-stories --performance

# 4. Generate case study outline
/outline --case-study --detailed --engagement --results-focused

# 5. Write comprehensive case study
/write --draft --testimonials --metrics --technical-details

# 6. Create supporting visualizations
/diagram --timeline --results --infographic --branded

# 7. Refine against best practices
/refine --engagement --conversion --brand-guidelines --context7

# 8. Publish as case study
/publish --case-study --publish --categories --social-preview
```

### Technical Whitepaper Development
```bash
# 1. Deep technical research
/research --technical --industry --market-intel --think-hard

# 2. Comprehensive whitepaper template
/template --whitepaper --executive --comprehensive --technical

# 3. Analyze existing technical content
/library --codebase --docs --technical --extract --motherduck

# 4. Create detailed technical outline
/outline --whitepaper --comprehensive --technical-depth --sequential

# 5. Write sections with technical accuracy
/write --sections --technical --examples --research --library

# 6. Generate technical diagrams
/diagram --architecture --flow --technical --detailed

# 7. Comprehensive code audit
/audit-code --production-ready --security --performance --documentation

# 8. Technical accuracy refinement
/refine --accuracy --technical-review --best-practices --context7

# 9. Publish technical whitepaper
/publish --whitepaper --schedule --metadata --technical-tags
```

---

## Best Practices

### 🎯 Workflow Optimization

**Research Phase:**
- Always combine `--web` and `--internal` research for comprehensive coverage
- Use `--deep` analysis for strategic content pieces
- Include `--competitors` for positioning insights

**Content Creation:**
- Start with templates (`/template`) before outline generation
- Use progressive complexity building in outlines
- Integrate research findings throughout writing process

**Quality Assurance:**
- Always audit code snippets before publication
- Refine content against brand guidelines and research
- Validate technical accuracy with appropriate tools

**Publishing:**
- Generate comprehensive metadata for SEO optimization
- Include social media previews and sharing optimization
- Schedule publication during optimal engagement times

### 🔧 MCP Integration Recommendations

**MotherDuck Integration:**
- Use for data validation in research phase
- SQL query optimization in code auditing
- Performance metrics analysis

**Puppeteer Integration:**
- Competitive website analysis during research
- Content accessibility testing
- Social media preview validation

**Sequential Integration:**
- Multi-step analysis for complex content strategies
- Strategic thinking for competitive positioning
- Content workflow optimization

**Context7 Integration:**
- Brand compliance validation throughout workflow
- Style guide consistency checking
- Documentation standards enforcement

### 💡 Content Quality Standards

**Technical Accuracy:**
- All code examples tested and validated
- Technical claims backed by research
- Performance metrics verified with data
- Security recommendations current and compliant

**Brand Consistency:**
- Voice and tone alignment throughout content
- Visual consistency in diagrams and media
- Messaging alignment with brand strategy
- Terminology consistency across content

**SEO Optimization:**
- Keyword research integration in content planning
- Meta description and title optimization
- Header structure and internal linking
- Image optimization and alt text

**Accessibility Compliance:**
- Content readable at appropriate grade level
- Visual elements include descriptive alt text
- Color contrast and visual accessibility
- Screen reader compatibility

---

**SuperClaude Marketing Copy Workflow v0.1.0** - 10-step marketing workflow | Research to publication | Strapi CMS integration | Code auditing | SVG diagram generation | MCP-enhanced quality assurance