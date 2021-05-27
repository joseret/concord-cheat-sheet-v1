# concord-cheat-sheet-v1
concord-cheat-sheet-v1

```
curl -v --header "Authorization: ED06ecvY2MXy8i1ZxMKpdw" \
  localhost:8001/api/v1/process \
  -F org=Default -F project=joseret -F repo=joseret \
  -F entryPoint=test-groovy-simple \
  -F request='{"arguments": {"a1": "a1-data"}};type=application/octet-stream'
```

```
curl -v --header "Authorization: ED06ecvY2MXy8i1ZxMKpdw" \
  localhost:8001/api/v1/process \
  -F org=Default -F project=joseret -F repo=joseret \
  -F entryPoint=test-groovy-simple \
  -F request=@request.json
```

