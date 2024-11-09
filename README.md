# Summary

Codon (JIT) performance tests vs python

## Results

### With Python 3.12 (codon-jit package recompiled locally):

```
JIT (no warm) Version 0.9460秒
JIT Version 0.1077秒
JIT full loop Version 0.0124秒
Normal Version 0.0086秒
Performance Inprovement -92.00%
Performance Inprovement with full loop -30.54%
```

### With codon 0.17.0 (removing import codon and @codon.jit from the code)

```
Codon Version 0.02099秒
Codon (Release build) Version 0.0083秒
```
