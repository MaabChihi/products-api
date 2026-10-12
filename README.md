# Products API

A Spring Boot REST API for product data.

## Requirements

- macOS
- Java 25

Check Java with `java -version`. Maven is provided by the included Maven Wrapper, so a separate Maven installation is not required.

## Run on macOS

From this directory, run:

```sh
./mvnw spring-boot:run
```

The API starts on `http://localhost:8080`. Product endpoints:

- `GET /products`
- `GET /products/{id}`

The project uses the `MaabChihi` GitHub account for new local commits. Existing commits and their original authorship are preserved.

## Attribution

This project is adapted from [Fatima Shahzad Arif's original products-api repository](https://github.com/fatima-shahzadarif/products-api). The original Git history is retained, and the original repository is kept as the `upstream` remote.
