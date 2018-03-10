

# le

less than or equal, ≤ operator.

## Syntax

- C = le(A, B)

## Input argument

 - A - a variable
 - B - a variable

## Output argument

 - C - result of le(A, B)

## Description


  <p><b>C = le(A, B)</b> returns a logical array with elements set to logical <b>true</b> A is less than or equal to B.</p>
  <p/>


## Examples

```Nelson
eye(2,2) &#60;= ones(2, 2)
```
```Nelson
0 &#60;= i
```
```Nelson
'Nelson' &#60;= 'Noslen'
```
```Nelson
'Nelson' &#60;= 'l'
```
```Nelson
le(0.8 - 0.6 - 0.2, 0)
```

## See also

[ne](ne.md), [lt](lt.md), [ge](ge.md), [gt](gt.md), [eq](eq.md).
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET


