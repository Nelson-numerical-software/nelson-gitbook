



QObject_get


QObject_get

Retrieve a property value from an QObject handle.

## Syntax

- R = get(h, property_name)

## Input argument

 - h - an QObject handle.
 - property_name - a string: property name.

## Output argument

 - R - The data type of the return value depends on the invoked method.

## Description


  <p><b>R = get(h, property_name)</b> returns the value of property asked.</p>


## See also

QObject_set.md QObject_set (set), get.md get.
## Example

```Nelson
h = errordlg()
h.visible // or get(h, 'visible')
h.title // or get(h, 'title')
```

## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET


