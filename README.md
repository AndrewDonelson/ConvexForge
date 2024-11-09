<div>
  <div style="display: flex; align-items: center; justify-content: center; padding-bottom: 50px;">
    <!-- Update path to where your SVG will be stored -->
    <img src="assets/ConvexForge-Logo.svg" alt="ConvexForge Logo" width="100" />
    <div style="margin-left: 16px; text-align: left;">
      <h1>ConvexForge</h1>
      <p>An open-source toolkit for creating modular, reusable features in Convex applications. Build your full-stack features with database schemas, backend functions, and frontend components.</p>
    </div>
  </div>
</div>

# ConvexForge Project Overview

## Project Description
ConvexForge is an open-source toolkit for creating modular, reusable features in Convex applications. It provides a CLI tool and component library similar to shadcn/ui but focused on full-stack features including database schema, backend functions, and frontend components.

# ConvexForge Project Structure

## Overview
ConvexForge is a toolkit for creating modular, reusable features in Convex applications, providing a CLI tool and component library similar to shadcn/ui but focused on full-stack features.

```
convexforge/
├── packages/
│   ├── cli/                    # The CLI tool (convexforge)
│   │   ├── src/
│   │   │   ├── commands/       # CLI commands (init, add, remove)
│   │   │   ├── utils/          # Helper functions
│   │   │   ├── templates/      # Base templates for different features
│   │   │   └── config/         # Configuration handling
│   │   └── package.json
│   │
│   ├── core/                   # Core utilities and shared code
│   │   ├── src/
│   │   │   ├── types/         # Shared TypeScript types
│   │   │   ├── validators/    # Schema validators
│   │   │   └── helpers/       # Shared helper functions
│   │   └── package.json
│   │
│   └── create-convexforge/     # Project creation tool (optional)
│       └── package.json
│
├── features/                   # The actual features library
│   ├── auth/                  # Example feature
│   │   ├── convex/           # Convex backend code
│   │   │   ├── schema.ts
│   │   │   └── auth.ts
│   │   ├── components/       # React components
│   │   ├── hooks/           # React hooks
│   │   ├── styles/          # (Optional) CSS/styles
│   │   └── config.json      # Feature configuration
│   │
│   └── [other-features]/     # Other features follow same structure
│
├── docs/                      # Documentation
│   ├── features/             # Feature documentation
│   ├── guides/              # How-to guides
│   └── api/                 # API documentation
│
├── examples/                 # Example projects
│   ├── next-app/
│   └── vite-app/
│
├── scripts/                  # Build and maintenance scripts
│
├── website/                  # Documentation website
│   ├── app/
│   └── public/
│
├── tests/                    # Test suites
│   ├── e2e/
│   └── unit/
│
└── package.json             # Root package.json for workspace
```

## Feature System

### Feature Definition
A feature in ConvexForge consists of:
1. Database Schema
2. Convex Functions (queries/mutations)
3. React Components
4. React Hooks
5. Configuration
6. Documentation

### Feature Lifecycle
1. Installation via CLI
2. Configuration
3. Integration
4. Customization
5. Updates

### Feature Dependencies
- How features can depend on each other
- Dependency resolution
- Version management
- Conflict resolution

## CLI Tool Design

### Commands
1. init: Project initialization
   - Analyzes existing project
   - Sets up configuration
   - Installs dependencies

2. add: Feature installation
   - Downloads feature
   - Installs dependencies
   - Adds necessary code
   - Updates configuration

3. remove: Feature removal
   - Removes feature code
   - Cleans up dependencies
   - Updates configuration

### Configuration System
- Project-level configuration
- Feature-specific configuration
- Environment variables
- Type definitions

## Development Guidelines

### Creating Features
1. Feature Structure
2. Required Files
3. Testing Requirements
4. Documentation Requirements

### Contributing
1. Code Style Guide
2. Pull Request Process
3. Testing Requirements
4. Documentation Requirements

## Technical Implementation

### Core Systems
1. CLI Implementation
2. Feature Registry
3. Dependency Management
4. Code Generation
5. Configuration Management

### Integration Systems
1. Next.js Integration
2. Convex Integration
3. Database Schema Management
4. Component Integration

## Testing Strategy
1. Unit Tests
2. Integration Tests
3. E2E Tests
4. Test Utilities

## Documentation System
1. Feature Documentation
2. API Reference
3. Guides
4. Examples
5. Website

## Deployment and Distribution
1. Package Publishing
2. Version Management
3. Release Process
4. Update Management

## Community and Support
1. Issue Guidelines
2. Discussion Forums
3. Support Channels
4. Community Guidelines

## Future Roadmap
1. Planned Features
2. Enhancement Proposals
3. Community Feedback Integration
4. Version Planning