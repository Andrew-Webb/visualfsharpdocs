# Lazy.CreateFromValue<'T> Extension Method (F#)

Creates a lazy computation that evaluates to the given value when forced.

**Namespace/Module Path:** Microsoft.FSharp.Control.LazyExtensions

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
type System.Lazy with
member static CreateFromValue : Lazy<'T>

// Usage:
lazy.CreateFromValue (value)


```





#### Parameters
*value*
Type: **'T**


The input value.



**The created [Lazy](http://msdn.microsoft.com/en-us/library/b29d0af5-6efb-4a55-a278-2662a4ecc489) object.**
## Remarks
**The following code example illustrates the use of the Lazy.CreateFromValue extension method. In this example, a dictionary is used to store previously computed values. When the factorial function is called, if the value is already computed, then Lazy.CreateFromValue is called with the cached result. If the value is not already computed, then Lazy.Create is used.**
[!code-fsharp[Main](snippets/fscorelib2/snippet12.fs)]
**Output**
**Creating lazy factorial for 12.**
**Evaluating lazy factorial for 12.**
**479001600**
**Reading factorial for 10 from cache.**
**3628800**
**Reading factorial for 11 from cache.**
**39916800**
**Creating lazy factorial for 30.**
**Evaluating lazy factorial for 30.**
**265252859812191058636308480000000**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0




## See Also
[Control.LazyExtensions Module &#40;F&#35;&#41;](Control.LazyExtensions-Module-%5BFSharp%5D.md)

[Lazy Computations &#40;F&#35;&#41;](Lazy-Computations-%5BFSharp%5D.md)

