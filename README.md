<h1 align="center">Scalable backend</h1>

<p align="center">An airbnb-like project with microservices architecture and communication with grpc </p>

<div align="center">

[Features](#Features) • [Installation](#Installation)

</div>




# Features
- Send emails with nodemailer & Gmail
- Use RabbitMQ to process & retry messages asynchronously
- GraphQL & Apollo Federation to build an API Gateway and expose our microservices
- Provision a load balancer to expose our application externally
- Test NestJS microservices using an E2E framework
- Integrate payment functionality with Stripe
- CRUD APIs & save data with MongoDB, Prisma & TypeORM
- Connect microservices together using gRPC
- An automated CI/CD pipeline with CloudBuild
- Production Dockerfile & package json for each microservice

# Installation

### Clone on your local machine

```bash
git clone https://github.com/joaoreider/scalable-backend
```

### Navigate to project directory

```bash
cd scalable-backend
```

### Install dependencies

```bash
pnpm install
```

### Rename .env.template to .env

```bash
mv .env.template .env
```

### Run 

```bash
# development
$ pnpm run start

# watch mode
$ pnpm run start:dev

# production mode
$ pnpm run start:prod
```


<br><br>

**Email**: *joaopauloj405@gmail.com*
