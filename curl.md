# cURL (Client URL)

```command
curl google.com
```

| Argument                     | Description                                     |
| ---------------------------- | ----------------------------------------------- |
| -I, --head                   | Show document info only                         |
| -i, --include                | Include protocol response headers in the output |
| -X, --request \<command>     | Specify request command to use                  |
| -H, --header \<header/@file> | Pass custom header(s) to server                 |
| -D

### With bearer token to see the header

```command
curl -s -D- -H "Authorization: Bearer %token%" https://google.com
```