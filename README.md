# Enconvo Help Assistant

## Description

A Bot helping you use EnConvo. This extension provides an AI-powered assistant to help users better understand and utilize EnConvo features.

## Features

- Interactive chat-based assistance
- Built-in recommended prompts for common questions
- Integrated knowledge base support
- Customizable preferences

## Installation

```bash
npm install
```

## Development

```bash
# Run in development mode
npm run dev

# Build the extension
npm run build

# Publish the extension
npm run publish
```

## Scripts

- `lint`: Run ESLint for code linting
- `lint:fix`: Fix linting issues automatically
- `format`: Format code using Prettier
- `format:check`: Check code formatting
- `build`: Build the extension using enconvo
- `dev`: Run in development mode
- `publish`: Publish the extension

## Configuration

### Preferences

1. **Recommended Prompts**
   - Type: JSON
   - Default prompts:
     - "What features does EnConvo have?"
     - "How to use EnConvo?"
     - "What is Providers?"

2. **Attached Knowledge Base**
   - Integrated knowledge base support
   - Default knowledge base included

3. **Force Use Knowledge Base**
   - Option to force using knowledge base when answering queries
   - Enabled by default

## Dependencies

- @enconvo/api: ^0.1.149

## Dev Dependencies

- @types/node: ^22.10.2
- @types/react: 19.0.1
- eslint: ^9.17.0
- prettier: ^3.4.2
- tsup: ^8.3.5
- typescript: ^5.7.2

## License

MIT

## Author

EnconvoAI
