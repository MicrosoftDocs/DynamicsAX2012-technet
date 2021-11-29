---
title: Transaction.StoreId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StoreId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction.StoreId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transaction.storeid(v=AX.60)
ms:contentKeyID: 62208745
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction.StoreId
dev_langs:
- CSharp
- C++
- VB
---

# StoreId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the store identifier where this transaction was created.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STORE")> _
<DataMemberAttribute> _
Public Property StoreId As String
    Get
    Set
'Usage
Dim instance As Transaction
Dim value As String

value = instance.StoreId

instance.StoreId = value
```

``` csharp
[ColumnAttribute("STORE")]
[DataMemberAttribute]
public string StoreId { get; set; }
```

``` c++
[ColumnAttribute(L"STORE")]
[DataMemberAttribute]
public:
property String^ StoreId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Transaction Class](transaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

