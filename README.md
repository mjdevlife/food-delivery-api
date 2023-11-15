# Food Ordering API Service

## Technology Stacks Used

- Node with Express
- Sequelize with PostgreSQL

## Running the project locally

- Clone the repository by running

```bash
 git clone git@github.com:mjdevlife/food-delivery-api.git
```

- In the root of your project create a `.env` and set the following environmental variables
- This configuration should point to a postgresql database

```bash
DB_USERNAME=
DB_PASSWORD=
DB_NAME=
DB_HOST=
JWT_LIFETIME=1d
JWT_SECRET=<random string>
```

- Inside the root of your project terminal

```bash
 npm install or yarn install
```

- Set up database models into your database by running the below command in terminal

```bash
  npx sequelize-cli db:migrate
```

- This should populate your database with all the necessary tables for the application to run

- Finally start the project by running

```bash
node app.js
```
