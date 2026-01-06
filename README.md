# AlertMedia Code Challenge (Modernized)

## Overview
Build a small, production-minded experience using the provided mock data (`db.json`). Choose any
technology stack (frontend, backend, or full-stack). We care less about framework choice and more
about the decisions you make, how you explain them, and how you leverage code generation tools.

Timebox: ~3-5 hours. Keep it focused and well-documented.

## What to Build
Pick one of the tracks below. You may do more, but do not feel obligated.

### Track A: Frontend Experience
Create a UI that helps a team understand and manage tasks and people.

Required:
- A primary view that lists tasks and supports filtering, sorting, and search.
- A detail view for a task that shows assignments and notes.
- A small dashboard or summary area that shows derived insights (counts by priority, completion rate,
  or similar).

Optional:
- Inline editing or creation of tasks/notes.
- A user detail page with their assigned tasks.
- Basic accessibility considerations (keyboard flow, labels, empty states).

### Track B: Backend/API
Create an API or service that serves the data in a way a real client could use.

Required:
- Endpoints for tasks and people with filtering, sorting, and pagination.
- A task detail endpoint that includes assignments and notes in one response.
- Input validation and helpful error responses.

Optional:
- Basic caching for common queries.
- A simple write path (create or update tasks/notes).
- API docs (OpenAPI or simple README examples).

### Track C: Full-Stack (Optional)
Combine the key requirements from Track A and Track B in a single project.

## Data
The dataset includes the following collections:
- `people`
- `tasks`
- `task_assignments`
- `task_notes`

You can use the data as files, load into a local database, or serve via a mock API.

### Quick Start with JSON-Server (Optional)
1. Install json-server

```sh
npm install -g json-server
```

2. Start JSON-Server

```sh
json-server -p [PORT] --watch db.json
```

3. Access the API endpoint at `http://localhost:[PORT]`

See https://github.com/typicode/json-server for full JSON-Server documentation.

## LLM / Code Generation Usage
We expect many candidates to use LLMs or code generation tools. Please:
- Be transparent: include a short log of how you used them.
- Show your judgment: note what you accepted, changed, or discarded.
- Validate outputs: mention how you verified correctness.

You can add a short `LLM_NOTES.md` or include a section in your README.

## Deliverables
- Source code in this repo.
- Clear setup/run instructions.
- A short write-up covering:
  - Key decisions and tradeoffs.
  - Areas you would improve with more time.
  - Any known limitations.

## What We Evaluate
We do not score based on a strict checklist or tests. We look for signals of seniority, including:
- Clarity of problem framing and tradeoffs.
- API or UI design quality (depending on the track).
- Data modeling and edge-case handling (nulls, empty states, missing relations).
- Code quality and readability.
- Thoughtful use of tooling (including LLMs).

## Questions
If anything is ambiguous, make a reasonable choice and document it.
