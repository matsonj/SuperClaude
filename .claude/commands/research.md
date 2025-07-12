# Marketing Research Tool

## /research - Content Research and Discovery

Comprehensive research tool for finding and analyzing web content and internal documents for marketing copy creation.

### Command-Specific Flags

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

**Content Types:**
- `--technical` - Technical documentation and API references
- `--marketing` - Marketing materials and campaigns
- `--product` - Product documentation and features
- `--case-studies` - Customer success stories and case studies
- `--blog-posts` - Blog content and thought leadership

### Examples

```bash
# Research web content for a new product launch
/research --web --industry --competitors --deep

# Find internal technical content for developer marketing
/research --internal --technical --product --motherduck

# Comprehensive competitor analysis
/research --competitors --marketing --case-studies --think-hard

# Customer research for testimonials and case studies
/research --customers --case-studies --web --sequential
```

### Integration Points

**Web Research:**
- Uses WebSearch for current trends and competitor analysis
- WebFetch for detailed content analysis
- Puppeteer for competitive website analysis

**Internal Research:**
- Indexes codebase documentation
- Searches existing blog posts and marketing materials
- Analyzes partner content and integrations

**Output Format:**
- Structured research reports with source citations
- Content summaries and key insights
- Competitive positioning analysis
- Market opportunity identification