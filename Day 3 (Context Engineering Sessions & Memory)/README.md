# Day 3 — Context Engineering: Sessions & Memory

## Overview
This unit explores context engineering: the practice of assembling and managing information inside an agent’s context window to enable stateful, personalized AI interactions. It defines two primary concepts:
- **Session:** the container for a single, immediate conversation’s history.
- **Memory:** the long-term persistence mechanism used across sessions.

You will learn how to make agents stateful by managing conversation history (session context and working memory) and how to give agents long-term memory that persists across sessions.

## Learning objectives
- Explain the difference between Sessions and Memory.
- Implement stateful agents by managing session history and working memory.
- Persist and retrieve long-term memory across sessions.
- Apply context engineering techniques in ADK and NotebookLM.

## Required materials
- Unit 3 — “Context Engineering: Sessions & Memory” whitepaper (read).
- Summary podcast episode for this unit (NotebookLM).
- Codelabs on Kaggle:
    - Build stateful agents and perform context engineering.
    - Explore memory integration with agents.
- Kaggle notebooks provided in the course.

## Assignment — Complete Unit 3
1. Listen to the Unit 3 podcast summary (NotebookLM).
2. Read the “Context Engineering: Sessions & Memory” whitepaper.
3. Complete the Kaggle codelabs:
     - Build stateful agents; manage conversation history and session context.
     - Implement and test long-term memory persistence across sessions.
4. Optional: Add the whitepapers to NotebookLM for interactive Q&A.

## Deliverables
- Completed Kaggle notebooks for both codelabs.
- Short notes (README section or notebook cell) summarizing:
    - How session context is captured and updated.
    - How memory is stored, retrieved, and used across sessions.
    - One example multi-turn interaction demonstrating coherent agent behavior.

## Recommended workflow
- Fork or copy the provided Kaggle notebooks.
- Run baseline cells to confirm environment and model access.
- Implement the session and memory handlers incrementally; test after each change.
- Validate persistence by restarting the session and confirming memory retrieval.

## Tips
- Keep session logs compact; include only relevant tokens to manage the context window.
- Use structured memory (key-value or embeddings) for reliable retrieval.
- Test edge cases (ambiguous references, topic shifts) to ensure coherence.

## Further reading
- Revisit the whitepaper for design patterns and best practices.
- Experiment with NotebookLM for interactive summarization and Q&A.
