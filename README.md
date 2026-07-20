# Yiannis Dermitzakis

DevOps engineer. I've spent my career building enterprise
software and delivery pipelines, with testing as my craft. Now I put AI agents
to work on all of it.

## Building

- **[frank](https://github.com/derio-net/frank)**: a self-hosted Kubernetes
  cluster on heterogeneous hardware, immutable OS, fully declarative. My first
  large-scale AI-native project.
- **[blog.derio.net](https://blog.derio.net)**: the cluster's blog, written in
  the voice of Frank himself: his build, his operations, and the decisions
  that shaped him.
- **[super-fr](https://github.com/derio-net/super-fr)**: a Claude Code plugin
  suite for autonomous feature delivery: brainstorm to reviewed PR inside
  isolated workspaces (git worktree + devcontainer), with phase dispatch to
  background runners.
- **[vscode-launchpad](https://github.com/derio-net/vscode-launchpad)**: a
  Tauri dashboard to search and open any VS Code workspace, with a live
  monitor for Claude Code sessions and a kill switch for the zombies. Built
  spec-first with [openspec](https://github.com/Fission-AI/OpenSpec).
- **[blog-craft](https://github.com/derio-net/blog-craft)**: portable
  scaffolding and authoring skills for teaching blogs, built as Claude Code
  skills.

## Focus

Multi-agent software delivery under real engineering discipline: spec-first,
tight TDD, cheap-to-iterate architecture. What I'm after is the layer
underneath: agent swarms that are trustworthy (reliable, secure, autonomous at
scale) and composable (workspaces, skills, and secrets tunable per agent).
I haven't found a system that does both well, so I'm building my own.

## Stack

Kubernetes · Talos · ArgoCD · GitOps · Terraform · Python · TypeScript ·
platform engineering · TDD/BDD and test automation · multi-agent systems
