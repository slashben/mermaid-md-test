# Mermaid UML testing in GitHub


```mermaid
sequenceDiagram
    participant Ben
    participant VS_Code
    participant GitHub
    Ben->>VS_Code: Install extension "Markdown Preview Mermaid Support"
    Ben->>VS_Code: Write some MD with Mermaid
    Ben->>GitHub: Push 
    GitHub->>Ben: Here is your nice sequenceDiagram
    
```