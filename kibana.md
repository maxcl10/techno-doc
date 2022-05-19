# Kibana

## Query

Simple query to search for logs with logLevel is 'ERROR'

```json
{
  "query": {
    "match": {
      "logLevel": {
        "query": "ERROR",
        "type": "phrase"
      }
    }
  }
}
```

Simple query to search for logs by trackingId

```json
{
  "query": {
    "match": {
      "trackingId": {
        "query": "7f366990-92e4-4f39-813b-1bf6d739f055",
        "type": "phrase"
      }
    }
  }
}
```
