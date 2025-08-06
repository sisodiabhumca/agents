# gAIsisodia AI Agents Collection

A comprehensive collection of **148 specialized AI agents** across **4 platforms** designed to accelerate and enhance every aspect of rapid development. Each agent is an expert in their domain, optimized for their specific platform.

## 🚀 Quick Overview

| Platform | Format | Agents | Status |
|----------|--------|--------|--------|
| **Claude Code** | Markdown + YAML | 37 | ✅ Ready |
| **Glean** | JSON | 37 | ✅ Ready |
| **ChatGPT** | JSON | 37 | ✅ Ready |
| **General** | Markdown + YAML | 37 | ✅ Ready |

**Total: 148 agents** across all platforms

## 📥 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/sisodiabhumca/agents.git
cd agents
```

### 2. Platform-Specific Setup

#### 🎯 Claude Code Agents
```bash
# Copy to Claude Code agents directory
cp -r claude-agents/* ~/.claude/agents/

# Restart Claude Code to load new agents
```

#### 🔍 Glean Agents
```bash
# Copy to your Glean workspace
cp -r glean-agents/* /path/to/your/glean/workspace/
```

#### 🤖 ChatGPT Agents
```bash
# Use with OpenAI API
# See chatgpt-agents/README.md for detailed integration
```

#### 🌐 General Agents
```bash
# Platform-agnostic - adapt to any AI platform
# See general-agents/README.md for migration guides
```

## 📁 Repository Structure

```
agents/
├── claude-agents/          # Claude Code agents (Markdown + YAML)
│   ├── engineering/        # 7 engineering agents
│   ├── design/            # 5 design agents
│   ├── marketing/         # 7 marketing agents
│   ├── product/           # 3 product agents
│   ├── project-management/ # 3 project management agents
│   ├── studio-operations/  # 5 operations agents
│   ├── testing/           # 5 testing agents
│   ├── bonus/             # 2 bonus agents
│   └── README.md          # Claude-specific documentation
├── glean-agents/          # Glean platform agents (JSON)
│   ├── [same structure]   # 37 JSON agents
│   └── README.md          # Glean-specific documentation
├── chatgpt-agents/        # ChatGPT platform agents (JSON)
│   ├── [same structure]   # 37 JSON agents
│   └── README.md          # ChatGPT-specific documentation
├── general-agents/        # Platform-agnostic agents (Markdown)
│   ├── [same structure]   # 37 universal agents
│   └── README.md          # General documentation
├── AGENTS_SUMMARY.md      # Complete collection overview
└── README.md              # This file
```

## 🎯 Agent Categories

### Engineering Department (7 agents)
- **ai-engineer** - AI/ML integration and implementation
- **backend-architect** - Scalable API and server design
- **devops-automator** - CI/CD and deployment automation
- **frontend-developer** - Responsive UI development
- **mobile-app-builder** - iOS/Android app development
- **rapid-prototyper** - MVP development and prototyping
- **test-writer-fixer** - Testing and bug fixing

### Design Department (5 agents)
- **brand-guardian** - Visual identity and brand consistency
- **ui-designer** - User interface design
- **ux-researcher** - User research and usability testing
- **visual-storyteller** - Visual content and storytelling
- **whimsy-injector** - Delightful user interactions

### Marketing Department (7 agents)
- **app-store-optimizer** - App store optimization
- **content-creator** - Multi-platform content creation
- **growth-hacker** - Viral growth strategies
- **instagram-curator** - Instagram content and engagement
- **reddit-community-builder** - Reddit community management
- **tiktok-strategist** - TikTok content strategy
- **twitter-engager** - Twitter engagement and trends

### Product Department (3 agents)
- **feedback-synthesizer** - User feedback analysis
- **sprint-prioritizer** - Feature prioritization
- **trend-researcher** - Market trend identification

### Project Management (3 agents)
- **experiment-tracker** - Data-driven experimentation
- **project-shipper** - Project delivery and launch
- **studio-producer** - Team coordination and execution

### Studio Operations (5 agents)
- **analytics-reporter** - Data analysis and insights
- **finance-tracker** - Budget and cost management
- **infrastructure-maintainer** - System reliability and scaling
- **legal-compliance-checker** - Regulatory compliance
- **support-responder** - Customer support management

### Testing Department (5 agents)
- **api-tester** - API testing and validation
- **performance-benchmarker** - Performance optimization
- **test-results-analyzer** - Test analysis and patterns
- **tool-evaluator** - Tool assessment and selection
- **workflow-optimizer** - Process optimization

### Bonus Agents (2 agents)
- **studio-coach** - Team guidance and mentorship
- **joker** - Humor and team morale

## 🚀 Quick Start Examples

### Claude Code Usage
```bash
# In Claude Code, simply describe your task:
"Create a new meditation app with user authentication"
# → Triggers rapid-prototyper, backend-architect, ui-designer

"Optimize our app store listing for better downloads"
# → Triggers app-store-optimizer

"Users are complaining about slow performance"
# → Triggers infrastructure-maintainer, performance-benchmarker
```

### Glean Integration
```json
{
  "agent": "ai-engineer",
  "task": "Implement a recommendation system",
  "context": "We have user behavior data and product catalog"
}
```

### ChatGPT API Usage
```python
import openai

client = openai.OpenAI(api_key="your_api_key")
response = client.chat.completions.create(
    model="gpt-4",
    messages=[
        {"role": "system", "content": "You are the AI Engineer agent..."},
        {"role": "user", "content": "Build a recommendation system for our app"}
    ]
)
```

## 📚 Platform-Specific Documentation

Each platform has detailed documentation:

- **[Claude Agents](claude-agents/README.md)** - Claude Code integration guide
- **[Glean Agents](glean-agents/README.md)** - Glean platform setup and usage
- **[ChatGPT Agents](chatgpt-agents/README.md)** - OpenAI API integration
- **[General Agents](general-agents/README.md)** - Platform-agnostic usage

## 🎯 Key Features

### Multi-Platform Support
- **Claude Code**: Native integration with YAML frontmatter
- **Glean**: JSON format with comprehensive metadata
- **ChatGPT**: OpenAI API compatible with function calling
- **General**: Universal format for any AI platform

### Specialized Expertise
- **37 unique agents** across 8 departments
- **Domain-specific tools** and capabilities
- **Real-world examples** and use cases
- **Performance metrics** and success criteria

### Rapid Development Focus
- **6-day sprint** optimization
- **Multi-agent workflows** for complex tasks
- **Proactive triggering** based on context
- **Quality assurance** and testing integration

## 🔧 Customization

### Agent Modification
Each agent can be customized for your specific needs:

1. **Edit YAML frontmatter** (Claude/General agents)
2. **Modify JSON configuration** (Glean/ChatGPT agents)
3. **Update system prompts** for your domain
4. **Add custom tools** and capabilities
5. **Adjust examples** for your use cases

### Adding New Agents
Follow the templates in each platform's README:
- Use consistent naming conventions
- Include comprehensive examples
- Define clear success criteria
- Test with real scenarios

## 📊 Performance Tracking

Track agent effectiveness through:
- **Task completion time**
- **User satisfaction scores**
- **Error rates and fixes**
- **Feature adoption metrics**
- **Development velocity**

## 🤝 Contributing

We welcome contributions to improve the agent collection:

1. **Test agents** with real projects
2. **Report issues** or suggest improvements
3. **Add new agents** following the templates
4. **Share successful patterns** with the community

### Contribution Guidelines
- Follow existing naming conventions
- Include comprehensive examples
- Test thoroughly before submitting
- Update documentation accordingly

## 📄 License

This project is open source. See individual platform READMEs for specific licensing information.

## 🆘 Support

- **Issues**: Report bugs or request features via GitHub Issues
- **Documentation**: Check platform-specific READMEs
- **Community**: Share experiences and best practices

## 🔄 Recent Updates

- ✅ **YAML parsing fixed** - All Claude agents now parse correctly
- ✅ **Multi-platform support** - 148 agents across 4 platforms
- ✅ **Author updates** - All references updated to gAIsisodia
- ✅ **Clean structure** - Organized directory layout
- ✅ **Comprehensive docs** - Platform-specific guides

---

**Repository**: [https://github.com/sisodiabhumca/agents](https://github.com/sisodiabhumca/agents)  
**Author**: gAIsisodia  
**Last Updated**: December 2024  
**Version**: 2.0.0
