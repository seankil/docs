# Finster API Documentation

This repository contains the documentation for the Finster Public API, which provides access to AI-powered queries and tasks against company data sources.

## Overview

The Finster API allows you to:
- Execute natural language queries against SEC filings, investor relations documents, industry research, and web search
- Submit research and generation tasks that are processed asynchronously
- Access structured responses with citations and source information

## Development

To preview the documentation locally:

1. Install the Mintlify CLI:
   ```bash
   npm i -g mint
   ```

2. Run the development server:
   ```bash
   mint dev
   ```

3. View your local preview at `http://localhost:3000`

The preview updates automatically as you edit files.

## Documentation Structure

- **API Reference**: Complete API documentation with OpenAPI specifications
  - Queries endpoint for real-time AI queries
  - Tasks endpoints for asynchronous research and generation

## Contributing

When making changes to the documentation:
1. Make your edits locally
2. Preview changes using `mint dev`
3. Commit and push your changes
4. Changes are automatically deployed

## Resources

- [API Introduction](/api-reference/introduction) - Get started with the Finster API
- [Quickstart Guide](/quickstart) - Quick start guide for using the API
