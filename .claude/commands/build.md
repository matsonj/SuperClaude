**Purpose**: Technical documentation and code project builder

---

@include shared/universal-constants.yml#Universal_Legend

## Command Execution
Execute: immediate. --plan→show plan first
Legend: Generated based on symbols used in command
Purpose: "[Action][Subject] in $ARGUMENTS"

Build technical documentation, code projects, or development environments based on requirements in $ARGUMENTS.

@include shared/flag-inheritance.yml#Universal_Always

Examples:
- `/build --docs --motherduck --context7` - Documentation site with data validation
- `/build --api --sequential --puppeteer` - API documentation with testing
- `/build --project --think-hard` - Complete project setup with analysis

Pre-build: Clean temp files & cache | Validate dependencies | Remove outdated documentation | Check code quality

Build modes:
**--docs:** Technical documentation | API references | User guides | Code documentation | Multi-format output
**--project:** Code project setup | Development environment | Build system | Testing framework | CI/CD pipeline  
**--api:** API documentation | OpenAPI specs | SDK generation | Testing suites | Integration guides

Templates:
- **API Documentation:** OpenAPI specs | SDK docs | Integration guides | Testing examples | Performance benchmarks
- **User Guides:** Step-by-step tutorials | Getting started | Troubleshooting | FAQ | Reference materials
- **Code Documentation:** Inline comments | Architecture docs | Development setup | Contributing guides | Deployment instructions
- **Technical Specifications:** System requirements | Architecture diagrams | Data models | Security protocols | Performance specifications

## Documentation Types

**API Documentation:**
- OpenAPI/Swagger specification generation
- SDK and client library documentation
- Authentication and authorization guides
- Rate limiting and error handling documentation
- Code examples and integration tutorials
- Performance benchmarks and optimization guides

**User Documentation:**
- Getting started guides and tutorials
- Step-by-step installation instructions
- Feature documentation with examples
- Troubleshooting guides and FAQ
- Best practices and usage patterns
- Migration guides and upgrade instructions

**Developer Documentation:**
- Architecture and design documentation
- Code contribution guidelines
- Development environment setup
- Testing strategies and frameworks
- Deployment and CI/CD processes
- Performance optimization guides

**Technical Specifications:**
- System architecture diagrams
- Database schema and data models
- Security protocols and compliance
- Performance requirements and benchmarks
- Integration patterns and workflows
- Technology stack documentation

## Code Project Workflows

**Frontend Projects:**
- Modern framework setup (React, Vue, Angular)
- Build system configuration (Webpack, Vite, Parcel)
- Testing framework integration (Jest, Cypress, Playwright)
- Code quality tools (ESLint, Prettier, TypeScript)
- Development server and hot reload setup

**Backend Projects:**
- API framework setup (Express, FastAPI, Spring Boot)
- Database integration and migration setup
- Authentication and authorization implementation
- Testing framework configuration (unit, integration, e2e)
- Logging, monitoring, and observability setup

**Full-Stack Projects:**
- Monorepo or microservices architecture
- Shared component libraries and utilities
- API documentation and SDK generation
- End-to-end testing strategies
- Deployment and infrastructure setup

**Library/Package Projects:**
- Package manager configuration (npm, pip, cargo)
- Build system for library distribution
- Documentation generation and hosting
- Testing across multiple environments
- Release automation and versioning

## MCP Integration Patterns

**Context7 Integration:**
- Documentation standards and style guide compliance
- Technical writing best practices implementation
- Content organization and information architecture
- Knowledge base integration and search optimization

**MotherDuck Integration:**
- Performance data analysis for documentation
- Code metrics and quality measurement
- Build performance optimization
- User analytics for documentation effectiveness

**Sequential Integration:**
- Complex project architecture planning
- Multi-step build process optimization
- Strategic technical decision making
- Dependency analysis and optimization

**Puppeteer Integration:**
- Documentation usability testing
- User interface testing for documentation sites
- Performance testing for built applications
- Accessibility compliance verification

## Technical Writer Persona Activation

Auto-activates technical writer persona with focus on:
- Documentation clarity and user experience
- Technical accuracy and completeness
- Code example validation and testing
- Accessibility and inclusive design

## Quality Assurance

All builds include:
- **Technical Accuracy**: Code examples tested and validated
- **Documentation Quality**: Clear, comprehensive, and user-focused
- **Code Quality**: Linting, formatting, and best practices compliance
- **Performance Optimization**: Build speed and runtime performance
- **Accessibility Compliance**: WCAG guidelines and inclusive design
- **Security Review**: Best practices and vulnerability scanning

## Build Outputs

**Documentation Sites:**
- Static site generation (Docusaurus, MkDocs, GitBook)
- Interactive API documentation (Swagger UI, Redoc)
- Code example validation and testing
- Search functionality and navigation
- Responsive design and mobile optimization

**Code Projects:**
- Development environment setup
- Build system configuration
- Testing framework integration
- Code quality and formatting tools
- Documentation generation and hosting

**API Documentation:**
- OpenAPI specification generation
- SDK and client library documentation
- Interactive API explorer and testing
- Authentication and integration guides
- Performance benchmarks and optimization

**Technical Specifications:**
- Architecture diagrams and documentation
- System requirements and dependencies
- Security and compliance documentation
- Performance specifications and benchmarks
- Integration patterns and best practices