# Array.maxBy<'T,'U> Function (F#)

Returns the greatest of all elements of the array, compared by using [Operators.max](http://msdn.microsoft.com/en-us/library/9a988328-00e9-467b-8dfa-e7a6990f6cce) on the function result.

**Namespace/Module Path:** Microsoft.FSharp.Collections.Array

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
Array.maxBy : ('T -> 'U) -> 'T [] -> 'T (requires comparison)

// Usage:
Array.maxBy projection array


```





#### Parameters
*projection*
Type: **'T -&gt; 'U**


The function to transform the elements into a type supporting comparison.


*array*
Type: **'T**[[]](http://msdn.microsoft.com/en-us/library/def20292-9aae-4596-9275-b94e594f8493)


The input array.



**exceptions tag is not supported!!!!**
**The maximum element.**
## Remarks
This function is named **MaxBy** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code example demonstrates the use of Array.maxBy.**
[!code-fsharp[Main](snippets/fsarrays/snippet56.fs)]
**Output**
**0.0**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Array Module &#40;F&#35;&#41;](Collections.Array-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

