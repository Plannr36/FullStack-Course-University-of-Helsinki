# This will be the README.md for part 0

Creating a graph

```mermaid
sequenceDiagram
    participant browser
    participant server

    browse-->server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
    activate server
    server-->browser: notes
    deactivate server
```
