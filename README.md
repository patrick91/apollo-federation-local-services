# Example of Apollo Federation with local services

This is a very basic example of using Apollo Federation with local services.
Normally Apollo Gateway works with remote services, but it still allows to use local schema if you know how the internal works.

Read more about this here: [https://patrick.wtf/posts/apollo-federation-local-services](https://patrick.wtf/posts/apollo-federation-local-services)

## Run the example

This example wraps https://countries.trevorblades.com/ under Apollo Federation, to demonstrate how to
run Apollo Federation with local services (in this case, a schema that wraps a remote schema) and also
how to add federation directives to pre-existing schemas using [graphql-transform-federation](https://github.com/0xR/graphql-transform-federation).

To run make sure you have a recent version of node and run the following commands:

```sh
npm install
npm run start
```

Then should be able to access the Playground at [http://localhost:4000/](http://localhost:4000/)
