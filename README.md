# DEPRECATED
> [!WARNING]  
> This is no longer supported as native Gnosis Chain support has been introduced. Please consider using the alternative setup path provided is [official documentation](https://docs.gnosischain.com/node/manual/beacon/nimbus).


```shell
docker build -t gnosischain/nimbus:latest --build-arg UPSTREAM_VERSION=v2.2.2 .
```

```shell
docker push gnosischain/nimbus:latest
```

# Starting the container in beacon mode 
```
--network="/custom_config_data"
--bootstrap-node="{{ bootnode_enrs | join(',') }}"
```

# Starting the container in validator mode
```
nimbus runs in both modes automatically 
```
