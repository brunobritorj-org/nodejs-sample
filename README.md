# (Sample) NodeJS

A simple Hello World page using NodeJS.

```
src/
├── index.js
├── package.json
└── package-lock.json
```

## Running

+ Using Docker

```
docker build . --tag nodejs-sample
docker run -p 3000:3000 nodejs-sample
```

+ Using Docker Compose

```
docker-compose up
```
