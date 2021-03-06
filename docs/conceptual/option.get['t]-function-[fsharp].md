# Option.get<'T> Function (F#)

Gets the value associated with the option.

**Namespace/Module Path:** Microsoft.FSharp.Core.Option

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
get : 'T option -> 'T

// Usage:
get option


```





#### Parameters
*option*
Type: **'T**[option](http://msdn.microsoft.com/en-us/library/b08add48-34bf-4410-80a1-ef6a8daddc58)


The input option.



**exceptions tag is not supported!!!!**
**The value within the option.**
## Remarks
This function is named **GetValue** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code illustrates the use of Option.get.**
[!code-fsharp[Main](snippets/fsoptions/snippet7.fs)]
**Output**
**1"xyz"1.0**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.Option Module &#40;F&#35;&#41;](Core.Option-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

