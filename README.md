# pgadmin-cf-deployment

cf deployment yaml to deploy pgadmin on cloud foundry using an existing DB to persist data.


```
cf set-env pgadmin-web PGADMIN_CONFIG_CONFIG_DATABASE_URI \
  "'postgresql://XXXXXXX:XXXXXXXX@XXXXXXXXXXXX:5432/postgres'"
```
