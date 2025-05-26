# Stackfu Code Developer Companion

A comprehensive AI development assistant that combines:
- **Orbie UI**: Modern, intuitive user interface
- **Bedrock Claude Chat**: Powerful AI chat capabilities using Amazon Bedrock
- **Code Companion**: Advanced code assistance features

![Stackfu Code Developer Companion](https://d107sfil7rheid.cloudfront.net/demo.gif)

## Features

- Interactive AI chat powered by Claude models on Amazon Bedrock
- Modern, intuitive UI with Orbie's design language
- Code completion, explanation, and refactoring
- Bot personalization with custom instructions
- RAG (Retrieval Augmented Generation) capabilities
- LLM-powered Agent functionality
- Administrator dashboard for usage analytics

## Architecture

This application is built on AWS managed services:
- Amazon Bedrock for AI model access (Claude 3 Sonnet, Claude 3 Haiku, and Cohere Embed Multilingual)
- Amazon DynamoDB for conversation storage
- Amazon API Gateway + AWS Lambda for backend services
- Amazon CloudFront + S3 for frontend delivery
- Amazon Cognito for user authentication
- Amazon Aurora PostgreSQL for vector storage
- Additional AWS services for complete functionality

## Project Structure

```
stackfu-code-developer-companion/
├── frontend/                  # Combined frontend with Orbie UI
├── backend/                   # Backend services with chatbot and code companion
├── orbie/                     # Original Orbie UI components
├── cdk/                       # AWS CDK infrastructure code
├── docs/                      # Documentation
└── examples/                  # Example use cases
```

## Getting Started

### Prerequisites
- AWS Account with access to Amazon Bedrock
- Model access enabled for Claude 3 Sonnet, Claude 3 Haiku, and Cohere Embed Multilingual
- AWS CLI configured with appropriate permissions

### Deployment
1. Clone this repository
2. Configure AWS credentials
3. Deploy using the provided CDK workflow

For detailed instructions, see the [deployment guide](./docs/DEPLOYMENT.md).

## License

This project is licensed under the MIT-0 License.
