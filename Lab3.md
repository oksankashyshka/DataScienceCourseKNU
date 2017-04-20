# Laba 3

## 1
```
> add2 <- function(arg1, arg2) {
+ return(arg1+arg2)
+ }
> add2(5, 8)
[1] 13

```

## 2
```
> above <- function(vector, n = 10) {
+ return (vector[vector > n])
+ }
> above(c(2, 5, 7, 10, 12))
[1] 12
> above(c(2, 5, 7, 10, 12), 5)
[1]  7 10 12

```

## 3
```
> my_ifelse <- function(vector_x, exp, n) {
+ switch(exp,
+ "<"={
+ return(vector_x[vector_x<n])
+ },
+ ">"={
+ return(vector_x[vector_x>n])
+ },
+ "<="={
+ return(vector_x[vector_x<=n])
+ },
+ ">="={
+ return(vector_x[vector_x>=n])
+ },
+ "=="={
+ return(vector_x[vector_x==n])
+ },
+ {
+ return(vector_x)
+ }
+ )
+ }
> my_ifelse(c(1, 2, 3), "Ґ", 5)
[1] 1 2 3
> my_ifelse(c(1, 2, 3, 8, 9), "<", 5)
[1] 1 2 3

```

## 4
```

```
