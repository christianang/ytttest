# Ytt Test Experiments

Experimenting with how ytt may allow you to override existing real
implementations of code with mocks, while still allowing you to use real
implementations.

```
ytt -f config.yml -f mocks/providers -f providers
```
