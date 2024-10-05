# Album REST API

A simple RESTful API built with Go and Gin framework for managing music albums.

## Description

This API provides endpoints to perform CRUD operations on a collection of music albums. Each album contains information about its ID, title, artist, and price.

## Features

- Get all albums
- Get a specific album by ID
- Add a new album

## Prerequisites

- Go 1.16 or higher
- Gin web framework

## Installation


1. Install dependencies
```bash
go get -u github.com/gin-gonic/gin
```

## Usage

1. Start the server
```bash
go run main.go
```

The server will start on `localhost:8080`

## API Endpoints

### Get all albums
```
GET /albums
```

### Get album by ID
```
GET /albums/:id
```

### Add new album
```
POST /albums
```
Request body example:
```json
{
    "id": "3",
    "title": "To Pimp A Butterfly",
    "artist": "Kendrick Lamar",
    "price": 59.99
}
```

## Sample Data

The API comes pre-loaded with sample albums:
- DAMN. by Kendrick Lamar
- Section.80 by Kendrick Lamar
- Black Panther: The Album by Kendrick Lamar
- Whole Lotta Red by Playboi Carti

