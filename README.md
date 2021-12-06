# **Serviceshaft.com**
---

A nodeJs project using [NestJs](https://nestjs.com/), [TypeORM](https://typeorm.io/), and [GraphQL](https://graphql.org/).


## **Running locally**

Make sure you have [Node.js](http://nodejs.org/) , [Redis](https://redis.io/) and [Postgress](https://www.postgresql.org/) installed. Follow the steps given below to run the project loacally.

#### Clone the project 
```sh
git clone git@github.com:aashishdhawan/markarian-backend.git
```


#### Go to project directory
```sh
cd markarian-backend
```

#### To checkout a branch (dev)
```sh
git fetch
git checkout -b dev --track origin/dev
```

#### Install dependencies
```sh
npm install
```

#### Cofigure environment
```sh
cp .env.example .env
``` 


#### For migrations
```sh
npm run typeorm migration:run
```

#### Start the server
```sh
npm run start:dev
```

Your app should now be running on [localhost:3000](http://localhost:3000/).

## **Running Tests**

#### To run testcases, run the following command

```sh
  npm run test
```

#### To check test report

```sh
npm run ts-coverage
```
