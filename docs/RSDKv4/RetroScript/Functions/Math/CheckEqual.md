# CheckEqual

Checks if `x` and `y` are equal and stores the result in `checkResult`.

## Parameters

`x`, `y`

:   The values to check.

## Return Value

Sets `checkResult` to the result.

## Syntax

```
CheckEqual(int x, int y)
```

## Example

```

// Sees if 14 and 20 are equal
CheckEqual(14, 20) // checkResult will be set to false, since they are not

// Sees if 20 and 20 are equal
CheckEqual(20, 20) // checkResult will be set to true, since they are indeed equal

// Sees if object.value2 and 100 are equal
CheckEqual(object.value2, 100)
```
