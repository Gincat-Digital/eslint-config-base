# Gincat Digital ESLint Plugin (base)

## Overview

The Gincat Digital ESLint Plugin is a custom ESLint plugin created specifically for projects developed at Gincat Digital. It provides a set of predefined configurations for enforcing coding standards and best practices in JavaScript and TypeScript codebases.

## Features

- **Consistent Coding Standards**: Enforce consistent coding standards across all Gincat Digital projects.
- **Best Practices**: Encourage the use of best practices and patterns in JavaScript and TypeScript development.
- **Customizable Configurations**: Easily customize configurations based on project requirements.
- **Integration with Build Pipelines**: Seamlessly integrate with build pipelines for automated code quality checks.

## Installation

You can install the Gincat Digital ESLint Plugin via npm:

```bash
npm install --save-dev @gincat-digital/eslint-config-base
```

## Usage

To use the plugin, simply extend the provided configurations in your ESLint configuration file:

```json
{
  "extends": [
    "@gincat-digital/eslint-config-base",
  ]
}
```

## License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.
