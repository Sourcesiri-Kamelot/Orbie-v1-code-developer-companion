# Stackfu Code Developer Companion - Project Structure

## Overview

This document outlines the organization of the Stackfu Code Developer Companion project, which combines three main components:

1. **Orbie UI** - The modern user interface and visual design
2. **Bedrock Claude Chat** - The core AI chat functionality using Amazon Bedrock
3. **Code Companion** - Additional code-specific features and capabilities

## Directory Structure

```
stackfu-code-developer-companion/
├── frontend/                  # Orbie UI + original frontend components
│   ├── src/                   # React source code
│   ├── public/                # Static assets
│   └── ...
├── backend/                   # Combined backend services
│   ├── app/                   # Main application code
│   │   ├── chatbot/           # Bedrock Claude Chat functionality
│   │   ├── code-companion/    # Code Companion features
│   │   └── ...
│   └── ...
├── cdk/                       # AWS CDK infrastructure code
├── docs/                      # Documentation
├── examples/                  # Example use cases and code
└── ...
```

## Component Integration

### Frontend Integration
- Orbie UI provides the visual design and user experience
- Original chatbot frontend components are integrated into the Orbie UI framework
- Code Companion UI elements are added to enhance code-specific interactions

### Backend Integration
- Bedrock Claude Chat provides the core AI conversation capabilities
- Code Companion adds specialized code analysis and assistance features
- Shared services handle authentication, storage, and other common functions

### Infrastructure
- AWS CDK is used to define and deploy all cloud resources
- Workflow configurations manage CI/CD processes

## Development Workflow

1. Local development using the combined codebase
2. Testing of individual components and integrated features
3. Deployment through CodeCatalyst workflows
4. Monitoring and management through the administrator dashboard
