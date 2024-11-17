# Members Only

This project demonstrates how to implement authentication in a Rails app, ensuring that only authorized users can perform specific actions.

## Features

- **User Authentication**: Only authenticated users can create posts.
- **Anonymous Posts**: Posts are anonymous to non-signed-in users. Signed-in members can view the author’s email.
- **Post Management**: Members can create posts, but there is no editing or deleting functionality.
- **Secure Access**: Non-authenticated users can only view posts, while authenticated users can see both the content and the author’s email.

## Setup

### Prerequisites

Ensure that you have the following installed on your system:

- Ruby (version 3.x)
- Rails (version 8.x or above)
- SQLite3 (for local development)

### Installation Steps

- Clone the repository
- Install dependencies:

```bash
  bundle install
```

- Set up the database:

```bash
  bin/rails db:create
  bin/rails db:migrate
```
