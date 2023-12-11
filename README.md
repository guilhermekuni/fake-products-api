### Fake Products App API | JSON Server Fake API

This is a Fake API built with [JSON Server](https://github.com/typicode/json-server). It was made to be used as the server for a Web App challenge.

### Testing the published API:
- You can check the published API on: https://my-json-server.typicode.com/guilhermekuni/fake-products-api/products

### Running locally
1. Clone this repository.
2. Run `yarn` to install the dependecies.
3. Run `yarn start` to start the API.
4. Go to `localhost:8000`.

### Testing
1. Run the API locally.
2. Point the requests to `{BASE_URL}/products`

**Note:** The `BASE_URL` is your domain. 
- If you are testing locally, your `BASE_URL` is `localhost:8000/`.
- If you are testing with the published API, your `BASE_URL` is `https://my-json-server.typicode.com/guilhermekuni/fake-products-api/`

### Pagination
1. To have pagination working, we just need to include `_page` and `_limit` query params.
2. Example: `{BASE_URL}/products?_page=1&_limit=5`

### Filters
1. To have filters working, we just need to include query params matching the properties names.
2. Example: `{BASE_URL}/products?category=fiction`
