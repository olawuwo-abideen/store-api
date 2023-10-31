# Storeapi

Develop a versatile online store application that empowers businesses to sell products and services online while providing a seamless shopping experience for customers.

## Features

- **User**: User can create, read, update, and delete product.

## Built With:

- JavaScript
- Node
- Express
- dotenv
- mongoose
- nodemon
- express-async-error
- cookie-parser
- helmet
- express-rate-limit

## Installation

- clone the repository

```sh
git clone git@github.com:olawuwo-abideen/store-api.git
```

- navigate to the folder

```sh
cd store-api.git
```

## Run the app in development mode

Open a terminal window session, or the equivalent on your machine, and enter the following command to install all the
Node modules needed to run the app:

```sh
npm install
```

After doing an `npm install` enter the following `npm start` command:

```sh

npm start

```

Set up the environment variables:

Create the .env file and setup the MongoDB URL.

The server will start running on the specified port (default: 3000) and establish a connection to the MongoDB database.

This will start the app and set it up to listen for incoming connections on port 3000. Open up your browser of choice
and go to the url

```sh

http://localhost:3000

```

to start using the app.

## API Endpoints

The following API endpoints are available:

- BaseUrl https://localhost:3000/

- `POST /api/v1/products` - Register a new product
- `GET /api/v1/products` - Read a product
- `GET /api/v1/products/static` - Read products by params such as name, price, company name and rating

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/olawuwo-abideen/store-api/issues).

## Authors

👤 **Olawuwo Abideen**

- GitHub: [@Olawuwo Abideen](https://github.com/olawuwo-abideen)
- Twitter: [@Olawuwo Abideen](https://twitter.com/olawuwo_abideen)
- LinkedIn: [@Olawuwo Abideen](https://www.linkedin.com/in/olawuwo-abideen/)
