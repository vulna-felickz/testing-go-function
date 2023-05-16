# testing-go-function

# CodeQL local

## DB Create
```
codeql database create go-db --overwrite --language=go
```

## DB Analyze
```
codeql database analyze go-db --format=sarif-latest --output=results-go.sarif
```