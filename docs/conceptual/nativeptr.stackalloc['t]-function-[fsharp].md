# NativePtr.stackalloc<'T> Function (F#)

Allocates a region of memory on the stack.

**Namespace/Module Path:** Microsoft.FSharp.NativeInterop.NativePtr

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
NativePtr.stackalloc : int -> nativeptr<'T> (requires unmanaged)

// Usage:
NativePtr.stackalloc count


```





#### Parameters
*count*
Type: [int](http://msdn.microsoft.com/en-us/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)


The number of objects of type T to allocate.



**A typed pointer to the allocated memory.**
## Remarks
This function is named **StackAllocate** in compiled assemblies. If you are accessing the member from a .NET language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[NativeInterop.NativePtr Module &#40;F&#35;&#41;](NativeInterop.NativePtr-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.NativeInterop Namespace &#40;F&#35;&#41;](Microsoft.FSharp.NativeInterop-Namespace-%5BFSharp%5D.md)

