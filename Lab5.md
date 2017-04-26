## 1

```
> specdata = "/home/oksana/R_task/R/specdata"
>
> pmean(specdata, "sulfate", 1:10)
[1] 4.064128
> pmean(specdata, "sulfate", 55)
[1] 3.587319
> pmean(specdata, "nitrate")
[1] 1.702932
```

## 2
```
> complete(specdata, 1)
id nobs
1  1  117
> complete(specdata, c(2, 4, 8, 10, 12))
  id nobs
1  2 1041
2  4  474
3  8  192
4 10  148
5 12   96
> complete(specdata, 50:60)
   id nobs
1  50  459
2  51  193
3  52  812
4  53  342
5  54  219
6  55  372
7  56  642
8  57  452
9  58  391
10 59  445
11 60  448
```

## 3
```
> cr <- corr(specdata, 150)
> head(cr); summary(cr)
[1] -0.01895754 -0.14051254 -0.04389737 -0.06815956 -0.12350667 -0.07588814
```
