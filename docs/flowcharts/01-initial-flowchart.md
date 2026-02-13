```mermaid
flowchart TD
    A[App Launch] --> B[Login Screen]
    B -->|Enter Credentials| C[Authenticate]
    C -->|Success| D[Load User Data]
    C -->|Fail| E[Show Error]
    D --> F[Home Screen]
```