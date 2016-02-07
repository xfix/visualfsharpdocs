# LanguagePrimitives.GenericEqualityERComparer Function (F#)

Return an F# comparer object suitable for hashing and equality. This hashing behavior of the returned comparer is not limited by an overall node count when hashing F# records, lists and union types. This equality comparer has equivalence relation semantics ([nan] = [nan]).

**Namespace/Module Path:** Microsoft.FSharp.Core.LanguagePrimitives

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax

```
// Signature:
GenericEqualityERComparer :  IEqualityComparer

// Usage:
GenericEqualityERComparer
```

## Remarks

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.LanguagePrimitives Module &#40;F&#35;&#41;](Core.LanguagePrimitives+Module+%28FSharp%29.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core+Namespace+%28FSharp%29.md)
