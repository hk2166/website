---
title: Generate code
description: In this tutorial, you'll learn how to generate code from your AsyncAPI document.
weight: 100
---

# Generate Code from AsyncAPI Documents

This tutorial explains how to generate code from your AsyncAPI documents using the official AsyncAPI Generator.

## Prerequisites

- Node.js v20.12.0 or later
- npm v10.5.0 or later
- An AsyncAPI document

## Installing the Generator

Install the AsyncAPI Generator globally using npm:

```bash
npm install -g @asyncapi/generator
```

## Basic Usage

The basic syntax for generating code is:

```bash
ag <asyncapi-file> <template> [options]
```

For example, to generate HTML documentation:

```bash
ag asyncapi.yaml @asyncapi/html-template
```

## Available Templates

The AsyncAPI Generator supports many official templates:

- `@asyncapi/html-template` - Generate HTML documentation
- `@asyncapi/nodejs-template` - Generate Node.js applications
- `@asyncapi/java-template` - Generate Java applications
- `@asyncapi/python-template` - Generate Python applications
- `@asyncapi/go-template` - Generate Go applications

View all available templates in the [template repository](https://github.com/asyncapi/generator#templates).

## Template Options

Most templates support configuration options. To see available options:

```bash
ag help <template>
```

For example:

```bash
ag help @asyncapi/nodejs-template
```

## Custom Templates

You can create your own templates for specific use cases. See the [Template Development Guide](https://www.asyncapi.com/docs/tools/generator/template-development) for details.

## Next Steps

- Explore the [AsyncAPI Generator documentation](https://www.asyncapi.com/docs/tools/generator)
- Learn about [creating custom templates](https://www.asyncapi.com/docs/tools/generator/template-development)
- Join our [community](https://www.asyncapi.com/community) for help
