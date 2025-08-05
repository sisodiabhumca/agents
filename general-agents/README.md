# Universal AI Agents

A comprehensive collection of specialized AI agents designed to work with any AI platform. These agents are platform-agnostic and can be adapted for use with Claude, ChatGPT, Gemini, or any other AI system.

## 🚀 Quick Start

### For Any AI Platform

1. **Copy the agent files** to your project directory
2. **Adapt the configurations** for your specific AI platform
3. **Configure API keys** and dependencies as needed
4. **Start using agents** by referencing them in your AI prompts

### Agent Categories

- **Engineering Agents** - AI/ML, Backend, Frontend, Mobile, DevOps
- **Design Agents** - UI/UX, Brand, Visual Storytelling
- **Marketing Agents** - Content, Growth, Social Media
- **Product Agents** - Research, Feedback, Prioritization
- **Operations Agents** - Analytics, Finance, Legal, Support
- **Testing Agents** - API Testing, Performance, Quality Assurance

## 📁 Directory Structure

```
general-agents/
├── engineering/
│   ├── ai-engineer.md
│   ├── backend-architect.md
│   ├── devops-automator.md
│   ├── frontend-developer.md
│   ├── mobile-app-builder.md
│   ├── rapid-prototyper.md
│   └── test-writer-fixer.md
├── design/
│   ├── brand-guardian.md
│   ├── ui-designer.md
│   ├── ux-researcher.md
│   ├── visual-storyteller.md
│   └── whimsy-injector.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── content-creator.md
│   ├── growth-hacker.md
│   ├── instagram-curator.md
│   ├── reddit-community-builder.md
│   ├── tiktok-strategist.md
│   └── twitter-engager.md
├── product/
│   ├── feedback-synthesizer.md
│   ├── sprint-prioritizer.md
│   └── trend-researcher.md
├── project-management/
│   ├── experiment-tracker.md
│   ├── project-shipper.md
│   └── studio-producer.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── finance-tracker.md
│   ├── infrastructure-maintainer.md
│   ├── legal-compliance-checker.md
│   └── support-responder.md
├── testing/
│   ├── api-tester.md
│   ├── performance-benchmarker.md
│   ├── test-results-analyzer.md
│   ├── tool-evaluator.md
│   └── workflow-optimizer.md
└── bonus/
    ├── joker.md
    └── studio-coach.md
```

## 🔧 Configuration

Each agent is provided in markdown format with YAML frontmatter that can be easily converted to any platform's format. The configuration includes:

- **Agent metadata** (name, description, category)
- **System prompt** with detailed instructions
- **Tools and capabilities** the agent can access
- **Example usage** scenarios
- **Performance metrics** and success criteria

## 💡 Usage Examples

### Basic Usage
```markdown
---
name: ai-engineer
description: Expert AI engineer for ML implementation
system_prompt: You are an expert AI engineer...
tools: [code_generation, api_integration, model_training]
---
```

### Platform-Specific Adaptation

#### For Claude
```json
{
  "name": "ai-engineer",
  "system_prompt": "You are an expert AI engineer...",
  "tools": ["code_generation", "api_integration"]
}
```

#### For ChatGPT
```python
messages = [
    {"role": "system", "content": "You are an expert AI engineer..."},
    {"role": "user", "content": "Implement ML features"}
]
```

#### For Gemini
```python
prompt = f"""
You are an expert AI engineer specializing in practical machine learning implementation.

{system_prompt}

User request: {user_request}
"""
```

## 🎯 Agent Capabilities

### Engineering Agents
- **AI Engineer**: ML pipelines, LLM integration, recommendation systems
- **Backend Architect**: API design, database optimization, scalability
- **Frontend Developer**: React/Vue components, performance optimization
- **Mobile App Builder**: iOS/Android development, cross-platform solutions
- **DevOps Automator**: CI/CD pipelines, infrastructure as code
- **Rapid Prototyper**: Quick MVPs, proof of concepts
- **Test Writer Fixer**: Automated testing, bug detection

### Design Agents
- **UI Designer**: Interface design, component systems, visual hierarchy
- **UX Researcher**: User testing, journey mapping, usability analysis
- **Brand Guardian**: Visual consistency, brand guidelines
- **Visual Storyteller**: Content creation, visual narratives
- **Whimsy Injector**: Delightful interactions, micro-animations

### Marketing Agents
- **Content Creator**: Multi-platform content, SEO optimization
- **Growth Hacker**: Viral loops, user acquisition, retention
- **Social Media Specialists**: Platform-specific strategies
- **App Store Optimizer**: ASO, keyword optimization, conversion

### Product Agents
- **Feedback Synthesizer**: User feedback analysis, feature prioritization
- **Trend Researcher**: Market analysis, competitive intelligence
- **Sprint Prioritizer**: Agile planning, value maximization

### Operations Agents
- **Analytics Reporter**: Data analysis, KPI tracking, insights
- **Finance Tracker**: Budget management, cost optimization
- **Legal Compliance**: Regulatory compliance, risk assessment
- **Support Responder**: Customer service, issue resolution

### Testing Agents
- **API Tester**: Endpoint testing, performance validation
- **Performance Benchmarker**: Speed optimization, load testing
- **Quality Assurance**: Bug detection, user experience testing

## 🔄 Platform Integration

### Claude Integration
```python
import anthropic

client = anthropic.Anthropic(api_key="your_api_key")

response = client.messages.create(
    model="claude-3-sonnet-20240229",
    max_tokens=1000,
    messages=[{
        "role": "user",
        "content": "You are the AI Engineer agent. Implement a recommendation system."
    }]
)
```

### ChatGPT Integration
```python
import openai

client = openai.OpenAI(api_key="your_api_key")

response = client.chat.completions.create(
    model="gpt-4",
    messages=[
        {"role": "system", "content": "You are the AI Engineer agent..."},
        {"role": "user", "content": "Implement ML features"}
    ]
)
```

### Gemini Integration
```python
import google.generativeai as genai

genai.configure(api_key="your_api_key")
model = genai.GenerativeModel('gemini-pro')

response = model.generate_content(
    "You are the AI Engineer agent. " + system_prompt + "\n\n" + user_request
)
```

### Custom Platform Integration
```python
# Generic agent template
def create_agent_prompt(agent_name, system_prompt, user_request):
    return f"""
    You are the {agent_name} agent.
    
    {system_prompt}
    
    User request: {user_request}
    
    Please respond as the {agent_name} agent would.
    """
```

## 📊 Performance Tracking

Track agent effectiveness with these metrics:

- **Task Completion Rate**: Percentage of successful task completions
- **Response Time**: Average time to complete tasks
- **User Satisfaction**: Feedback scores for agent outputs
- **Error Rate**: Frequency of failed or incorrect responses
- **Cost Efficiency**: Cost per task completion

## 🛠️ Customization

### Modifying Agents
1. Edit the markdown files
2. Adjust system prompts for your specific needs
3. Add custom tools and capabilities
4. Update examples to match your use cases

### Creating New Agents
1. Copy an existing agent template
2. Modify the metadata and system prompt
3. Add relevant tools and capabilities
4. Test with real scenarios
5. Document usage patterns

### Platform-Specific Adaptations
1. **Claude**: Use JSON format with tools array
2. **ChatGPT**: Use function calling for structured outputs
3. **Gemini**: Use structured prompts with clear instructions
4. **Custom**: Adapt to your platform's specific format

## 🔒 Security & Privacy

- All agents respect data privacy and security best practices
- No sensitive data is stored or transmitted unnecessarily
- API keys and credentials should be managed securely
- Follow your organization's security policies

## 📚 Resources

### Platform Documentation
- [Claude API Documentation](https://docs.anthropic.com/)
- [ChatGPT API Documentation](https://platform.openai.com/docs)
- [Gemini API Documentation](https://ai.google.dev/docs)
- [Custom Platform Integration Guide](docs/custom-integration.md)

### Best Practices
- [Agent Design Patterns](docs/design-patterns.md)
- [System Prompt Optimization](docs/prompt-optimization.md)
- [Multi-Agent Workflows](docs/multi-agent-workflows.md)
- [Performance Optimization](docs/performance-optimization.md)

## 🤝 Support

For questions or issues with these agents:
- Check the platform-specific documentation
- Review agent-specific examples
- Test with simple scenarios first
- Contact platform support for technical issues

## 📄 License

These agents are provided as-is for use with any AI platform. Modify and adapt them for your specific needs.

## 🔄 Migration Guide

### From Claude Code to Other Platforms
1. Extract system prompt from YAML frontmatter
2. Convert tools array to platform-specific format
3. Adapt examples to platform capabilities
4. Test with platform-specific API

### From ChatGPT to Other Platforms
1. Extract system message content
2. Convert function definitions to platform format
3. Adapt response handling
4. Test with platform-specific features

### From Gemini to Other Platforms
1. Extract prompt content
2. Convert structured outputs to platform format
3. Adapt safety settings and constraints
4. Test with platform-specific capabilities 