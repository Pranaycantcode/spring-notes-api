# Spring Notes API

A small Spring Boot project built to understand the basics of Java backend development, REST APIs, Spring Data JPA, and H2 Database.

## Tech Stack

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Maven

## Features

- Create a note
- Get all notes
- Get note by ID
- Update a note
- Delete a note
- View stored data using H2 Console

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/hello` | Test endpoint |
| GET | `/notes` | Get all notes |
| GET | `/notes/{id}` | Get note by ID |
| POST | `/notes` | Create note |
| PUT | `/notes/{id}` | Update note |
| DELETE | `/notes/{id}` | Delete note |

## Sample POST Body

```json
{
  "title": "First Spring Note",
  "content": "Learning Spring Boot CRUD"
}