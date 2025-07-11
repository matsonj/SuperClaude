**Purpose**: Technical validation for code, data, and system quality

---

@include shared/universal-constants.yml#Universal_Legend

## Command Execution
Execute: immediate. --plan→show plan first
Legend: Generated based on symbols used in command
Purpose: "[Action][Subject] in $ARGUMENTS"

Validate code quality, data integrity, and system performance specified in $ARGUMENTS.

@include shared/flag-inheritance.yml#Universal_Always

Examples:
- `/validate --sql --performance --motherduck` - SQL validation and optimization
- `/validate --code --quality --sequential` - Code quality validation
- `/validate --documentation --accessibility --context7` - Documentation validation
- `/validate --api --security --puppeteer` - API security validation

Validation modes:

**--sql:** Extract and validate SQL queries from files | Performance optimization | Syntax checking | Data integrity validation

**--code:** Code quality assessment | Syntax validation | Best practices compliance | Security vulnerability scanning

**--documentation:** Documentation quality validation | Accessibility compliance | Technical accuracy | User experience assessment

**--api:** API functionality validation | Security testing | Performance benchmarking | Integration testing

**--data:** Data quality assessment | Accuracy verification | Completeness checking | Consistency validation

**--performance:** System performance validation | Load testing | Resource utilization analysis | Bottleneck identification

## MCP Integration Patterns

**MotherDuck Integration:**
- SQL query extraction and execution testing
- Performance analysis and optimization recommendations
- Data quality assessment and validation
- Query result verification and accuracy checking

**Sequential Integration:**
- Complex validation process analysis
- Multi-step quality assurance workflows
- Strategic validation planning
- Comprehensive system validation

**Context7 Integration:**
- Documentation standards compliance validation
- Technical writing quality assessment
- Style guide adherence checking
- Knowledge base validation

**Puppeteer Integration:**
- User interface validation and testing
- Documentation usability testing
- Performance testing in real browsers
- Accessibility compliance verification

## Technical Writer Persona Activation

Auto-activates technical writer persona for validation tasks with focus on:
- Documentation quality and accuracy
- Technical content validation
- User experience assessment
- Accessibility compliance verification

## Quality Standards

**Data Quality Validation:**
- Accuracy and completeness verification
- Consistency checks across data sources
- Format validation and standardization
- Error detection and correction procedures

**Documentation Quality:**
- Technical accuracy and completeness
- Clarity and accessibility standards
- Style guide compliance
- User experience optimization

**Code Quality Validation:**
- Syntax and structure verification
- Best practices compliance
- Security vulnerability assessment
- Performance optimization opportunities

**API Quality Validation:**
- Functionality and behavior verification
- Security testing and vulnerability assessment
- Performance benchmarking and optimization
- Integration testing and compatibility

## Output Standards

Validation reports include:
- **Validation Summary**: Pass/fail status with detailed findings
- **Error Documentation**: Specific errors with resolution guidance
- **Performance Metrics**: Execution times and optimization opportunities
- **Recommendations**: Prioritized improvements and best practices
- **Next Steps**: Specific implementation guidance for fixes

## Validation Types

**SQL Validation:**
- Query syntax and structure verification
- Performance optimization analysis
- Data integrity and consistency checks
- Security vulnerability assessment
- Best practices compliance verification

**Code Validation:**
- Syntax and compilation verification
- Code quality metrics assessment
- Security vulnerability scanning
- Performance bottleneck identification
- Design pattern compliance checking

**Documentation Validation:**
- Technical accuracy verification
- Accessibility compliance testing
- User experience assessment
- Content completeness analysis
- Style guide adherence checking

**API Validation:**
- Endpoint functionality testing
- Security vulnerability assessment
- Performance benchmarking
- Integration compatibility testing
- Documentation accuracy verification

**System Validation:**
- Performance and scalability testing
- Security compliance verification
- Integration testing and validation
- Data flow and processing validation
- Error handling and recovery testing