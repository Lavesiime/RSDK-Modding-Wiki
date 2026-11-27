# Cos

Gets the value from the `cos512` lookup table based on `angle` and sets it in `store`.

## Parameters

`store`

:   The variable to store the result.

`angle`

:   The value of the angle.

## Return Value

Sets `store` to the result.

## Syntax

```
Cos(var store, int angle)
```

## Example

```
Cos(temp0, 0)   // temp0 = Cos(0) = 512
Cos(temp0, 128) // temp0 = Cos(128) = 0
Cos(temp0, 256) // temp0 = Cos(256) = -512
Cos(temp0, 384) // temp0 = Cos(384) = 0

// temp0 = Cos(object.angle)
Cos(temp0, object.angle)
```
