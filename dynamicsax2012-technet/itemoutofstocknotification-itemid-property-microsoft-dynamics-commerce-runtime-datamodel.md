---
title: ItemOutOfStockNotification.ItemId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemOutOfStockNotification.ItemId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemoutofstocknotification.itemid(v=AX.60)
ms:contentKeyID: 65322144
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemOutOfStockNotification.ItemId
dev_langs:
- CSharp
- C++
- VB
---

# ItemId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the unmatched address with sales tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemId As String
    Get
    Private Set
'Usage
Dim instance As ItemOutOfStockNotification
Dim value As String

value = instance.ItemId
```

``` csharp
[DataMemberAttribute]
public string ItemId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ItemId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ItemOutOfStockNotification Class](itemoutofstocknotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

