## EXPERIENCE.md

### Tool Selection Justification

Initially, I chose **Cursor**, an AI-First IDE, due to prior familiarity and the desire to test its **AI Agent** capability to bootstrap a project from scratch. However, a premium model quota restriction prevented Agent usage in the free tier. Consequently, I swiftly transitioned to **Replit Agent (Ghostwriter AI)** to maintain the **Cloud-Based Vibe Coding** experience without local installation risks. Replit proved a robust alternative by providing both the necessary React/Tailwind environment and immediate Agent access.

### Development Process

The development process was structured around providing high-level, segmented prompts to the Replit Ghostwriter, rather than writing code manually.

1.  **First Prompt (Scaffolding):** A prompt requested the basic structure (React, Tailwind, 25/5 modes, buttons). This iteration successfully set up dependencies, the UI, and initial state definitions.
2.  **Second Prompt (Cyclical Logic & Refactoring):** The most critical feature—**automatic and cyclical mode switching** with **customized durations** (45/15 and 25/5 modes)—was requested in a single complex prompt.
    * **Most Effective Prompt:** * "Restructure the timer logic into two main modes: 'Intense Mode' (45 min work, 15 min break) and 'Standard Mode' (25 min work, 5 min break). When a mode finishes, it must automatically transition to the break and play an audio alert."*
3.  **Iterations:** Only **2 main iterations** were required to get the core functionality running: one for scaffolding and one for integrating the complex cyclical logic. Manual coding or debugging was minimally required.

### Challenges and Solutions

**The Biggest Challenge:** The initial failure to access the **Cursor Agent feature** due to quota limitations. This highlighted that desktop IDEs are subject to sudden license and quota restrictions. **The Solution** was immediately switching to Replit, proving the **portability** of the Vibe Coding approach across different cloud environments.

**Technical Difficulty:** An AI-agnostic issue was the **audio notification** not playing immediately due to browser security restrictions requiring user interaction. This was solved by instructing the AI via prompt: *"Use a function that waits for user interaction before attempting to play the sound."* This demonstrated the AI's ability to integrate technical solutions rapidly.

**Documentation Limitation:** Ghostwriter AI successfully produced all code, but it could not automatically generate the required **reporting and documentation files** (`ANALYSIS.md`, `EXPERIENCE.md`). This limitation confirmed that AI Agents' capabilities are currently focused on **code generation and manipulation**, leaving **project management and documentation** to the developer.

### Reflection

The most surprising aspect of Vibe Coding was Ghostwriter's capacity to implement the **complex cyclical state management** (Work $\rightarrow$ Auto Break $\rightarrow$ Reset) from a single, high-level command. This logic would typically require extensive manual state management.

Vibe Coding transformed my development workflow from **writer to director**. I focused on dictating the project's **intent** in natural language rather than writing every line of code. This efficiency, particularly in prototyping and feature integration, potentially shortened the development time by an estimated **60-70%** compared to traditional coding. I would definitely use this tool for future projects. This technology has the potential to make software development highly accessible, but code **verification, testing, and security** remain the developer's critical responsibility.
