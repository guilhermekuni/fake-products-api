### Fake Products App API | JSON Server Fake API

This is a Fake API built with [JSON Server](https://github.com/typicode/json-server). It was made to be used as the server for a Web App challenge.

### Running locally
1. Clone this repository.
2. Run `yarn` to install the dependecies.
3. Run `yarn start` to start the API.
4. Go to localhost:8000.

### Testing
1. Run the API locally.
2. Point the requests to `localhost:8000/products`

#### Pagination
1. To have pagination working, we just need to include `_page` and `_limit` query params.
2. Example: `localhost:8000/products?_page=1&_limit=5`

#### Filters
1. To have filters working, we just need to include query params matching the properties names.
2. Example: `localhost:8000/products?category=fiction`
