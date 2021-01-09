<div align="center">
  <a href="https://mockoon.com" alt="mockoon logo">
    <img height="200" src="https://mockoon.com/images/logo-square.png">
  </a>
  <a href="https://docker.com" alt="docker logo">
    <img height="200" src="https://www.docker.com/sites/default/files/d8/2019-07/vertical-logo-monochromatic.png">
  </a>
  <br>
  <h1>Mockoon + Docker</h1>
</div>

### Run with docker-compose

1. Copy `.env.example` to `.env`
2. Replace the `docker/data.json` with your exported **Mockoon** data. [See here](https://mockoon.com/docs/latest/import-export-data/)
3. Run `docker-compose up -d`
4. You can access your mocked API at [http://localhost:3000/users](http://localhost:3000/users)

### Run without docker-compose

1. Enter `docker` directory
2. Replace the `data.json` with your exported **Mockoon** data.
3. Run `docker build -t my-mockoon .`
4. Run `docker run -d -p 3000:3000 my-mockoon`
5. You can access your mocked API at [http://localhost:3000/users](http://localhost:3000/users)
