# Mockoon Docker

### How to run with compose

1. Copy `.env.example` to `.env.example`
2. Replace the `docker/data.json` with your exported **Mockoon** data. [See here](https://mockoon.com/docs/latest/import-export-data/)
3. Run `docker-compose up -d`
4. You can access your mocked API at [http://localhost:3000/users](http://localhost:3000/users)

### Run without compose

1. Enter `docker` directory
2. Replace the `data.json` with your exported **Mockoon** data.
3. Run `docker build -t my-mockoon .`
4. Run `docker run -d -p 3000:3000 my-mockoon`
5. You can access your mocked API at [http://localhost:3000/users](http://localhost:3000/users)
