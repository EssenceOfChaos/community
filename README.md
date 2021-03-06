# Community

An Elixir/Phoenix application with GraphQL. View [screenshot](https://github.com/EssenceOfChaos/community/blob/master/assets/images/screenshot.png)

## Use this implementation

*   Install dependencies with `mix deps.get`
*   Create and migrate your database with `mix ecto.create && mix ecto.migrate`
*   Start Phoenix endpoint with `mix phx.server`

---

*   Navigate to localhost:5000/graphiql to view the graphiql UI
*   Check out the docs to view the auto-generated documentation
*   Run a query for all links with:

```graphql
query {
	allLinks {
		id
		description
		url
	}
}
```
