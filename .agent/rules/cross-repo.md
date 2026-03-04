# Cross-Repository Rules

You must analyze both backend and frontend before:

- Changing API structure
- Renaming fields
- Removing endpoints
- Changing authentication logic

Cross-Impact Checklist:

If backend changes:
□ Check all frontend API calls
□ Update TypeScript types
□ Update form validations
□ Update error handling

If frontend changes data expectations:
□ Verify backend response shape
□ Confirm no contract mismatch

When refactoring:
1. Search entire workspace for symbol usage.
2. Update imports across folders.
3. Ensure no broken integration.
4. List impacted files in final response.
