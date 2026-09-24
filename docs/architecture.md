# Architecture

## Boundaries

### Client
Responsible for UI, user interaction, client-side state, and API consumption.

### Server
Responsible for API routes, validation, business logic, and service/data access.

### Docs
Contains architecture and audit documentation.

### Test
Contains automated/manual test documentation.

## First Vertical Feature Slice

User action → Client UI → HTTP/API request → Server validation/business logic → Response → Client UI.
