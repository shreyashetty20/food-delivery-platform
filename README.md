# Food Delivery Platform

Backend application for a food delivery platform.

## Features

* User management
* Address management
* Restaurant and menu management
* Order management
* Payment management
* Delivery tracking

## Tech Stack

* Java
* Spring Boot
* Spring Data JPA
* Hibernate
* PostgreSQL
* Gradle

## Project Structure

```text
food-delivery-platform/
└── backend/
    └── src/
        └── main/
            └── java/
                └── com.fooddelivery/
                    ├── user/
                    ├── restaurant/
                    ├── menu/
                    ├── order/
                    ├── payment/
                    └── tracking/
```

## Getting Started

### Prerequisites

* Java
* PostgreSQL
* Git

### Run the Application

Clone the repository:

```bash
git clone <repository-url>
cd food-delivery-platform
```

Build the project:

```bash
./gradlew build
```

Run the application:

```bash
./gradlew bootRun
```

The application will start on:

```text
http://localhost:8080
```

## API

The APIs follow the structure:

```text
/api/v1/{resource}
```

Example:

```text
GET    /api/v1/users
GET    /api/v1/users/{id}
POST   /api/v1/users
PUT    /api/v1/users/{id}
DELETE /api/v1/users/{id}
```

## Status

🚧 Work in progress.
