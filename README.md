flowchart TD
    A[Input Dependencies] --> B[Dependency Scanner]
    B --> C[Vulnerability Checker]
    B --> D[License Analyzer]
    C --> E[Risk Assessment]
    D --> E
    E --> F[Generate Report]
    F --> G[Graphs & Insights]
