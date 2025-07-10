**Purpose**: Multi-dimensional marketing and campaign analysis

---

@include shared/universal-constants.yml#Universal_Legend

## Command Execution
Execute: immediate. --plan→show plan first
Legend: Generated based on symbols used in command
Purpose: "[Action][Subject] in $ARGUMENTS"

Multi-dimensional analysis on campaigns, content, audience, or performance data in $ARGUMENTS.

@include shared/flag-inheritance.yml#Universal_Always

Examples:
- `/analyze --campaign --motherduck` - Campaign performance analysis with data
- `/analyze --brand --seq` - Deep brand consistency analysis  
- `/analyze --audience --hubspot --think` - Comprehensive audience segmentation
- `/analyze --competitive --think-hard` - Strategic competitive analysis

Analysis modes:

**--campaign:** Performance review→metrics, conversion, ROI | Issues→underperformance, attribution, targeting | Optimization→A/B tests, segments, channels | Trends→growth, seasonal, lifecycle

**--brand:** Brand consistency & compliance | Voice alignment across channels | Visual identity usage | Message coherence assessment | Brand guideline adherence

**--audience:** Customer segmentation & behavior | Journey mapping & touchpoints | Engagement patterns & preferences | Conversion funnel analysis | Persona validation & insights

**--competitive:** Market positioning & differentiation | Competitive messaging & strategy | Share of voice & presence | Campaign tactics & performance | Opportunity identification

**--content:** Performance metrics & engagement | Brand voice consistency | SEO optimization & ranking | Social sharing & virality | Conversion attribution & optimization

**--funnel:** Conversion path analysis | Drop-off point identification | Attribution modeling | Customer journey optimization | Multi-touch analysis

## MCP Integration Patterns

**MotherDuck Integration:**
- Campaign performance data extraction and analysis
- Customer behavior pattern analysis
- ROI and attribution modeling
- Cohort analysis and retention metrics

**HubSpot Integration:**
- Customer segmentation and persona analysis
- Lead scoring and qualification analysis
- Campaign attribution and pipeline analysis
- Customer lifecycle and journey mapping

**Google Analytics Integration:**
- Website performance and user behavior analysis
- Content engagement and conversion analysis
- Traffic source attribution and optimization
- Goal completion and funnel analysis

**Sequential Analysis:**
- Complex strategic market analysis
- Multi-factor competitive positioning
- Customer journey optimization strategies
- Campaign performance root cause analysis

## Marketing Persona Activation

Auto-activates appropriate personas based on analysis type:
- Campaign analysis → Growth Marketer persona
- Brand analysis → Brand Strategist persona  
- Content analysis → Content Creator persona
- Audience analysis → Product Marketer persona
- Performance analysis → SQL Auditor persona

@include shared/marketing-quality-patterns.yml#Marketing_Severity_Levels

## Output Standards

Analysis reports include:
- **Executive Summary**: Key findings and recommendations
- **Data Sources**: All data sources with timestamps and links
- **Evidence**: Supporting metrics and visualizations
- **Recommendations**: Prioritized action items with expected impact
- **Next Steps**: Specific implementation guidance

@include shared/marketing-docs-patterns.yml#Documentation_Quality