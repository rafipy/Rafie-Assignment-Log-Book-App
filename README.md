# This is a local API created in Express for an assignment.
### Below is the routing design of the API.

Method | Endpoint | Request Body | Response Body |
|--------|----------|--------------|---------------|
| GET | /api/assignments | None | `[{ id, title, description }]` |
| POST | /api/assignments | `{ title, description }` | `{ id, title, description }` |
| GET | /api/assignments/{id} | None | `{ id, title, description }` |
| PUT | /api/assignments/{id} | `{ title, description, dueDate }` | `{ id, title, description }` |
| DELETE | /api/assignments/{id} | None | None 
