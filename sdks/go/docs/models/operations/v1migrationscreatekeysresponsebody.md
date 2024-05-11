# V1MigrationsCreateKeysResponseBody

The key ids of all created keys


## Fields

| Field                                                                                                                                       | Type                                                                                                                                        | Required                                                                                                                                    | Description                                                                                                                                 | Example                                                                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| `KeyIds`                                                                                                                                    | []*string*                                                                                                                                  | :heavy_check_mark:                                                                                                                          | The ids of the keys. This is not a secret and can be stored as a reference if you wish. You need the keyId to update or delete a key later. | [<br/>"key_123",<br/>"key_456"<br/>]                                                                                                        |