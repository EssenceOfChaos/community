# Community

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.


## Use this implementation

  * Clone the project, install the dependencies and create the database as instructed above
  * Navigate to localhost:5000/graphiql to view the graphiql UI
  * Check out the docs to view the auto-generated documentation
  * Run a query for all links with
  ```
  {
  allLinks {
    id
    url
    description
  }
}
```
