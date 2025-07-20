
Gemini
Summarize this folder
Analyze each file
in this folder
What can Gemini do with folders
in Google Drive
Lyra Gem
Sales pitch ideator
Create compelling sales pitches that resonate with your audience and drive conversions.
Learning coach
Here to help you learn and practice new concepts. Tell me what you'd like to learn, and I'll help you get started.
Your Gems will appear across Workspace
Gemini for Workspace can make mistakes, including about people, so double-check it. Learn more
---
name: document
description: Update CLAUDE.md with AI context and README.md with comprehensive project documentation
---

# Project Documentation Generator

You are an expert technical writer and documentation specialist. Your task is to analyze the current project and update two critical documentation files: CLAUDE.md (for AI assistance context) and README.md (for users and developers).

## Documentation Process

### Phase 1: Project Analysis

1. **Scan the entire project** to understand:

   - Project structure and architecture
   - Main technologies and frameworks used
   - Key features and functionality
   - Dependencies and requirements
   - Current state of existing documentation

2. **Identify documentation gaps** by checking:
   - Missing setup instructions
   - Undocumented features
   - Outdated information
   - Incomplete API documentation
   - Missing architectural decisions

### Phase 2: CLAUDE.md Update

The CLAUDE.md file should contain AI-relevant context to help Claude (or other AI assistants) understand and work with this project effectively.

#### CLAUDE.md Structure:

```markdown
# Project Context for AI Assistance

## Project Overview

[Brief description of what this project does and its main purpose]

## Architecture

[High-level architecture description, main components, and how they interact]

## Key Technologies

- [Technology 1]: [Why it's used]
- [Technology 2]: [Why it's used]

## Project Structure
```

[Project directory tree with explanations]

```

## Important Files and Their Purposes
- `[filename]`: [Purpose and key functionality]
- `[filename]`: [Purpose and key functionality]

## Current Development Status
- Latest features: [What's recently added]
- Work in progress: [What's being developed]
- Known issues: [Current bugs or limitations]

## Development Patterns
- Coding standards: [Project conventions]
- Design patterns used: [Patterns and where]
- Testing approach: [How tests are structured]

## Common Tasks
### Adding a new feature
[Step-by-step process]

### Debugging issues
[Common debugging approaches]

### Running tests
[Test execution commands and strategies]

## Integration Points
- APIs: [External APIs used]
- Databases: [Database schema overview]
- Third-party services: [Services and their purposes]

## Performance Considerations
[Key performance aspects to consider when modifying code]

## Security Considerations
[Security patterns and things to watch for]

## Deployment
[How the project is deployed and environment considerations]
```

### Phase 3: README.md Update

The README.md should be user and developer-friendly, providing all necessary information to understand, install, use, and contribute to the project.

#### README.md Structure:

````markdown
# [Project Name]

[Project badges: build status, version, license, etc.]

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Configuration](#configuration)
- [Development](#development)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

[Compelling project description, what problem it solves, why it exists]

## ✨ Features

- **[Feature 1]**: [Description]
- **[Feature 2]**: [Description]
- **[Feature 3]**: [Description]

## 🚀 Demo

[Link to live demo or screenshots/GIFs showing the project in action]

## 📦 Installation

### Prerequisites

- [Requirement 1] (version X.X or higher)
- [Requirement 2]

### Quick Start

```bash
# Clone the repository
git clone [repository-url]

# Navigate to project directory
cd [project-name]

# Install dependencies
[installation command]

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run the application
[run command]
```
````

### Detailed Installation

[More detailed steps if needed]

## 💻 Usage

### Basic Usage

```[language]
// Example code showing basic usage
```

### Advanced Usage

```[language]
// More complex examples
```

### CLI Commands (if applicable)

| Command     | Description   | Example     |
| ----------- | ------------- | ----------- |
| `[command]` | [description] | `[example]` |

## 📚 API Documentation

### Endpoints (if applicable)

| Method | Endpoint          | Description   | Parameters |
| ------ | ----------------- | ------------- | ---------- |
| GET    | `/api/[endpoint]` | [description] | [params]   |

### Functions/Methods (if applicable)

#### `functionName(parameters)`

- **Description**: [What it does]
- **Parameters**:
  - `param1` (type): [description]
  - `param2` (type): [description]
- **Returns**: [return description]
- **Example**:

```[language]
[example code]
```

## ⚙ Configuration

### Environment Variables

| Variable     | Description   | Default   | Required |
| ------------ | ------------- | --------- | -------- |
| `[VAR_NAME]` | [description] | [default] | Yes/No   |

### Configuration Files

- `[config-file]`: [Purpose and key settings]

## 🛠 Development

### Setting Up Development Environment

```bash
# Additional development setup steps
[commands]
```

### Project Structure

```
[project-name]/
├── src/              # Source code
├── tests/            # Test files
├── docs/             # Documentation
└── ...
```

### Development Workflow

1. Create a new branch: `git checkout -b feature/your-feature`
2. Make changes and commit: `git commit -m "Add feature"`
3. Push to the branch: `git push origin feature/your-feature`
4. Create a Pull Request

### Code Style

[Code style guidelines and linting commands]

## 🧪 Testing

### Running Tests

```bash
# Run all tests
[test command]

# Run specific test suite
[specific test command]

# Run with coverage
[coverage command]
```

### Writing Tests

[Guidelines for writing tests]

## 🚢 Deployment

### Production Deployment

[Step-by-step deployment instructions]

### Environment-Specific Configuration

[Different configurations for dev/staging/prod]

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### How to Contribute

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is licensed under the [License Type] - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Credit 1]
- [Credit 2]

## 📞 Contact

- **Author**: [Name]
- **Email**: [email]
- **Project Link**: [repository-url]

```

## Update Process

### Step 1: Analyze Current Documentation
- Check if CLAUDE.md exists and review its current content
- Check if README.md exists and review its current content
- Note what information is missing or outdated

### Step 2: Gather Project Information
- Analyze project structure
- Identify main files and their purposes
- Extract technology stack
- Find existing tests and test patterns
- Identify APIs and endpoints
- Review configuration requirements

### Step 3: Update CLAUDE.md
- Create or update the file with AI-relevant context
- Ensure it includes all architectural decisions
- Document coding patterns and conventions
- Include debugging tips and common issues
- Add information about test structure

### Step 4: Update README.md
- Create or update with comprehensive user documentation
- Ensure installation steps are tested and work
- Include real code examples from the project
- Add badges if applicable
- Ensure all links are valid

### Step 5: Verify Documentation
- Check that all code examples actually work
- Ensure commands are accurate
- Verify file paths are correct
- Confirm environment variables match actual usage

## Output Format

After analyzing the project, provide:

1. **Documentation Status Report**
```

# Documentation Analysis

CLAUDE.md: [Exists/Missing] - [Current/Outdated/Incomplete]
README.md: [Exists/Missing] - [Current/Outdated/Incomplete]

Key Updates Needed:

- [Update 1]
- [Update 2]

```

2. **Updated CLAUDE.md content** (complete file)

3. **Updated README.md content** (complete file)

4. **Additional Documentation Recommendations**
- Other documentation files that should be created
- Suggestions for improving documentation maintenance

## Documentation Best Practices

1. **Be Specific**: Use actual file names, real commands, and working examples
2. **Stay Current**: Reflect the actual state of the project
3. **Be Complete**: Don't assume knowledge; explain everything needed
4. **Use Examples**: Show, don't just tell
5. **Test Everything**: Ensure all commands and code examples work
6. **Consider Audiences**: CLAUDE.md for AI, README.md for humans
7. **Maintain Structure**: Use consistent formatting and organization
```
