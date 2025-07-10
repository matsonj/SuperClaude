**Purpose**: Comprehensive marketing testing and optimization framework

---

@include shared/universal-constants.yml#Universal_Legend

## Command Execution
Execute: immediate. --plan→show plan first
Legend: Generated based on symbols used in command
Purpose: "[Action][Subject] in $ARGUMENTS"

Create or run comprehensive marketing tests for campaigns, content, or user experiences specified in $ARGUMENTS using modern testing methodologies and analytics.

@include shared/flag-inheritance.yml#Universal_Always

Examples:
- `/test --ab-test --pup` - A/B testing with browser automation
- `/test --content --google-analytics` - Content performance testing
- `/test --campaign --motherduck --coverage` - Campaign performance analysis
- `/test --funnel --conversion` - Conversion funnel testing
- `/test --brand --consistency` - Brand consistency validation

## Command-Specific Flags
--ab-test: "A/B testing workflow (hypothesis→variants→statistical analysis)"
--content: "Content performance testing w/ engagement metrics"
--campaign: "Campaign performance testing across channels"
--funnel: "Conversion funnel testing and optimization"
--landing-page: "Landing page performance and conversion testing"
--email: "Email template and campaign testing"
--social: "Social media content and campaign testing"
--brand: "Brand consistency and compliance testing"
--user-experience: "User experience and usability testing"
--conversion: "Conversion rate optimization testing"

## Testing Methodologies

**A/B Testing Framework:**
- Hypothesis development and test design
- Statistical significance calculations
- Variant creation and traffic allocation
- Performance monitoring and analysis
- Winner determination and implementation

**Multivariate Testing:**
- Multiple element testing and interaction analysis
- Complex campaign optimization
- Statistical modeling and significance testing
- Performance attribution and insights

**Content Testing:**
- Headline and copy performance testing
- Visual asset effectiveness analysis
- Content format and length optimization
- Engagement and conversion testing

**User Experience Testing:**
- Usability testing and user journey analysis
- Interface and interaction optimization
- Mobile and cross-device experience testing
- Accessibility and performance validation

## MCP Integration Patterns

**Puppeteer Testing:**
- Automated browser testing for landing pages
- Email template rendering across clients
- Social media content preview testing
- User flow and conversion funnel testing
- Performance and load testing automation

**MotherDuck Analytics:**
- Test result data analysis and statistical validation
- Performance metric calculation and comparison
- Historical test data analysis and insights
- Predictive modeling for test outcomes

**Google Analytics Integration:**
- Goal tracking and conversion measurement
- User behavior analysis during tests
- Traffic source performance during tests
- Real-time test monitoring and alerts

**HubSpot Integration:**
- Lead quality analysis during tests
- Customer journey testing and optimization
- Personalization testing and segmentation
- Sales conversion impact analysis

## Test Types and Applications

**Campaign Testing:**
- Message testing and optimization
- Channel performance comparison
- Audience segment effectiveness
- Creative asset performance analysis
- Timing and frequency optimization

**Content Testing:**
- Headline and subject line optimization
- Content format and length testing
- Call-to-action effectiveness
- Visual content performance
- Content distribution optimization

**Landing Page Testing:**
- Layout and design optimization
- Form optimization and conversion
- Loading speed and performance
- Mobile responsiveness and usability
- Trust signals and social proof

**Email Testing:**
- Subject line and preview text optimization
- Template design and layout testing
- Send time and frequency optimization
- Personalization effectiveness
- Call-to-action placement and design

**Social Media Testing:**
- Post format and content optimization
- Posting time and frequency testing
- Hashtag and keyword effectiveness
- Visual content performance
- Engagement and reach optimization

## Marketing Persona Activation

Auto-activates appropriate personas based on test type:
- A/B testing → Growth Marketer persona
- Content testing → Content Creator persona
- Brand testing → Brand Strategist persona
- User experience testing → Technical Writer persona
- Performance testing → SQL Auditor persona

@include shared/marketing-quality-patterns.yml#Marketing_Severity_Levels

## Statistical Standards

Testing requires:
- **Sample Size**: Minimum sample size calculations for statistical power
- **Significance Level**: 95% confidence level (p < 0.05) for test validity
- **Test Duration**: Minimum test duration for reliable results
- **Practical Significance**: Minimum detectable effect size definition
- **Data Quality**: Data validation and outlier detection

## Test Documentation

All tests include:
- **Test Plan**: Hypothesis, methodology, success criteria
- **Setup Documentation**: Configuration, targeting, technical setup
- **Results Analysis**: Statistical analysis, insights, recommendations
- **Implementation Plan**: Winner implementation and follow-up testing
- **Learning Documentation**: Key insights and future test ideas

@include shared/marketing-docs-patterns.yml#Research_Report_Template

## Quality Assurance Framework

**Pre-Test Validation:**
- Hypothesis validation and test design review
- Technical setup verification and quality checks
- Sample size and duration calculation validation
- Success criteria and measurement definition

**During-Test Monitoring:**
- Real-time performance monitoring and alerts
- Data quality validation and anomaly detection
- Statistical significance tracking
- External factor monitoring and documentation

**Post-Test Analysis:**
- Statistical significance validation and interpretation
- Practical significance assessment and business impact
- Confounding factor analysis and documentation
- Actionable insights and recommendation development

@include shared/marketing-quality-patterns.yml#Campaign_Quality_Gates