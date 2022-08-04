## Spring Boot Microservice 2 - Purchase Service

### Endpoints

#### Save Purchase

```
POST /api/purchase HTTP/1.1
Host: localhost:4444
Authorization: Basic cmFuZG9tU2VjdXJlS2V5VXNlcm5hbWUhOnJhbmRvbVNlY3VyZUtleVBhc3N3b3JkIQ==
Content-Type: application/json
Content-Length: 76

{
    "userId":1,
    "courseId":1,
    "title":"course-1",
    "price": 9
}
```

#### Get Purchase of User

```
GET /api/purchase/1 HTTP/1.1
Host: localhost:4444
Authorization: Basic cmFuZG9tU2VjdXJlS2V5VXNlcm5hbWUhOnJhbmRvbVNlY3VyZUtleVBhc3N3b3JkIQ==
```