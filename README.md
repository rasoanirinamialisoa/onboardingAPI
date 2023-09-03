**Project README**

# 1.1 - Description OpenAPI 3.0: STD22026
This project is an OpenAPI 3.0 specification for the STD22026 API. The version is 1.0.11. It provides endpoints to manage student and teacher information.

  
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
    
### /teachers

#### GET

- **Summary**: Retrieve teacher information.
- **Responses**:
  - `200`: Successful response content in JSON format.
  - `500`: Internal server error response in JSON format.

#### POST

- **Summary**: Add new teacher.
- **Request Body**: JSON content required.
- **Responses**:
  - Successful update: `200` with JSON response.
  - `500`: Internal server error response in JSON format.
    
## Schemas
- `StatusResponse`: Referenced schema for successful responses.
- `ErrorResponse`: Referenced schema for internal server error responses.
- `TeacherResponse`: Referenced schema for teacher responses.
- `TeacherRequest`: Referenced schema for teacher requests.
- `Course`: Referenced schema for courses.
  
#### PUT

- **Summary**: Update student information.
- **Request Body**: JSON content required.
- **Responses**:
  - Successful update: `200` with JSON response.
  - `500`: Internal server error response in JSON format.

#### DELETE

- **Summary**: Delete student information based on certain criteria.
- **Responses**:
  - Successful deletion: `200` with JSON response.
  - `500`: Internal server error response in JSON format.

## Servers
- Server URL: [https://STD22026.com](https://STD22026.com)

## Link
- Petstore URL : [https://petstore.swagger.io/?url=https://raw.githubusercontent.com/rasoanirinamialisoa/onboardingAPI/master/onboardingAPI.yaml)

