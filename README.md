# GET STARTED

To get started, clone the repository and install dependencies:

```bash
git clone xx &&
cd mongoDBExpressLearn &&
npm i install  # or yarn if you prefer that package manager over npm
```

Express app with MongoDB integration in Nodejs
Then create a `.env` file in root directory with your MongoDB connection string as follows (replace 
<your_connection_string>`):

```bash
MONGODB_URI=<your_connection_string>
PORT=3001   # optional port number to use for development server; defaults to process
NODE_ENV=development    # set this value to "production" when deploying on production environment
SECRET="mysecretkeygoeshere"    # secret key used by jsonwebtoken middleware
JWT_EXPIRATION='24h'   # expiration time of JWT tokens generated using jwtmiddleware
```




Now we can launch our application locally either via command line interface (`nodemon`) or directly from node
(`npm`). To do so, simply type one of these commands below depending on which method you want
to choose:

```bash
DEBUG=mongodb-express-learn:* npm run dev
```

```bash
DEBUG=mongodb-express-learn:* npm start
````

