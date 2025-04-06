```mermaid
sequenceDiagram
participant browser
participant server

    browser->>server: POST /new_note_spa
    activate server
    server-->>browser: Confirmation with new note data
    deactivate server

    Note right of browser: The browser updates the UI and renders the new note
```