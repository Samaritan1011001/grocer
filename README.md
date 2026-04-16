# Grocer

A Grocery List Management API documentation site.

## API Endpoints

The following endpoints are available for managing grocery lists:

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/grocery-lists` | Retrieve user's grocery lists |
| POST | `/api/grocery-lists` | Create a new grocery list |
| PUT | `/api/grocery-lists/{id}` | Update an existing list |
| DELETE | `/api/grocery-lists/{id}` | Remove a grocery list |

## Authentication

All authenticated requests require a Bearer token. Include the `Authorization` header with your JWT token:

```
Authorization: Bearer <your-jwt-token>
```

## Rate Limits

API calls are limited to 1000 requests per hour per authenticated user.

## Usage

Open `index.html` in a browser to view the full API documentation.
