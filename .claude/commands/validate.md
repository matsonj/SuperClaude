**Purpose**: Data quality and SQL validation for marketing analytics

---

@include shared/universal-constants.yml#Universal_Legend

## Command Execution
Execute: immediate. --plan→show plan first
Legend: Generated based on symbols used in command
Purpose: "[Action][Subject] in $ARGUMENTS"

Validate SQL queries, data quality, and analytics setup specified in $ARGUMENTS.

@include shared/flag-inheritance.yml#Universal_Always

Examples:
- `/validate --sql --performance --persona-sql-auditor` - SQL validation and optimization
- `/validate --analytics --tracking --google-analytics` - Analytics setup validation
- `/validate --data --quality --motherduck` - Data quality validation

Validation modes:

**--sql:** Extract and validate SQL queries from files | Performance optimization | Syntax checking | Data integrity validation

**--data:** Data quality assessment | Accuracy verification | Completeness checking | Consistency validation

**--analytics:** Analytics tracking validation | Goal setup verification | Attribution model checking | Performance measurement validation

**--performance:** Query performance optimization | Execution time analysis | Resource usage assessment | Bottleneck identification

## MCP Integration Patterns

**MotherDuck Integration:**
- SQL query extraction and execution testing
- Performance analysis and optimization recommendations
- Data quality assessment and validation
- Query result verification and accuracy checking

**Google Analytics Integration:**
- Tracking setup validation and verification
- Goal configuration and measurement validation
- Attribution model accuracy assessment
- Performance metric validation and analysis

## Marketing Persona Activation

Auto-activates SQL Auditor persona for data validation tasks.

@include shared/marketing-quality-patterns.yml#Data_Quality_Validation

## Output Standards

Validation reports include:
- **Validation Summary**: Pass/fail status with detailed findings
- **Error Documentation**: Specific errors with resolution guidance
- **Performance Metrics**: Query execution times and optimization opportunities
- **Recommendations**: Prioritized improvements and best practices
- **Next Steps**: Specific implementation guidance for fixes

@include shared/marketing-docs-patterns.yml#Documentation_Quality