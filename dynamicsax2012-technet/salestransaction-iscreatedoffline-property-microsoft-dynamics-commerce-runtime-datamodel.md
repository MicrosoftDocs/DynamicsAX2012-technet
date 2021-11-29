---
title: SalesTransaction.IsCreatedOffline Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsCreatedOffline Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsCreatedOffline
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.iscreatedoffline(v=AX.60)
ms:contentKeyID: 62214659
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsCreatedOffline
dev_langs:
- CSharp
- C++
- VB
---

# IsCreatedOffline Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether transaction is created in offline mode (used in ePOS only).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISCREATEDOFFLINE")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("ISCREATEDOFFLINE")> _
Public Property IsCreatedOffline As Boolean
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Boolean

value = instance.IsCreatedOffline

instance.IsCreatedOffline = value
```

``` csharp
[ColumnAttribute("ISCREATEDOFFLINE")]
[DataMemberAttribute]
[ReadOnlyAttribute("ISCREATEDOFFLINE")]
public bool IsCreatedOffline { get; set; }
```

``` c++
[ColumnAttribute(L"ISCREATEDOFFLINE")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"ISCREATEDOFFLINE")]
public:
property bool IsCreatedOffline {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

