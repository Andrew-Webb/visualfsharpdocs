# QueryBuilder.AverageBy<'T,'Q,^Value> Method (F#)

A query operator that selects a value for each element selected so far and returns the average of these values.

**Namespace/Module Path**: Microsoft.FSharp.Linq

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
member this.AverageBy : QuerySource<'T,'Q> * ('T -> ^Value) -> ^Value when ^Value with static member (+) and ^Value with static member DivideByInt and ^Value with static member Zero

// Usage:
queryBuilder.AverageBy (source, projection)


```





#### Parameters
*source*
Type: [QuerySource](http://msdn.microsoft.com/en-us/library/873589c1-c5dc-47d9-8abf-fee7258dfb00)&lt;'T,'Q&gt;


The input query.


*projection*
Type: 'T -&gt; ^Value


A function that determines a value for each element.




## Return Value
The average of all the values produced by the projection function.


## Remarks
For more information and examples, see [Query Expressions (F#)](http://msdn.microsoft.com/en-us/library/ff72235c-3ad8-4215-8679-2754484823db)


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 4.0, Portable




## See Also
[Linq.QueryBuilder Class &#40;F&#35;&#41;](Linq.QueryBuilder-Class-%5BFSharp%5D.md)

[Microsoft.FSharp.Linq Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Linq-Namespace-%5BFSharp%5D.md)

