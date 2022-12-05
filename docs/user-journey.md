# User journey

```mermaid
sequenceDiagram
    Start->>Profile: Select profile
    Profile->>Workflow: Select workflow (ex: landscape)
    Profile->>Settings: Customize user settings
    Workflow->>Step: Run workflow step by step
```