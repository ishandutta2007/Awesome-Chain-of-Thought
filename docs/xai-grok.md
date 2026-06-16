# xAI Grok (Think Mode)

## Overview
Grok 3 features a dedicated "Think Mode" and "DeepSearch" capability. It is designed to handle complex coding and mathematical reasoning by breaking down tasks into sub-tasks.

## History
- **Grok 3 Announcement:** February 17, 2025.

## Architecture Diagram
```mermaid
graph TD
    Query[User Query] --> Planner[Task Planner]
    Planner --> SubTask1[Sub-Task 1]
    Planner --> SubTask2[Sub-Task 2]
    SubTask1 --> Evaluator[Result Evaluator]
    SubTask2 --> Evaluator
    Evaluator -- Valid? --> Final[Final Response]
    Evaluator -- No --> Planner
```

## Technical Resources
- **Blog Post:** [Grok 3](https://x.ai/blog/grok-3)
- **Official Announcement:** [Elon Musk on X](https://x.com/elonmusk/status/1891340445854134544)
