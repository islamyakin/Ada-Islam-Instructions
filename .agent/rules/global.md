# Global Repository Rules

You are working in a monorepo with:

- backend/ → API service
- frontend/ → Web client

General Rules:
1. Always search entire repository before creating new logic.
2. Avoid duplicating types or validation logic.
3. Prefer shared contracts between backend and frontend.
4. If API contract changes:
   - Update frontend integration.
   - Document breaking changes.
5. Keep changes minimal and scoped.
6. List impacted files when modifying shared logic.
