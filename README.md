# Go Health Checker

A simple tool to check the availability of websites using HTTP requests.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/AkhilSharma90/go-health-checker.git
    cd go-health-checker
    ```

2. Install dependencies (if needed):

    ```bash
    go mod tidy
    ```

3. Run the application:

    ```bash
    go run . --domain example.com
    ```

## Usage

### Options:
- `--domain, -d`  The domain name to check.
- `--port, -p`    The port to use (default is 80).
- `--help, -h`     Show help.

Example:

```bash
go run . --domain pexels.com
