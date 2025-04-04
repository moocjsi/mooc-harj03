```mermaid
sequenceDiagram
  participant User
  participant Browser
  participant Server

  User->>Browser: Open web page
  Browser->>Server: Request HTML/CSS/JS
  Server-->>Browser: Send response
  Browser-->>User: Render page
```
