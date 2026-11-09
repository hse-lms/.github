<div align="center">
<strong>A unified learning platform for programming courses</strong><br>
Assignments · Learning materials · Submissions · Code and report checks · Grades
</div>

---

HSE LMS brings independently developed academic projects together into a single learning management system. The integration focuses on shared authentication, consistent APIs, asynchronous processing, and reproducible releases across independently versioned services.

**Status:** architecture and integration planning. The repositories and GitHub organization are set up; the components have not yet been integrated into a working system. The capabilities below describe the target architecture.

### Components

| Repository | Responsibility |
| --- | --- |
| [core-service](https://github.com/hse-lms/core-service) | User accounts, roles, and authentication |
| [study-service](https://github.com/hse-lms/study-service) | Courses, assignments, submission versions, grades, and gradebook |
| [wiki-service](https://github.com/hse-lms/wiki-service) | Learning materials, publishing, and search |
| [report-validator](https://github.com/hse-lms/report-validator) | DOCX formatting checks and feedback |
| [code-checker](https://github.com/hse-lms/code-checker) | C# code checking integration and test results |
| [web-client](https://github.com/hse-lms/web-client) | Web interface for students, reviewers, and course managers |
| [mobile-client](https://github.com/hse-lms/mobile-client) | Flutter client for the shared LMS API |
| [infra](https://github.com/hse-lms/infra) | Local deployment, release composition, and end-to-end verification |

The component repositories are currently private.

### Engineering focus

- Define shared data ownership and API and event contracts across existing projects.
- Connect submissions, automated checks, reviewer feedback, and grades in one workflow.
- Manage independent component versions and validate compatible product releases.
- Build a reproducible local environment with Docker Compose and end-to-end tests.

**Component stack:** ASP.NET Core, PostgreSQL, FastAPI, React, TypeScript, Flutter, MongoDB, and Meilisearch. Kafka and the shared Docker Compose environment are planned as part of the integration.

The project builds on existing student work, with source attribution and applicable licenses preserved.

<sub>An academic integration project associated with programming coursework at HSE University. This is not an official university service. Student submissions and personal data are not published.</sub>
