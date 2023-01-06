# minio+rclone+artivc learning

> should install rclone+artivc

## Running

* init

```code
docker-compose up -d
```

* rclone config

> remote with myremote

```code
rclone config 
```

* artivc init

```code
avc init rclone://myremote/dalong/demoappfirst
```