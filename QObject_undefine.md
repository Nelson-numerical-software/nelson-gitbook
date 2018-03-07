



QObject_undefine


QObject_undefine

Undefine a dynamic property of a QObject handle.

## Syntax

- QObject_undefine(h, property_name)

## Input argument

 - h - an QObject handle.
 - property_name - a string : dynamic property name.

## Output argument

 - R - a string: method signature.

## Description


  <p>Undefine a dynamic property of a QObject handle.</p>


## See also

QObject_set.md QObject_set (set), QObject_get.md QObject_get (get).
## Example

```Nelson
h = errordlg()
set(h, 'myProp', 33)
h
get(h, 'myProp')
QObject_undefine(h, 'myProp')
get(h, 'myProp')
```

## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET


