# tinfoil
(thin folly), folly as needed by mvfst

Only those folly headers required by mvfst. Trims down folly from 784 to 384 headers.

```shell
mvfst/_build/deps/include/tinfoil$ find . -type f | wc -l
559
mvfst/_build/deps/include/folly$ find . -type f | wc -l
784
```
