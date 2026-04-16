# Grocery List Management API

A REST API for managing grocery lists and orders.

## Endpoints

| Method | Path | Description |
|--------|------|-------------|
| GET | `/api/grocery-lists` | Retrieve user's grocery lists |
| POST | `/api/grocery-lists` | Create a new grocery list |
| PUT | `/api/grocery-lists/{id}` | Update an existing list |
| DELETE | `/api/grocery-lists/{id}` | Remove a grocery list |

## Authentication

All requests require a Bearer token. Include it in the `Authorization` header as a JWT.

```
Authorization: Bearer <your-token>
```

## Rate Limits

API calls are limited to 1000 requests per hour per authenticated user.

## Error Handling

The API uses standard HTTP status codes to indicate success or failure.
