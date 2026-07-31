# File Metadata Microservice

A freeCodeCamp API project that accepts a file upload and returns its metadata (name, MIME type, and size) as JSON.

## Stack

- **Runtime:** Node.js
- **Framework:** Express
- **File handling:** multer (memory storage)

## How to run

The app starts automatically via the **Start application** workflow (`node index.js`), which listens on port 5000.

## API

### `POST /api/fileanalyse`

Upload a file using `multipart/form-data` with the field name `upfile`.

**Response:**
```json
{ "name": "example.txt", "type": "text/plain", "size": 1234 }
```

## User preferences

_None recorded yet._
