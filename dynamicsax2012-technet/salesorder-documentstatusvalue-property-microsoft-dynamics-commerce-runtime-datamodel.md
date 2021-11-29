---
title: SalesOrder.DocumentStatusValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DocumentStatusValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder.DocumentStatusValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesorder.documentstatusvalue(v=AX.60)
ms:contentKeyID: 62210959
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder.DocumentStatusValue
dev_langs:
- CSharp
- C++
- VB
---

# DocumentStatusValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the document status enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DocumentStatusValue As Integer
    Get
    Set
'Usage
Dim instance As SalesOrder
Dim value As Integer

value = instance.DocumentStatusValue

instance.DocumentStatusValue = value
```

``` csharp
[DataMemberAttribute]
public int DocumentStatusValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int DocumentStatusValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrder Class](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

