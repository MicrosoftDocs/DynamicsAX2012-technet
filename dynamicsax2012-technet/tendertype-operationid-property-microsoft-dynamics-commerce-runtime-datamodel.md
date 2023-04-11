---
title: TenderType.OperationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OperationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.OperationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.operationid(v=AX.60)
ms:contentKeyID: 62210442
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.OperationId
dev_langs:
- CSharp
- C++
- VB
---

# OperationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the operation identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OPERATIONID")> _
Public Property OperationId As Integer
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Integer

value = instance.OperationId

instance.OperationId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OPERATIONID")]
public int OperationId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OPERATIONID")]
public:
property int OperationId {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

