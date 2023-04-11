---
title: CustomerBalances.PendingTransactionsAnchor Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PendingTransactionsAnchor Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerBalances.PendingTransactionsAnchor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customerbalances.pendingtransactionsanchor(v=AX.60)
ms:contentKeyID: 62212709
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerBalances.PendingTransactionsAnchor
dev_langs:
- CSharp
- C++
- VB
---

# PendingTransactionsAnchor Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property PendingTransactionsAnchor As Long
    Get
    Set
'Usage
Dim instance As CustomerBalances
Dim value As Long

value = instance.PendingTransactionsAnchor

instance.PendingTransactionsAnchor = value
```

``` csharp
[IgnoreDataMemberAttribute]
public long PendingTransactionsAnchor { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property long long PendingTransactionsAnchor {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[CustomerBalances Class](customerbalances-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

