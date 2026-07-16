# REST API Design

Base URL

/api/v1

## Modules

Authentication

- POST /auth/login
- POST /auth/refresh
- POST /auth/logout

Users

- POST /users
- GET /users
- PUT /users/{id}

Offers

- POST /offers
- GET /offers
- PUT /offers/{id}
- POST /offers/{id}/submit
- POST /offers/{id}/approve
- POST /offers/{id}/publish

Notifications

- GET /notifications

Audit

- GET /audit