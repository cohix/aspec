# aspec
> Agentic Specification-Driven development

This project is a set of templates that can be used with a variety of agentic coding tools to create a predictable development workflow.

The goal is to allow the creation of agents, SaaS applications, CLIs, and more by "co-working" with agentic coding tools using easily-understandable structured specifications that guide an agent's actions.

There is no "aspec tool" because these templates are meant to be used directly with claude, gemini, codex, etc. You should not need to use a CLI tool in an agentic world. Similarly, you should be able to collaborate with an agent to create the specifications in the first place. aspec is meant to be a starting point to reduce the initial toil required to bootstrap a generative AI co-authored project.

Use this repo as a template to bootstrap a new project, and then use your agentic tool of choice to begin building code. All specs are contained within the `aspec` folder, and can be referenced individually or as a collective to help AI build predictable code.

## How to use it
Use this repository as a template when creating a new project, or copy the `aspec` folder into an existing project.

The first step is to review `foundation.md` and fill in your project's specific information and guidance.

Next, review the `architecture`, `uxui`, `agentic` and `devops` folders to customize for your project.

The general workflow will involve creating a `work item` from the `0000-item.md` template. Use work items as specs for specific features, bugs, or other development tasks you wish to collaborate with your agent on.

Eventually, you will want to review the `operations` folder to ensure the application can be deployed and run as desired.
