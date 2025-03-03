# Rust Task Manager (Monorepo)

## Services

- `user-service/` - Handles authentication and user management.
- `task-service/` - Manages tasks and assignments.
- `notification-service/` - Sends notifications for task updates.
- `api-gateway/` - Routes requests to respective services.

## Running the Project

```sh
cargo run -p user-service
cargo run -p task-service
