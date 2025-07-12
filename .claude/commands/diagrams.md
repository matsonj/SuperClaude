# SVG Diagram Generation and Placement

## /diagram - SVG Diagram Generation

Advanced SVG diagram generation system with intelligent placement suggestions for marketing content.

### Command-Specific Flags

**Diagram Types:**
- `--architecture` - System architecture diagrams
- `--flow` - Process flow and workflow diagrams
- `--comparison` - Feature comparison charts
- `--timeline` - Project timeline and roadmap diagrams
- `--infographic` - Data visualization and infographics
- `--network` - Network topology and integration diagrams
- `--hierarchy` - Organizational and data hierarchy charts

**Visual Style:**
- `--minimal` - Clean, minimal design aesthetic
- `--technical` - Technical documentation style
- `--marketing` - Marketing-focused visual design
- `--branded` - Brand-consistent colors and styling
- `--interactive` - Interactive diagram elements

**Complexity Levels:**
- `--simple` - Basic concepts and overview diagrams
- `--detailed` - Comprehensive system diagrams
- `--comprehensive` - Full technical architecture diagrams

### Diagram Generation Process

**Phase 1: Content Analysis**
1. **Text Mining** - Extract diagrammable concepts from content
2. **Relationship Mapping** - Identify connections and dependencies
3. **Visual Opportunities** - Find complex explanations that benefit from visuals
4. **Placement Strategy** - Determine optimal diagram placement

**Phase 2: Diagram Creation**
1. **Concept Mapping** - Create visual concept map
2. **Layout Design** - Design optimal layout and flow
3. **SVG Generation** - Generate clean, scalable SVG code
4. **Accessibility** - Add alt text and accessibility features

**Phase 3: Integration**
1. **Placement Recommendations** - Suggest optimal content placement
2. **Content Flow** - Ensure diagrams enhance content flow
3. **Responsive Design** - Mobile and desktop optimization
4. **SEO Optimization** - Structured data and image SEO

### Examples

```bash
# Generate architecture diagram for technical blog post
/diagram --architecture --technical --detailed --placement

# Create process flow for tutorial content
/diagram --flow --minimal --step-by-step --interactive

# Marketing comparison chart
/diagram --comparison --marketing --branded --features

# Timeline for product roadmap announcement
/diagram --timeline --roadmap --milestones --marketing
```

### Diagram Categories

**Technical Architecture:**
- System component diagrams
- API integration flows
- Data flow diagrams
- Security architecture
- Deployment topologies

**Process Flows:**
- User journey maps
- Implementation workflows
- Decision trees
- Troubleshooting flows
- Onboarding processes

**Comparison Charts:**
- Feature comparison matrices
- Pricing tier comparisons
- Performance benchmarks
- Technology stack comparisons
- Competitive analysis

**Data Visualizations:**
- Performance metrics
- Usage statistics
- Growth trends
- Survey results
- Market analysis

### Placement Intelligence

**Automatic Placement Suggestions:**
1. **Introduction Diagrams** - High-level overviews after introductions
2. **Concept Illustrations** - Complex concepts need visual explanation
3. **Process Breakdowns** - Multi-step processes benefit from flow diagrams
4. **Comparison Points** - Feature comparisons enhanced with visual charts
5. **Summary Visuals** - Key takeaways reinforced with infographics

**Content Enhancement Rules:**
- **Complex Explanations** → Architecture diagrams
- **Multi-step Processes** → Flow charts
- **Feature Comparisons** → Comparison matrices
- **Performance Data** → Data visualizations
- **Timeline Content** → Roadmap diagrams

### SVG Code Generation

**Technical Standards:**
- Clean, semantic SVG markup
- Responsive viewBox settings
- Accessibility-compliant alt text
- Brand-consistent color schemes
- Optimized file sizes

**Example SVG Structure:**
```svg
<svg viewBox="0 0 800 600" xmlns="http://www.w3.org/2000/svg" 
     role="img" aria-labelledby="diagram-title">
  <title id="diagram-title">API Integration Architecture</title>
  <desc>System architecture showing client applications connecting to API gateway</desc>
  <!-- Diagram content with semantic grouping -->
  <g class="clients">
    <!-- Client applications -->
  </g>
  <g class="api-layer">
    <!-- API gateway and services -->
  </g>
  <g class="data-layer">
    <!-- Database and storage -->
  </g>
</svg>
```

### Integration with Content Workflow

**Content Analysis Phase:**
- Scan content for diagrammable concepts
- Identify technical complexity that needs visualization
- Map relationships between concepts
- Suggest diagram types and placement

**Writing Phase:**
- Generate diagrams based on content outline
- Provide placement recommendations
- Create responsive diagram code
- Include accessibility features

**Refinement Phase:**
- Update diagrams based on content changes
- Optimize visual clarity and impact
- Ensure brand consistency
- Validate accessibility compliance