**Purpose**: Universal marketing campaign and content builder

---

@include shared/universal-constants.yml#Universal_Legend

## Command Execution
Execute: immediate. --plan→show plan first
Legend: Generated based on symbols used in command
Purpose: "[Action][Subject] in $ARGUMENTS"

Build marketing campaigns, content, or strategies based on requirements in $ARGUMENTS.

@include shared/flag-inheritance.yml#Universal_Always

Examples:
- `/build --campaign --motherduck --magic` - Data-driven campaign with creative assets
- `/build --content --magic --hubspot` - Personalized content with customer data
- `/build --strategy --seq --competitive` - Strategic planning with market analysis

Pre-build: Remove outdated assets (old campaigns, deprecated content) | Clean temp files & cache | Validate brand compliance | Remove test content

Build modes:
**--campaign:** Complete marketing campaign | Strategy→tactics→creative→launch | Multi-channel execution | Performance tracking setup
**--content:** Content creation workflow | Brand-aligned messaging | Multi-format output | Distribution optimization  
**--strategy:** Strategic planning process | Market research→positioning→tactics | Evidence-based approach

Templates:
- **Product Launch:** GTM strategy|positioning|messaging|content calendar|performance tracking
- **Brand Campaign:** Brand strategy|voice guidelines|visual identity|content framework|measurement
- **Content Marketing:** Content strategy|editorial calendar|SEO optimization|social distribution|performance analysis
- **Growth Campaign:** Funnel analysis|optimization strategy|A/B testing framework|conversion tracking|scaling plan

## Campaign Types

**Product Launch Campaign:**
- Market research and competitive analysis
- Target audience definition and persona development
- Value proposition and messaging framework
- Multi-channel launch strategy and timeline
- Content creation and asset development
- Performance tracking and optimization plan

**Brand Awareness Campaign:**
- Brand positioning and differentiation strategy
- Brand voice and visual identity guidelines
- Storytelling framework and content themes
- Influencer and partnership strategies
- Social media and content distribution plan
- Brand tracking and sentiment monitoring

**Lead Generation Campaign:**
- Lead magnet strategy and content development
- Landing page optimization and conversion flow
- Email nurturing sequences and automation
- Sales and marketing alignment processes
- Lead scoring and qualification frameworks
- ROI tracking and attribution modeling

**Customer Retention Campaign:**
- Customer lifecycle mapping and segmentation
- Personalization and targeting strategies
- Customer success content and communications
- Loyalty program development and optimization
- Feedback collection and experience improvement
- Lifetime value optimization and growth

## Content Creation Workflows

**Blog Content:**
- SEO keyword research and content planning
- Editorial calendar development and management
- Brand voice and style guide implementation
- Content optimization for search and social
- Performance tracking and content analytics

**Social Media Content:**
- Platform-specific content strategies and formats
- Visual brand identity and creative templates
- Community management and engagement tactics
- Influencer collaboration and partnership content
- Social media advertising and promoted content
- Performance analytics and optimization

**Email Marketing:**
- Email strategy and audience segmentation
- Template design and brand compliance
- Automation workflows and trigger sequences
- Personalization and dynamic content strategies
- Performance optimization and A/B testing

**Video Content:**
- Video strategy and content planning
- Scriptwriting and storyboard development
- Brand guideline implementation for video
- Distribution and promotion strategies
- Performance tracking and optimization

## MCP Integration Patterns

**Magic Content Generation:**
- Creative asset development with brand alignment
- Multi-format content creation and optimization
- Template generation for consistent brand application
- Visual content and design element creation

**MotherDuck Analytics:**
- Performance data analysis for content optimization
- Audience behavior insights for content strategy
- ROI analysis and attribution modeling
- Campaign performance benchmarking and forecasting

**HubSpot Integration:**
- Customer data integration for personalization
- Lead nurturing and conversion optimization
- Campaign attribution and pipeline analysis
- Customer journey mapping and optimization

**Puppeteer Testing:**
- Landing page performance and conversion testing
- Email template rendering and compatibility testing
- Social media content preview and optimization
- Campaign asset quality assurance and validation

## Marketing Persona Activation

Auto-activates appropriate personas based on build type:
- Campaign builds → Growth Marketer persona
- Content builds → Content Creator persona
- Strategy builds → Product Marketer or Brand Strategist persona
- Brand builds → Brand Strategist persona

@include shared/marketing-quality-patterns.yml#Brand_Validation_Sequence

## Quality Assurance

All builds include:
- **Brand Compliance Check**: Adherence to brand guidelines and voice
- **Performance Baseline**: Benchmark metrics and success criteria
- **Content Quality Review**: Grammar, accuracy, and brand alignment
- **Technical Validation**: Asset optimization and compatibility testing
- **Launch Readiness**: Complete checklist and approval workflow

@include shared/marketing-docs-patterns.yml#Campaign_Report_Template