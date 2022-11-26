## 1. NodeJS Template README

### 1.1. Requirements

- [x] Requirement 1

### 1.2 Documentation

##### 1.2.1 Development

- [Swagger Doc](http://localhost:3000/api)

##### 1.2.2 Production

- [Link](http://link)

### 2. To get started

```bash
git clone {repository link}

cd {repository name}

yarn husky install

yarn install

docker compose up -d

yarn start:dev

```

### 3. EVNS

##### Use .env for the ENV validation to work

| Name         | Value | Description                          |
| ------------ | ----- | ------------------------------------ |
| PORT         |       | Port                                 |
| NODE_ENV     |       | 'development' , 'test', 'production' |
| DATABASE_URL |       |                                      |
