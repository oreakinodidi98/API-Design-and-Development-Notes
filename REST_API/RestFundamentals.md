# Rest Fundamentals

## Designing an API

- REST is a protocal
- No specific version

### REST URLs and Request Verbs

- Format is:
- Schemma;domain;port;path;query
- E.G https://www.carvedrockfutness.com:443/api/items/1?include=images
- **Schemma** =https
- **Domain** = www.carvedrockfutness.com
- **Port** = 443
- **Path** = /api/items/1
- **Query** = ?include=images -> optional -> allows you to modify request

REST Verbs

- Tell the Server what you want to do

| Web/Mobile UI | REST Verb | Database |
|---------------|-----------|----------|
| View          | GET       | READ     |
| Add           | POST      | CREATE   |
| Update        | PUT/PATCH | UPDATE   |
| Delete        | DELETE    | DELETE   |


| Use                       | REST Verb |
|---------------------------|-----------|
| Updating an entire item   | PUT       |
| Creating New items        | POST      |
| Updating part of an item  | PATCH     |