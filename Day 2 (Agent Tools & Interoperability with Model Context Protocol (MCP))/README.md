# Day 2 — Agent Tools & Interoperability with Model Context Protocol (MCP)

## Overview
This unit covers external tool integrations for agents and introduces the Model Context Protocol (MCP). You will learn how to extend agent capabilities with custom tools, implement long‑running operations, and evaluate MCP’s architecture, communication patterns, and enterprise readiness considerations.

## Learning Objectives
- Understand the role and design of external tools for agents.
- Describe MCP architecture and its communication layers.
- Identify risks and enterprise readiness gaps in MCP adoption.
- Implement custom Python functions as agent tools.
- Implement long‑running operations and pause/resume workflows requiring human approval.

## Required Reading & Listening
- Listen: Unit 2 summary podcast (NotebookLM)
- Read: “Agent Tools & Interoperability with Model Context Protocol (MCP)” whitepaper

## Codelabs (Kaggle)
Complete the following hands‑on exercises:
- Create custom tools by converting Python functions into agent actions.
- Add tools to expand agent capabilities and follow tooling best practices.
- Implement MCP interactions and long‑running operations, including pause/approval/resume flows.

## Assignments
- Finish Unit 2 codelabs on Kaggle.
- Add the Unit 2 whitepaper to NotebookLM for interactive exploration.
- Prepare a short reflection (bullet list) describing:
    - One new tool you implemented and its purpose.
    - How you used MCP in a workflow.
    - Any risks or gaps you observed and proposed mitigations.

## Deliverables
- Completed Kaggle codelabs (links or Kaggle notebook IDs).
- A short reflection file (REFLECTION.md) with the items above.
- Optional: NotebookLM session link if you used it to analyze the whitepaper.

## Estimated Time
- Reading & listening: 45–60 minutes
- Codelabs: 2–4 hours (depending on familiarity)
- Reflection & deliverables: 30–60 minutes

## Tips & Best Practices
- Design tools with clear, minimal interfaces and explicit failure modes.
- Validate inputs and handle timeouts for long‑running operations.
- Log tool actions and decisions for auditability.
- When using MCP, document message schemas and expected state transitions.
- Use human‑in‑the‑loop checkpoints for operations that require approval.

## Resources
- Kaggle codelabs (Unit 2)
- Unit 2 whitepaper (MCP)
- NotebookLM for interactive summaries and Q&A

--- 
Place this README.md in the Day 2 folder and update links or notebook IDs after completing the codelabs.