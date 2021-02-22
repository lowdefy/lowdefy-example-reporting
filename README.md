# Lowdefy Reporting Example

[![Netlify Status](https://api.netlify.com/api/v1/badges/51d48dcb-b42a-4d03-8740-2d8b861e4da9/deploy-status)](https://app.netlify.com/sites/lowdefy-example-reporting/deploys)

> [View this example.](https://example-reporting.lowdefy.com)

This example demonstrate useful patterns for building a BI report/dashboard pages in Lowdefy. It connects to a MongoDB database with the Atlas Movies sample dataset pre-loaded.

This reporting example is deployed using [Netlify](https://docs.lowdefy.com/deployment).

Three additional block types is loaded for this examples:

- `AmChartsXY` and `AmChartsPie` from [@lowdefy/blocks-amcharts](https://github.com/lowdefy/blocks-amcharts).
- `AgGridAlpine`, from [@lowdefy/blocks-aggrid](https://github.com/lowdefy/blocks-aggrid).

## Running this example

- Create a [MongoDB Atlas](https://www.mongodb.com/try) free tier cluster and select to load the sample dataset.
- Add a database user to the MongoDB database and generate a connection uri containing the database username and password. Be sure to create the database user with read privileges for the sample database. Read more about using [the Lowdefy MongoDB connector](https://docs.lowdefy.com/MongoDB).
- Clone this repository.
- Create a `.env` file in your project folder and set your MongoDB database connector URI as a variable in the `.env` file: `LOWDEFY_SECRET_EXAMPLES_MDB="{{ your_mongodb_connection_uri }}"`
- In the command console, navigate to your project folder and run the Lowdefy CLI: `npx lowdefy@latest dev`.

## More Lowdefy resources

- Getting started with Lowdefy - https://docs.lowdefy.com/tutorial-start
- Lowdefy docs - https://docs.lowdefy.com
- Lowdefy website - https://lowdefy.com
- Community forum - https://github.com/lowdefy/lowdefy/discussions
- Bug reports and feature requests - https://github.com/lowdefy/lowdefy/issues

## Licence

[MIT](https://github.com/lowdefy/lowdefy-example-reporting/blob/main/LICENSE)
