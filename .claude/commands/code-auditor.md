# Code Snippet Accuracy Auditor

## /audit-code - Code Snippet Accuracy Auditor

Comprehensive code auditing system that validates accuracy, security, and best practices of code snippets in marketing content.

### Command-Specific Flags

**Audit Types:**
- `--syntax` - Syntax validation and error checking
- `--security` - Security vulnerability assessment
- `--performance` - Performance optimization review
- `--best-practices` - Industry best practices compliance
- `--compatibility` - Version and platform compatibility
- `--documentation` - Code documentation and comments

**Programming Languages:**
- `--javascript` - JavaScript and Node.js code
- `--python` - Python code validation
- `--java` - Java code review
- `--go` - Go language validation
- `--rust` - Rust code checking
- `--sql` - SQL query validation
- `--bash` - Shell script validation
- `--api` - API endpoint and schema validation

**Validation Levels:**
- `--basic` - Syntax and basic functionality
- `--comprehensive` - Full security and performance audit
- `--production-ready` - Production deployment standards

### Auditing Process

**Phase 1: Code Discovery**
1. **Content Scanning** - Scan marketing content for code blocks
2. **Language Detection** - Identify programming languages used
3. **Context Analysis** - Understand code purpose and audience
4. **Dependency Mapping** - Identify external dependencies

**Phase 2: Accuracy Validation**
1. **Syntax Checking** - Validate code syntax and structure
2. **Execution Testing** - Test code execution in safe environment
3. **Output Verification** - Verify expected outputs and behavior
4. **Error Handling** - Check error handling and edge cases

**Phase 3: Security Assessment**
1. **Vulnerability Scanning** - Check for security vulnerabilities
2. **Best Practices** - Validate against security best practices
3. **Credential Safety** - Ensure no hardcoded credentials
4. **Input Validation** - Check input sanitization

**Phase 4: Quality Enhancement**
1. **Performance Optimization** - Suggest performance improvements
2. **Code Clarity** - Improve readability and comments
3. **Documentation** - Add or improve code documentation
4. **Best Practices** - Apply language-specific best practices

### Examples

```bash
# Comprehensive code audit for blog post
/audit-code --comprehensive --javascript --python --security

# Basic syntax validation for tutorial
/audit-code --basic --syntax --api --documentation

# Production-ready audit for whitepaper
/audit-code --production-ready --security --performance --all-languages

# SQL query validation for technical guide
/audit-code --sql --motherduck --performance --best-practices
```

### Validation Framework

**JavaScript/Node.js Validation:**
- ESLint configuration compliance
- Security vulnerability scanning
- Performance optimization opportunities
- Modern JavaScript best practices
- Node.js security patterns

**Python Validation:**
- PEP 8 style guide compliance
- Security best practices (Bandit)
- Performance optimization suggestions
- Type hint validation
- Import statement optimization

**SQL Validation:**
- Query syntax validation
- Performance optimization analysis
- Security injection prevention
- Index optimization suggestions
- Database compatibility checking

**API Validation:**
- Endpoint accessibility testing
- Response format validation
- Authentication method verification
- Rate limiting compliance
- Error response handling

### Security Audit Checklist

**Common Security Issues:**
- [ ] No hardcoded credentials or API keys
- [ ] Input validation and sanitization
- [ ] SQL injection prevention
- [ ] Cross-site scripting (XSS) prevention
- [ ] Authentication and authorization
- [ ] Secure communication (HTTPS/TLS)
- [ ] Error message information disclosure
- [ ] Dependency vulnerability scanning

**Performance Audit Areas:**
- Algorithm efficiency and complexity
- Database query optimization
- Memory usage patterns
- Network request optimization
- Caching strategy implementation
- Resource cleanup and management

### Audit Report Format

**Code Audit Summary:**
```json
{
  "audit_id": "audit_20240115_001",
  "content_file": "api-integration-guide.md",
  "code_blocks_audited": 12,
  "languages_detected": ["javascript", "python", "sql"],
  "overall_score": 85,
  "issues_found": {
    "critical": 0,
    "high": 1,
    "medium": 3,
    "low": 5
  },
  "recommendations": [
    {
      "severity": "high",
      "type": "security",
      "location": "Code block 7, line 3",
      "issue": "Hardcoded API key detected",
      "recommendation": "Use environment variable for API key",
      "fixed_code": "const apiKey = process.env.API_KEY;"
    }
  ]
}
```

**Issue Categories:**

**Critical Issues:**
- Security vulnerabilities
- Syntax errors that prevent execution
- Major performance problems
- Incompatible code versions

**High Priority Issues:**
- Best practice violations
- Minor security concerns
- Performance optimization opportunities
- Documentation gaps

**Medium Priority Issues:**
- Code style inconsistencies
- Minor optimization opportunities
- Improved error handling
- Better variable naming

**Low Priority Issues:**
- Code formatting improvements
- Additional comments
- Alternative approaches
- Efficiency micro-optimizations

### Integration with Content Workflow

**Writing Phase:**
- Real-time code validation during content creation
- Syntax highlighting and error detection
- Best practice suggestions
- Security warning alerts

**Refinement Phase:**
- Comprehensive code audit execution
- Issue prioritization and fixing
- Performance optimization implementation
- Documentation enhancement

**Quality Assurance:**
- Final validation before publication
- Cross-platform compatibility testing
- Security vulnerability assessment
- Production readiness verification