Setup a dev environment

Manually set

1. `CUDA_PREFIX` in `activate`


Run the following


```
make repos
make env
. activate_
make deps
make ucx/install
make build
```

Verify the ucx-py isntall with

```
$ cd ucx-py
$ python -m pytest tests
```

Verify the distributed isntall with


```
python -m pytest distributed/comm/tests/test_ucx.py
```
