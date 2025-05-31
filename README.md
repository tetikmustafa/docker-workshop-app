# Getting Started App

A modern todo list application built with Node.js, React, and MySQL.

## Features

- Create, read, update, and delete todo items
- Mark items as complete/incomplete
- Persistent storage with MySQL
- Modern React-based UI
- Docker support for easy deployment

## Prerequisites

- Node.js (v18 or later)
- Docker and Docker Compose
- MySQL (if running without Docker)

## Getting Started

### Using Docker (Recommended)

1. Clone the repository:
   ```bash
   git clone https://github.com/tetikmustafa/docker-workshop-app.git
   cd getting-started-app
   ```

2. Start the application:
   ```bash
   docker compose up
   ```

3. Access the application at `http://localhost:3000`

### Manual Setup

1. Install dependencies:
   ```bash
   yarn install
   ```

2. Set up environment variables:
   ```bash
   cp .env.example .env
   # Edit .env with your database configuration
   ```

3. Start the application:
   ```bash
   yarn dev
   ```

## Development

- `yarn dev` - Start development server
- `yarn build` - Build for production
- `yarn test` - Run tests
- `yarn lint` - Run linter

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Code of Conduct

Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for details on our code of conduct.

## Acknowledgments

- React Bootstrap for UI components
- Docker for containerization
- MySQL for database