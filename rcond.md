



rcond


rcond

Inverse condition number.

## Syntax

- res = rcond(x)

## Input argument

 - x - a numeric value: scalar or square matrix (double or single)

## Output argument

 - res - a numeric value: a scalar.

## Description


  <p><b>rcond(x)</b> computes the reciprocal of the condition of x in the 1-norm.</p>


## Example

```Nelson
X = rand(10, 10);
r = rcond(X);
```

## See also

inv.md inv.
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET



