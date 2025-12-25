---
id: 10
title: List Gemini Plugins
stage: general
date_iso: 2025-12-14
surface: agent
model: gemini-1.5-pro
feature: none
branch: main
user: 
command: gemini plugins list
labels: ["gemini-cli", "plugins"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files_yaml:
  - history/prompts/general/010-list-gemini-plugins.general.prompt.md
tests_yaml: []
prompt_text: |
  gemini plugins list
response_text: |
  The available Gemini commands (plugins) are:
  - `sp.adr`
  - `sp.analyze`
  - `sp.checklist`
  - `sp.clarify`
  - `sp.constitution`
  - `sp.git.commit_pr`
  - `sp.implement`
  - `sp.phr`
  - `sp.plan`
  - `sp.specify`
  - `sp.tasks`
outcome: |
  The agent successfully listed the Gemini CLI commands.
evaluation: |
  The agent correctly interpreted 'plugins' as the custom commands in the .gemini/commands directory and provided a clear list.
---