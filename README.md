# 🧹 Data Cleaning Workflow

```mermaid
flowchart TD
    A[Raw Dataset] --> B[Import Dataset]
    B --> C[Inspect Dataset]
    C --> D[Check Missing Values]
    D --> E[Remove Duplicates]
    E --> F[Correct Data Types]
    F --> G[Save Cleaned Dataset ✅]
