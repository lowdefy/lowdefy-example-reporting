# 📊 Lowdefy Reporting Example

> [View this example.](https://example-reporting.lowdefy.com)

This example demonstrates useful patterns for building a BI report/dashboard pages in Lowdefy. It connects to a MongoDB database with the Atlas Movies sample dataset pre-loaded.

## ⚙️ Running this example

- Create a MongoDB cluster and get a URI connection string:
  - Create a free MongoDB database cluster hosted by [MongoDB Atlas](https://www.mongodb.com/try).
  - Load the Atlas sample dataset.
  - In the Database access section, create a database user with read access to any database (You can also specify the database as `sample_mflix`).
  - In the main cluster view, click "connect", then "Connect your application". This will give a MongoDB URI connection string. Use the credentials you just created.
  - You can read more about the [Lowdefy MongoDB connector](https://docs.lowdefy.com/MongoDB).
- Clone this repository.
- Create a `.env` file in your project folder and set your MongoDB database connector URI as a variable in the `.env` file: `LOWDEFY_SECRET_EXAMPLES_MDB="{{ your_mongodb_connection_uri }}"`
- In the command console, navigate to your project folder and run the Lowdefy CLI: `pnpx lowdefy@4 dev`.

## 🔗 More Lowdefy resources

- Getting started with Lowdefy - https://docs.lowdefy.com/tutorial-start
- Lowdefy docs - https://docs.lowdefy.com
- Lowdefy website - https://lowdefy.com
- Community forum - https://github.com/lowdefy/lowdefy/discussions
- Bug reports and feature requests - https://github.com/lowdefy/lowdefy/issues
- Discord - https://discord.gg/WmcJgXt

## ⚖️ Licence

[MIT](https://github.com/lowdefy/lowdefy-example-reporting/blob/main/LICENSE)
