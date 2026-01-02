---
layout: page
title: Projects
permalink: /projects/
---

# Current Projects

## [Save](https://github.com/to-ny/save)

**Kubernetes-native S3-compatible object storage written in Rust.**

A distributed storage system designed to run on Kubernetes with full S3 API compatibility. Works with existing S3 tools and SDKs out of the box.

**Features:**
- Raft consensus for consistent metadata
- Quorum writes for durability
- AWS SigV4 authentication
- Helm charts for deployment
- Prometheus metrics & health endpoints

**Tech:** Rust, Kubernetes, Raft, S3 API, Helm

---

## [Devflow](https://github.com/to-ny/devflow)

**Desktop application for AI-assisted iterative code development.**

A Tauri-based app that integrates AI agents with a diff review workflow. Send prompts, watch the agent work in real-time, review changes with inline comments, and iterate until satisfied.

**Features:**
- Chat interface with streaming responses
- Integrated diff view with syntax highlighting
- Line-specific and global code comments
- Support for Anthropic and Gemini models
- Git integration with commit flow

**Tech:** Rust, Tauri, React, TypeScript, Vite

---

# Past Projects

- [crypto-trackers](https://github.com/to-ny/crypto-trackers) — Playground project for testing AI agent capabilities on a green-field codebase
