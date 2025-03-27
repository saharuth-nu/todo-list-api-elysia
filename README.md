# Elysia with Bun runtime

## Getting Started
To get started with this template, simply paste this command into your terminal:
```bash
bun create elysia ./elysia-example
```

## Development
To start the development server run:
```bash
bun run dev
```

## env
```bash
SERVER_PORT="SERVER_PORT"
DB_USERNAME="DB_USERNAME"
DB_PASSWORD="DB_PASSWORD"
DB_HOST="DB_HOST"
DB_PORT="DB_PORT"
DB_DATABASE="DB_DATABASE"
```

Open http://localhost:3000/ with your browser to see the result.

## Detail

We’re continuing with the APIs for our backend project ideas, this time around for a To-Do application. Why is it different from the previous one?

While the previous project only focused on the main CRUD operations, here we’ll add some more interesting responsibilities, such as:

- An authentication logic, which means you’ll have to keep a new table of users and their credentials
- You’ll have to create both users and tasks.
- You’ll also have to be able to update tasks (their status) and even delete them.
- Get a list of tasks, filter them by status and get the details of each one.
