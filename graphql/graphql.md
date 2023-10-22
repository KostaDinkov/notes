# GraphQL Notes

## Why GraphQL

***Problems of REST***

1. RESTfull routing with highly relational data becomes quite challenging.
2. In order to get related data, we either generate a multiple http requests to different endpoints or
3. Endpoints become too customized.
4. In most cases, the client receives more data than needed.

These are all solvable problems, but they require a lot of engineering time

***GraphQL solves above problems***

1. We make single request to a single endpoint
2. The query is sent in the body of the request
3. We get precisely the data we want, no more, no less.
