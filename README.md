# Scriibe 📖

A web app for cataloging your personal book library: what you own, what you've read, and what you want to read next.

> **Status:** early development (Sprint 1). This README describes the direction of the project, not a finished product.

## Goals 🗒️

- Keep a simple, organized record of a personal library
- Make books quick to find
- Build it the way a production app is built: layered architecture, automated tests, CI, and measurable quality

## Tech Stack 🖥️

| Area | Technology |
| --- | --- |
| Language | Java |
| Framework | Spring Boot (Web, Validation, Security) |
| Views | Thymeleaf, HTML, CSS |
| Build | Maven |
| Testing | JUnit 5, Mockito, Spring MockMvc |
| CI | GitHub Actions |
| Planned | PostgreSQL, Docker |

## Getting Started 🚀

**Prerequisites:** JDK 25, Maven, Git

1. Clone the repository: `git clone <repository-url>`
2. Run the tests: `mvn test`
3. Start the app: `mvn spring-boot:run`
4. Open `http://localhost:8080` in your browser

> These steps will be confirmed once the project skeleton is committed.

## Project Structure 🏗️

```
controller   HTTP layer: receives requests, returns views
service      Business logic
repository   Data access behind interfaces
model        Domain objects
dto          Objects that cross layer boundaries
search       Sorting and search algorithms
config       Application and security configuration
```

## Development Workflow 👷

- Work is tracked as GitHub Issues on a project board, grouped into short sprints
- One issue per branch, merged through a pull request
- Commit messages follow [Conventional Commits](https://www.conventionalcommits.org/)
- CI runs the test suite on every push and pull request

## Quality Metrics 🧮

Updated at the end of each sprint.

| Metric | Current |
| --- | --- |
| Automated tests | n/a |
| Line coverage | n/a |
| Build time (CI) | n/a |

## Roadmap 🗺️

See the project board and open issues for current and upcoming work.

## License 💼

To be decided.
