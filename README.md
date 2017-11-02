## GraphQL
Sample GraphQL Project
> https://github.com/apollographql/apollo-server

### Example Mutation
```
{
  "query": "mutation UpdateAccount ($attrs: UpdateAccountInput!) { updateAccount(account: $attrs) { id farmId }}",
  "variables": { "attrs": { "id":"71a6a833-8c36-4599-8883-194797ba4490", "farmId": "james" } }
}
```

### Example Query
```
{
    "query": "query { farm (keyword: \"leo\") { uuid address  } }"
}
```

### Example Query List
```
{
    "query": "query { farmList (keyword: \"sydney\") { items { uuid address name { en } } } }"
}
```
