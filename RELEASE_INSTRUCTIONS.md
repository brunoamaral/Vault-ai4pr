# Release Instructions for v1.1

## Summary
This document provides instructions for creating the v1.1 release of the Vault-ai4pr repository.

## Release Details
- **Tag Name**: v1.1
- **Target Commit**: 56b7e4b (grafted) update definitions
- **Release Name**: v1.1 - Content Expansion Release
- **Release Type**: Minor release (content additions)

## Release Notes

### What's New in v1.1

This release significantly expands the knowledge base with 15 new AI/ML definitions and 9 new literature notes covering topics like:
- Large Language Models and GPT technology  
- Machine Learning approaches for Public Relations
- AI ethics and moral considerations
- Communication strategies and AI applications
- Clinical trial research methodologies

### New Definitions (15 added):
- API
- CoPilot
- Deepfake
- EU AI Act
- Fine Tuning
- Generative pre-trained transformer (GPT)
- Hallucination
- International Clinical Trials Registry Platform
- Large language model (LLM)
- Model Context Protocol
- Prompt Structure
- Retrieval Augmented Generation (RAG)
- Self Hosted
- Shadow IT
- prompt injection

### New Literature Notes (9 added):
- AIPublicRelations
- GPT41PromptingGuide
- baumannLargeLanguageModel2025
- bregmanMoralAmbitionStop2025
- lopesMachineLearningApproach2023
- nabaisUsingLargeLanguage2025
- waddingtonImpactAIPublic
- walkerrettbergChatGPTMultilingualMonocultural2022
- wolframWhatChatGPTDoing2023

### Other Changes:
- Updated README.md with additional resources (kickstart guide for students)
- Added meeting notes and organizational information
- Updated Obsidian configuration and settings
- Added new base files for people management
- Improved stakeholder mapping capabilities

## Commands to Execute

To create this release, the repository maintainer should:

1. Create and push the tag:
```bash
git tag -a v1.1 56b7e4b -m "v1.1 - Content Expansion Release"
git push origin v1.1
```

2. Create the GitHub release using the web interface or CLI with the release notes provided above.

## Files Changed Since v1
Total files changed: 36 files
- 15 new definition files
- 9 new literature note files  
- 12 configuration and other files

The vault now provides a more comprehensive resource for AI and Public Relations research and academic workflows.