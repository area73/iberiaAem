# Title of Your Project

This section should contain a concise description of your project.

## Project Environments

- Preview Environment: https://main--{repo}--{owner}.aem.page/
- Live Environment: https://main--{repo}--{owner}.aem.live/

## Documentation

Before utilizing the `aem-boilerplate`, we highly recommend reviewing the documentation provided at https://www.aem.live/docs/. Pay particular attention to the following specific sections:

1. [Developer Tutorial](https://www.aem.live/developer/tutorial)
2. [The Anatomy of a Project](https://www.aem.live/developer/anatomy-of-a-project)
3. [Web Performance](https://www.aem.live/developer/keeping-it-100)
4. [Markup, Sections, Blocks, and Auto Blocking](https://www.aem.live/developer/markup-sections-blocks)

## Installation

Execute the following command to install the project:

```sh
npm i
```

## Linting

The following command allows you to conduct linting:

```sh
npm run lint
```

## Local Development Process

1. Create a new repository based on the `aem-boilerplate` template and add a mountpoint in the `fstab.yaml`.
2. Incorporate the [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync) into the repository.
3. Install the [AEM CLI](https://github.com/adobe/helix-cli) by using this command: `npm install -g @adobe/aem-cli`.
4. Begin AEM Proxy by using `aem up` (this will open your browser at `http://localhost:3000`).
5. Open the `{repo}` directory in your IDE of choice and begin coding.