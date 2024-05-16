# Example ERC721 token API

This example shows how to create a GraphQL API for an ERC721 token using Ponder. It uses ERC721 ABI, but you need to add configuration of deployment chain as well as AWS to an ".env.local" file

## Sample queries

### Get all tokens currently owned by an account

```graphql
{
  account(id: "0x2B8E4729672613D69e5006a97dD56A455389FB2b") {
    id
    tokens {
      id
    }
  }
}
```

