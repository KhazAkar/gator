# gator 

This project is a simple, golang based RSS feed aggregator from boot.dev course.

Necessary applications:
- PostgreSQL
- Golang (for building/running project)

## How to install
1. Clone the repository
2. Create a `.env` file in the root directory and add the following variables:
```env
DB_URL=postgres://postgres:postgres@localhost:5432/postgres?sslmode=disable
```
3. Create .gatorconfig.json file in the home directory with following content:
```json
{"db_url":"postgresql URL. If local - remember about sslmode=disable"}
```
4. Run the following command to start the server:
```bash
go run main.go
```

## How to build

1. Run the following command to build the project:
```bash
go build
```
