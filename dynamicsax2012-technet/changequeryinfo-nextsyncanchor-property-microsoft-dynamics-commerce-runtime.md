---
title: ChangeQueryInfo.NextSyncAnchor Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: NextSyncAnchor Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ChangeQueryInfo.NextSyncAnchor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.changequeryinfo.nextsyncanchor(v=AX.60)
ms:contentKeyID: 49853268
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ChangeQueryInfo.NextSyncAnchor
dev_langs:
- CSharp
- C++
- VB
---

# NextSyncAnchor Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the anchor for subsequent listing synchronizations for the specified destination.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property NextSyncAnchor As Long
    Get
    Friend Set
'Usage
Dim instance As ChangeQueryInfo
Dim value As Long

value = instance.NextSyncAnchor
```

``` csharp
public long NextSyncAnchor { get; internal set; }
```

``` c++
public:
property long long NextSyncAnchor {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ChangeQueryInfo Class](changequeryinfo-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

