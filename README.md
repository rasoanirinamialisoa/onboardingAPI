**Project README**

# 1.1 - Description OpenAPI 3.0: STD22026

This project is an OpenAPI 3.0 specification for the STD22026 API. The version is 1.0.11. It provides endpoints to manage student information. The API allows retrieving student status information through a `GET` request and updating it via a `POST` request. The API responses include successful status information and internal server error details.

## Endpoints

### /students

#### GET

- **Summary**: Retrieve student status information.
- **Responses**:
  - `200`: Successful response content in JSON format.
  - `500`: Internal server error response in JSON format.

#### POST

- **Summary**: Update student status information.
- **Request Body**: JSON content required.
- **Responses**:
  - Successful update: `200` with JSON response.
  - `500`: Internal server error response in JSON format.

## Schemas

- `StatusResponse`: Referenced schema for successful responses.
- `ErrorResponse`: Referenced schema for internal server error responses.

## Servers

- Server URL: [https://STD22026.com](https://STD22026.com)
