# Printf.fprintfn<'T> Function (F#)

Prints to a text writer, adding a newline.

**Namespace/Module Path:** Microsoft.FSharp.Core.Printf

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
fprintfn : TextWriter -> TextWriterFormat<'T> -> 'T

// Usage:
fprintfn textWriter format


```





#### Parameters
*textWriter*
Type: **T:System.IO.TextWriter**


The **T:System.IO.TextWriter** instance to print to.


*format*
Type: [TextWriterFormat](http://msdn.microsoft.com/en-us/library/2080c4a5-7bdd-4a01-8e01-10b498af92de)**&lt;'T&gt;**


The input formatter.



**The return type and arguments of the formatter.**
## Remarks
This function is named **PrintFormatLineToTextWriter** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.Printf Module &#40;F&#35;&#41;](Core.Printf-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

