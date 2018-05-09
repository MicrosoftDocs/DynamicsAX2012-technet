---
title: ChangeQueryInfo.ExpectedLastSyncAnchor Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ExpectedLastSyncAnchor Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ChangeQueryInfo.ExpectedLastSyncAnchor
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.changequeryinfo.expectedlastsyncanchor(v=AX.60)
ms:contentKeyID: 49848205
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ChangeQueryInfo.ExpectedLastSyncAnchor
dev_langs:
- CSharp
- C++
- VB
---

# ExpectedLastSyncAnchor Property

Gets or sets the value compared against the stored last successful synchronization anchor for specified destination for listings to detect database restores.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ExpectedLastSyncAnchor As Long
    Get
    Set
'Usage
Dim instance As ChangeQueryInfo
Dim value As Long

value = instance.ExpectedLastSyncAnchor

instance.ExpectedLastSyncAnchor = value
```

``` csharp
public long ExpectedLastSyncAnchor { get; set; }
```

``` c++
public:
property long long ExpectedLastSyncAnchor {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ChangeQueryInfo Class](changequeryinfo-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

