
### 2. `CONFIGURATION.md`
This file details the environment variables required to run the service properly.

```markdown
# Configuration

The service is configured using environment variables.

## Required Variables

| Variable | Description | Default |
| :--- | :--- | :--- |
| `PORT` | The port the service listens on | `3000` |
| `DB_HOST` | The database hostname | `localhost` |
| `JWT_SECRET` | Secret key for token signing | `None` |

## Example `.env` File

```env
PORT=3000
DB_HOST=postgres.local
JWT_SECRET=super-secret-key-123
