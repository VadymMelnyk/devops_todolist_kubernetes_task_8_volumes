### Run .sh script

```bash
./bootstrap.sh
```

### Open sh of your pod

```bash
kubectl exec <pod-name> -it -- sh
```


### How to validate: App is running

```bash
curl http://todoapp-service
```

### How to validate: ConfigMap data is mounted as files in the right order

```bash
cat configs/PYTHONUNBUFFERED
```

### How to validate: Secret data is mounted as a file

```bash
cat secrets/SECRET_KEY
```