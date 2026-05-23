# Part 0 - Exercise 0.6

## New note in Single page app diagram

```mermaid
sequenceDiagram
    actor browser
    actor server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: 201 created
    deactivate server
