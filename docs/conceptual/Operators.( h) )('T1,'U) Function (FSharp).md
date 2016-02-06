# Operators.( |> )<'T1,'U> Function (F#)

Apply a function to a value, the value being on the left, the function on the right.

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax

```
// Signature:
( |> ) : 'T1 -> ('T1 -> 'U) -> 'U

// Usage:
arg |> func
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*arg*
Type: **'T1**


The argument.


*func*
Type: **'T1 -&gt; 'U**


The function.



**The function result.**
## Remarks
**The following example demonstrates the use of the forward pipe operator.**
[!code-fsharp[Main](snippets/fsoperators/snippet1.fs)]
**"abc" |&gt; append1 gives "abc.append1"**
**result2: "abc.append1.append2"**
**300 200 100**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.Operators Module &#40;F&#35;&#41;](Core.Operators+Module+%28FSharp%29.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core+Namespace+%28FSharp%29.md)
