# Conotion AI CLI

> **The AI-powered documentation generator that transforms your code into professional docs in seconds.**

[![npm version](https://badge.fury.io/js/@conotion%2Fcli.svg)](https://badge.fury.io/js/@conotion%2Fcli)
[![Node.js Version](https://img.shields.io/node/v/@conotion/cli.svg)](https://nodejs.org/)
[![License](https://img.shields.io/badge/license-Commercial-blue.svg)](./LICENSE)

## What is Conotion AI?

Conotion AI is the **world's most advanced AI documentation platform** that automatically generates comprehensive technical documentation, API references, and security reports for your projects. Our CLI brings the power of AI model (Mistral) directly to your terminal.

### Perfect for:
- **Developers** who want instant, high-quality documentation
- **Teams** needing consistent documentation standards
- **Companies** requiring automated security auditing
- **Open source projects** seeking professional documentation


<div align="center">

![Conotion CLI Demo](https://cli.conotion.ai/image1.png)

</div>

## Key Features

### **Intelligent Documentation Generation**
- **Auto-detect project structure** and generate relevant docs
- **Multi-format output**: Markdown, JSON
- **Smart content**: API docs, README, user guides, technical specs
- **Customizable templates** for different project types

### **Advanced Security Auditing**
- **SonarQube integration** with AI-enhanced analysis
- **Vulnerability detection** across multiple languages
- **Automated fix suggestions** with detailed explanations
- **Compliance reporting** for enterprise standards

### **Developer-First Experience**
- **One-command setup**: `npm i -g @conotion/cli`
- **Interactive prompts** for guided documentation
- **Smart caching** for faster subsequent runs
- **Team collaboration** with shared configurations

### **Enterprise Features**
- **Multi-language support**: JavaScript, TypeScript, Python, Java, Go, Rust, and more
- **Custom branding** and styling options
- **API access** for programmatic usage

---

## Quick Start

### Installation

```bash
# Install globally
npm install -g @conotion/cli
```

Get your Conotion AI API key [here](https://conotion.ai)

### Basic Usage

```bash
# Start interactive mode
conotion

# Generate docs for current project
conotion docs

# Run security audit
conotion security

# Quick project initialization
conotion init
```

## Documentation Types

### **Quick Documentation**
Perfect for rapid prototyping and getting started quickly.

### **Comprehensive Documentation**
Full project documentation with detailed explanations.

### **Focused Documentation**
Target specific areas of your project.

### **Custom Documentation**
Use your own templates and configurations.

---

## Security Features

### Automated Security Scanning

```bash
# Full security audit
conotion security

# Continue security todoo
conotion security continue

```

### Security Report Generation

```bash
# Export detailed security report to Conotion Cloud
conotion security export
```

---

## Configuration

Create a `conotion.config.js` file in your project root with `conotion init` :

```json
{
  "projectName": "Mitchi",
  "outputDir": "./docs",
  "defaultType": "complete",
  "defaultAreas": [
    "architecture",
    "api",
    "setup",
    "security",
    "performance",
    "deployment"
  ]
}
```

---

## Why Choose Conotion AI?

### **Lightning Fast**
- Generate comprehensive documentation in seconds
- Smart caching reduces subsequent generation time by 80%
- Parallel processing for large codebases

### **AI-Powered Intelligence**
- Uses Conotion AI API
- Context-aware documentation generation
- Learns from your codebase patterns

---

## Contributing

We're building the future of AI-powered documentation. Join our community:

- [Report bugs](https://discord.gg/EUQPv3ET)
- [Request features](https://discord.gg/EUQPv3ET)
- [Improve docs](https://discord.gg/EUQPv3ET)

---

## Support

- **Documentation**: [cli.conotion.ai](https://cli.conotion.ai/docs)
- 💬 **Community**: [Discord](https://discord.gg/EUQPv3ET)
- 📧 **Email**: support@conotion.ai

---

## License

© 2024 Conotion AI. All rights reserved.
Use is subject to [Conotion's Commercial Terms of Service](./LICENSE).
