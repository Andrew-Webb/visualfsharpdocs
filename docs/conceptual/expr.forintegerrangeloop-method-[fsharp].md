# Expr.ForIntegerRangeLoop Method (F#)

Creates a **for** expression that represent loops over integer ranges.

**Namespace/Module Path:** Microsoft.FSharp.Quotations

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
static member ForIntegerRangeLoop : Var * Expr * Expr * Expr -> Expr

// Usage:
Expr.ForIntegerRangeLoop (loopVariable, start, endExpr, body)


```





#### Parameters
*loopVariable*
Type: [Var](http://msdn.microsoft.com/en-us/library/2b1237f9-d897-4bcf-872a-4a297db3f7b5)


The subexpression that declares the loop variable.


*start*
Type: [Expr](http://msdn.microsoft.com/en-us/library/ed6a2caf-69d4-45c2-ab97-e9b3be9bce65)


The subexpression that sets the initial value of the loop variable.


*endExpr*
Type: [Expr](http://msdn.microsoft.com/en-us/library/ed6a2caf-69d4-45c2-ab97-e9b3be9bce65)


The subexpression that declares the final value of the loop variable.


*body*
Type: [Expr](http://msdn.microsoft.com/en-us/library/ed6a2caf-69d4-45c2-ab97-e9b3be9bce65)


The subexpression that represents the body of the loop.



**The resulting expression.**
## Remarks

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Quotations.Expr Class &#40;F&#35;&#41;](Quotations.Expr-Class-%5BFSharp%5D.md)

[Microsoft.FSharp.Quotations Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Quotations-Namespace-%5BFSharp%5D.md)

