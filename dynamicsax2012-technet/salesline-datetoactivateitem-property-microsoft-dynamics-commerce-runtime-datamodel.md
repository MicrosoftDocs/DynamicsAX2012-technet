---
title: SalesLine.DateToActivateItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateToActivateItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.DateToActivateItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.datetoactivateitem(v=AX.60)
ms:contentKeyID: 49853281
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.DateToActivateItem
dev_langs:
- CSharp
- C++
- VB
---

# DateToActivateItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the date when the items becomes active.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DateToActivateItem As DateTimeOffset
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As DateTimeOffset

value = instance.DateToActivateItem

instance.DateToActivateItem = value
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset DateToActivateItem { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset DateToActivateItem {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

