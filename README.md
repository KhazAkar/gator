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

## License

Unless otherwise noted, the original material in this repository is licensed
under the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version (SPDX: `GPL-3.0-or-later`).
See [LICENSE](LICENSE) for the full license text.

Third-party material retains its own copyright notices and license terms.
