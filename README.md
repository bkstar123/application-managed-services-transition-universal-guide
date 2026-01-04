# Application Managed Services - Transition Univeral Guide

A comprehensive framework and methodology for understanding, documenting, and taking over existing codebases using AI-powered analysis tools.

## 📋 Overview

This repository contains battle-tested strategies, prompts, and workflows for:

- **Reverse Engineering**: Systematically analyzing and understanding unfamiliar codebases
- **AMS Transitions**: Complete takeover of Application Managed Services from customers
- **Documentation Generation**: Creating comprehensive technical documentation using AI tools
- **Knowledge Transfer**: Capturing tribal knowledge and operational expertise

## 🎯 Use Cases

### 1. **New Project Onboarding**
Quickly understand a new codebase you're joining with systematic analysis covering architecture, domain models, business rules, and operational aspects.

### 2. **AMS Takeover**
Complete framework for transitioning ownership of production systems with zero downtime (see [AMS_transition/master_plan.md](AMS_transition/master_plan.md)).

### 3. **Legacy System Documentation**
Generate comprehensive documentation for undocumented legacy systems using AI-assisted analysis.

### 4. **Production Readiness Assessment**
Evaluate operational readiness, infrastructure, monitoring, and deployment procedures.

## 📂 Repository Structure

```
.
├── AMS_transition/
│   └── master_plan.md          # 12-week AMS takeover framework
├── chain_of_thoughts/
│   ├── cot-01                  # Comprehensive code analysis approach
│   └── cot-02                  # Operations-focused analysis (production ownership)
├── system_prompts/
│   └── strategy-01.md          # Ultimate reverse engineering system prompt
└── LICENSE                      # MIT License
```

## 🚀 Quick Start

### For Code Analysis

1. **Use the System Prompt**: Copy the content from [system_prompts/strategy-01.md](system_prompts/strategy-01.md) into GitHub Copilot or your AI assistant configuration.

2. **Choose Your Analysis Path**:
   - **New Developer**: Use prompts from [chain_of_thoughts/cot-01](chain_of_thoughts/cot-01) for domain-first understanding
   - **Operations/SRE**: Use [chain_of_thoughts/cot-02](chain_of_thoughts/cot-02) for production readiness focus

3. **Start Analyzing**:
   ```
   "Perform an EXHAUSTIVE codebase analysis covering ALL aspects"
   ```

### For AMS Transition

Follow the complete 12-week plan in [AMS_transition/master_plan.md](AMS_transition/master_plan.md):

- **Weeks 1-2**: Business alignment & access setup
- **Weeks 2-4**: Code analysis & knowledge transfer
- **Weeks 4-6**: Operational deep dive
- **Weeks 6-8**: Hands-on validation
- **Weeks 8-10**: Shadow operations
- **Weeks 10-12**: Full ownership transition

## 🎓 Key Features

### Comprehensive Analysis Modes

The system prompt ([strategy-01.md](system_prompts/strategy-01.md)) provides specialized analysis modes:

- **📊 Architecture Analysis**: System structure, layers, components
- **🎯 Domain Analysis**: Business logic, glossary, domain models
- **🗄️ Database Deep Dive**: Complete ERD, constraints, indexes
- **🖥️ UI/Screen Mapping**: All screens, navigation flows, user journeys
- **🔄 End-to-End Flows**: Complete traces from UI → API → DB → UI
- **🔒 Security Review**: Vulnerabilities, authentication, authorization
- **⚡ Performance Analysis**: Bottlenecks, optimization opportunities
- **🚀 Infrastructure & Deployment**: CI/CD, containers, IaC
- **📡 Operations & Monitoring**: Logging, alerting, troubleshooting
- **🔗 External Integrations**: Third-party APIs, webhooks, fallbacks

### Automated Documentation

Generates structured documentation with:

- ✅ Mermaid diagrams for all visualizations
- ✅ Complete wiki structure (17 specialized folders)
- ✅ Cross-referenced markdown files
- ✅ Progressive documentation building
- ✅ Business and technical perspectives

### Production-Ready Focus

Special emphasis on operational knowledge:

- Deployment procedures and rollback steps
- Monitoring, alerting, and troubleshooting
- Incident response and runbooks
- Data lineage and compliance
- Cost analysis and scaling strategies

## 📚 Documentation Philosophy

### Three-Tier Analysis

1. **Business Layer** (What & Why)
   - Domain glossary and ubiquitous language
   - Business rules and workflows
   - User journeys and screen purposes

2. **Technical Layer** (How)
   - Architecture and design patterns
   - Code organization and conventions
   - API specifications and data models

3. **Operational Layer** (Run & Maintain)
   - Deployment and monitoring
   - Troubleshooting and incident response
   - Infrastructure and scaling

## 🛠️ Tools & Technologies

This framework works with:

- **AI Assistants**: GitHub Copilot, ChatGPT, Claude
- **Documentation**: Markdown, Mermaid diagrams
- **Code Editors**: Visual Studio Code (primary), any IDE
- **Version Control**: Git, GitHub/GitLab/Bitbucket

## 📖 Example Usage

### Analyzing a New Module

```
User: "Analyze the OrderService module"

AI Response:
- Creates comprehensive analysis with diagrams
- Documents business rules and domain logic
- Maps end-to-end flows
- Identifies integration points
- Generates ready-to-save markdown files:
  - wiki/03-modules/order-service/overview.md
  - wiki/01-domain/workflows/order-fulfillment.md
  - wiki/08-api/endpoints/order-endpoints.md
```

### Understanding End-to-End Flow

```
User: "Trace the complete checkout flow"

AI Response:
- Full sequence diagram from user click to database
- Shows all screens involved
- Documents API calls and validations
- Maps business rules applied
- Shows error handling paths
- Saves to: wiki/01-domain/end-to-end-flows/checkout-flow.md
```

## 📊 Success Metrics

### For Code Analysis
- **Time Saved**: 40-50% faster than manual analysis
- **Coverage**: Comprehensive documentation of all system aspects
- **Quality**: Structured, searchable, maintainable documentation

### For AMS Transitions (from master_plan.md)
- **Timeline**: 8-12 weeks for complete takeover
- **Effort**: ~1,800 hours team effort
- **Cost**: $143K-$215K (based on blended rates)
- **Success Rate**: Zero service disruption when followed

## 🎯 Best Practices

1. **Start with Domain**: Understand business context before diving into code
2. **Progressive Documentation**: Build wiki incrementally, not all at once
3. **Validate with Humans**: AI analysis should be verified by team members
4. **Focus on Operations**: For production systems, prioritize operational knowledge
5. **Capture Tribal Knowledge**: Document what's NOT in the code (interviews, incidents)

## 🤝 Contributing

This is a living framework. Contributions welcome:

- Additional analysis prompts
- Refinements to system prompts
- AMS transition case studies
- Documentation templates
- Tool integrations

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🔗 Related Resources

- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [Mermaid Diagram Syntax](https://mermaid.js.org/)
- [Domain-Driven Design](https://martinfowler.com/bliki/DomainDrivenDesign.html)
- [C4 Model](https://c4model.com/)

## 💡 Key Insights

> **80% of system knowledge is tribal, not in code**
> 
> This framework captures both: code analysis (20%) + operational knowledge (80%)

> **Documentation is a byproduct, not the goal**
> 
> The goal is understanding. Documentation ensures that understanding persists.

> **Operations beats theory**
> 
> For AMS: shadow operations and hands-on practice matter more than reading code.

## 🚨 Important Notes

### What This Framework Does
✅ Provides systematic approach to code analysis  
✅ Generates comprehensive documentation structure  
✅ Guides AMS transition with proven methodology  
✅ Captures both technical and operational knowledge  

### What This Framework Doesn't Do
❌ Replace human expertise and judgment  
❌ Automatically fix bugs or refactor code  
❌ Guarantee project success without team effort  
❌ Eliminate need for customer collaboration (for AMS)  

## 📞 Support & Questions

For questions about:
- **System Prompts**: See detailed examples in [strategy-01.md](system_prompts/strategy-01.md)
- **AMS Transitions**: Refer to comprehensive guide in [master_plan.md](AMS_transition/master_plan.md)
- **Analysis Approaches**: Check [chain_of_thoughts/](chain_of_thoughts/) for different perspectives

---

**Version**: 1.0  
**Last Updated**: 4th January 2026  
**Maintained By**: Tuan Hoang

---

*Built for developers taking over unfamiliar codebases and operations teams transitioning to new systems.*
