# Dyn_data

Some data sets for [dyn](https://github.com/kyleparisi/dyn).

## Movies

```bash
# npm i
node load.js
node import.js
```

## ProductCatalog

```bash
# Make a table in AWS Console with name: ProductCatalog and Primary Key: Id (Number)
aws dynamodb batch-write-item --request-items file://ProductCatalog.json
```