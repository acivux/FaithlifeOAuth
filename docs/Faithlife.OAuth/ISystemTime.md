# ISystemTime interface

Provides a mechanism for getting the current system time.

```csharp
public interface ISystemTime
```

## Members

| name | description |
| --- | --- |
| [GetUtcNow](ISystemTime/GetUtcNow.md)() | Gets the current UTC time. |

## Remarks

This is intended to return the current system time in production, but can return a fixed value for testing.

## See Also

* namespace [Faithlife.OAuth](../Faithlife.OAuth.md)
* [ISystemTime.cs](https://github.com/Faithlife/FaithlifeOAuth/tree/master/src/Faithlife.OAuth/ISystemTime.cs)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.OAuth.dll -->