# etj
JSON to env converter.

# Example
Use this sample env.
```
ENV_A=a
ENV_B=b
ENV_C=c
```

Pass `env` command output to etj, etj converts to json map.

```
$ env | etj
"ENV_A":"a",
"ENV_B":"b",
"ENV_C":"c"
```

# Installation
Please folow.
```
$ curl -L https://raw.githubusercontent.com/convto/etj/master/etj > /usr/local/bin/etj
$ chmod +x /usr/local/bin/etj
```

# Usage
Pass env.
```
$ env | etj
$ cat .env.test | etj
$ go env | etj
```
