# Book Store

Welcome to the Book Store project! This is a simple Go application for managing books with CRUD operations (Create, Read, Update, Delete). The project uses the Gorilla Mux router and GORM for interacting with a MySQL database.

## Getting Started

### Prerequisites

- Go installed on your machine
- MySQL database

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Mayejacob/book-store.git
    ```

2. Navigate to the project directory:

    ```bash
    cd book-store/cmd/main
    ```

3. Run the application:

    ```bash
    go run main.go
    ```

    Or alternatively:

    ```bash
    go run .
    ```

   The server will start on [http://localhost:9010](http://localhost:9010).

## API Endpoints

- **List all books:** `GET /books/`
- **Retrieve details of a specific book:** `GET /books/{id}`
- **Add a new book:** `POST /books/`
- **Update details of an existing book:** `PUT /books/{id}`
- **Delete a book:** `DELETE /books/{id}`

## Example Usage

### List all books

```bash
curl http://localhost:9010/books/
```

### book by ID

```bash
curl http://localhost:8000/books/1
```