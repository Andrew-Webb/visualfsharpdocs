# Operators.float32<^T> Function (F#)

Converts the argument to 32-bit float. This is a direct conversion for all primitive numeric types. For strings, the input is converted using **M:System.Single.Parse(System.String)** with **P:System.Globalization.CultureInfo.InvariantCulture** settings. Otherwise the operation requires an appropriate static conversion method on the input type.

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
float32 : ^T -> float32 (requires ^T with static member op_Explicit)

// Usage:
float32 value


```





#### Parameters
*value*
Type: **^T**


The input value.



**The converted float32 value.**
## Remarks
This function is named **ToSingle** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.Operators Module &#40;F&#35;&#41;](Core.Operators-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

