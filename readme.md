# Benchmark for Go hashmap



Run this benchmark via

```
gotip test -bench=. -run=NOTEST -count=10 -benchmem -timeout=10h >swiss_map.txt
GOEXPERIMENT=noswissmap  gotip test -run='^$' -timeout=10h -bench=. -count=10 > map.txt
```

