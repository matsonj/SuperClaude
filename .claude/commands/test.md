**Purpose**: Comprehensive testing framework for code, documentation, and systems

---

@include shared/universal-constants.yml#Universal_Legend

## Command Execution
Execute: immediate. --plan→show plan first
Legend: Generated based on symbols used in command
Purpose: "[Action][Subject] in $ARGUMENTS"

Create or run comprehensive tests for code, documentation, or systems specified in $ARGUMENTS using modern testing methodologies and validation.

@include shared/flag-inheritance.yml#Universal_Always

Examples:
- `/test --unit --coverage --motherduck` - Unit testing with coverage analysis
- `/test --integration --puppeteer` - Integration testing with browser automation
- `/test --documentation --accessibility --context7` - Documentation testing
- `/test --performance --load --sequential` - Performance and load testing
- `/test --security --vulnerability` - Security vulnerability testing

## Command-Specific Flags
--unit: "Unit testing workflow (isolation→coverage→validation)"
--integration: "Integration testing across system components"
--e2e: "End-to-end testing with real user scenarios"
--performance: "Performance testing and benchmarking"
--load: "Load testing and scalability validation"
--security: "Security testing and vulnerability assessment"
--accessibility: "Accessibility compliance testing"
--documentation: "Documentation accuracy and usability testing"
--api: "API functionality and contract testing"
--database: "Database testing and data validation"

## Testing Modes

**--unit:** Unit testing and code coverage
- Individual function and method testing
- Code coverage analysis and reporting
- Test-driven development (TDD) workflows
- Mocking and stubbing strategies
- Assertion libraries and frameworks

**--integration:** Integration testing workflows
- Component interaction testing
- API integration validation
- Database integration testing
- Service-to-service communication testing
- Third-party service integration testing

**--e2e:** End-to-end testing scenarios
- User journey testing and validation
- Cross-browser compatibility testing
- Mobile responsiveness testing
- User interface interaction testing
- Business workflow validation

**--performance:** Performance testing and optimization
- Load testing and stress testing
- Response time and throughput analysis
- Resource utilization monitoring
- Bottleneck identification and resolution
- Scalability testing and validation

**--security:** Security testing and vulnerability assessment
- Authentication and authorization testing
- Input validation and sanitization testing
- SQL injection and XSS vulnerability testing
- API security testing and validation
- Data protection and privacy testing

**--accessibility:** Accessibility compliance testing
- WCAG guidelines compliance validation
- Screen reader compatibility testing
- Keyboard navigation testing
- Color contrast and visual accessibility
- Alternative text and semantic markup validation

## MCP Integration Patterns

**Puppeteer Integration:**
- Browser automation and testing
- User interface testing and validation
- Performance testing in real browsers
- Accessibility compliance verification
- Visual regression testing

**MotherDuck Integration:**
- Test data management and validation
- Performance metrics analysis
- Test result aggregation and reporting
- Data-driven testing scenarios
- Query performance testing

**Sequential Integration:**
- Complex test scenario planning
- Multi-step testing workflows
- Strategic testing analysis
- Comprehensive test coverage planning

**Context7 Integration:**
- Documentation testing and validation
- Technical writing quality assessment
- Style guide compliance testing
- Knowledge base validation

## Technical Writer Persona Activation

Auto-activates technical writer persona for testing tasks with focus on:
- Documentation accuracy and completeness testing
- Technical content validation
- User experience testing
- Accessibility compliance verification

## Quality Standards

**Test Coverage Standards:**
- Minimum 80% code coverage for unit tests
- Comprehensive integration test coverage
- End-to-end test coverage for critical user journeys
- Performance benchmark validation
- Security vulnerability assessment

**Documentation Testing Standards:**
- Technical accuracy verification
- Code example validation and testing
- User guide usability testing
- Accessibility compliance validation
- Style guide adherence checking

**API Testing Standards:**
- Contract testing and validation
- Security testing and vulnerability assessment
- Performance benchmarking
- Error handling and edge case testing
- Documentation accuracy verification

## Testing Frameworks and Tools

**Unit Testing:**
- Jest (JavaScript/TypeScript)
- pytest (Python)
- JUnit (Java)
- RSpec (Ruby)
- PHPUnit (PHP)
- Go testing package

**Integration Testing:**
- Postman/Newman (API testing)
- Testcontainers (database testing)
- WireMock (service mocking)
- Cypress (browser testing)
- Selenium (web application testing)

**Performance Testing:**
- JMeter (load testing)
- k6 (performance testing)
- Artillery (load testing)
- Lighthouse (web performance)
- WebPageTest (performance analysis)

**Security Testing:**
- OWASP ZAP (security scanning)
- Burp Suite (security testing)
- Snyk (vulnerability scanning)
- SonarQube (code quality and security)
- Bandit (Python security linting)

## Test Reporting and Analysis

**Test Results:**
- Comprehensive test execution reports
- Code coverage analysis and trends
- Performance benchmarking results
- Security vulnerability assessments
- Accessibility compliance reports

**Quality Metrics:**
- Test pass/fail rates and trends
- Code coverage percentages
- Performance benchmarks and thresholds
- Security vulnerability counts
- Accessibility compliance scores

**Recommendations:**
- Test coverage improvement suggestions
- Performance optimization opportunities
- Security vulnerability remediation
- Accessibility compliance improvements
- Testing strategy enhancements