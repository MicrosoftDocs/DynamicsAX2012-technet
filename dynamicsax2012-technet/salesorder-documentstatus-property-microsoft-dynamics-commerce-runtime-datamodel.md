---
title: SalesOrder.DocumentStatus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DocumentStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder.DocumentStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesorder.documentstatus(v=AX.60)
ms:contentKeyID: 62208743
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder.DocumentStatus
dev_langs:
- CSharp
- C++
- VB
---

# DocumentStatus Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the document status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("DOCUMENTSTATUS")> _
Public Property DocumentStatus As DocumentStatus
    Get
    Set
'Usage
Dim instance As SalesOrder
Dim value As DocumentStatus

value = instance.DocumentStatus

instance.DocumentStatus = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("DOCUMENTSTATUS")]
public DocumentStatus DocumentStatus { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"DOCUMENTSTATUS")]
public:
property DocumentStatus DocumentStatus {
    DocumentStatus get ();
    void set (DocumentStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DocumentStatus](documentstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DocumentStatus](documentstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesOrder Class](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

