# Minimal Python example with Gramine powered by Intel SGX

## Serialize argv

```console
$ gramine-argv-serializer "/usr/bin/python3.8" "scripts/main.py" "1" "2" "3" > scripts/args
```

## Build

```console
$ make SGX=1
```

## Exec

```console
$ gramine-sgx ./python
```

