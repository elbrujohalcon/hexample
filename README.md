# hexample
Example on how erlang.mk fails with hex for lager

## What happens?
```bash
$ make
…
$ ls deps
lager
```

## What **should** happen?
```bash
$ make
…
$ ls deps
goldrush lager
```
