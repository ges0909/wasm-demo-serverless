# Tests

## Simple

```shell
curl --silent http://127.0.0.1:3000/simple | python -m json.tool
```

```shell
curl --silent https://demo-xtzjs1xt.fermyon.app/simple | python -m json.tool
```

### Load test

```shell
hey -c 20 -n 1000 https://demo-xtzjs1xt.fermyon.app/simple
```

## Outbound

```shell
curl --silent https://demo-xtzjs1xt.fermyon.app/outbound | python -m json.tool
```

## Info

```shell
curl --silent https://demo-xtzjs1xt.fermyon.app/info
```
