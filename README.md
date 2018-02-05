# base-docker
Base docker to setup developer environment

## Environment Information
- Ubuntu
- Nginx
- MySql v8.x
    - MYSQL_USER: default
    - MYSQL_PASSWORD: secret
    - MYSQL_DATABASE: default
- PHP-FPM 7.1

## Usage Commands
### Initial docker configure

```shell
./dev init
```

### Build or rebuild environment

```shell
./dev build
```

### Start environment from begin

```shell
./dev start
```

### Run environment

```shell
./dev run
```

### List containers in environment

```shell
./dev status
```

### Open services in environment

```shell
./dev open
```

#### Example

```shell
./dev open mysql
OR
./dev open workspace
```

### Stop environment

```shell
./dev stop
```