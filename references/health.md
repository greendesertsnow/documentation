# Health

## Get health of MeiliSearch server
<RouteHighlighter method="GET" route="/health"/>

Get health of MeiliSearch server.

#### Headers

| Header              | Value         |
|---------------------|---------------|
| **X-Meili-API-Key** | `$API_KEY`    |
| **Accept-encoding** | gzip, deflate |


### Example

```bash
curl \
  --request GET 'http://localhost:8080/health' \
  --header "X-Meili-API-Key: $API_KEY"
```

#### Response: `204 No Content`


## Set Health of meiliSearch instance

<RouteHighlighter method="POST" route="/health"/>

Get health of MeiliSearch server.

#### Headers

| Header              | Value         |
|---------------------|---------------|
| **X-Meili-API-Key** | `$API_KEY`    |
| **Accept-encoding** | gzip, deflate |


### Example

```bash
curl \
  --request GET 'http://localhost:8080/health' \
  --header "X-Meili-API-Key: $API_KEY"
```

#### Response: `204 No Content`