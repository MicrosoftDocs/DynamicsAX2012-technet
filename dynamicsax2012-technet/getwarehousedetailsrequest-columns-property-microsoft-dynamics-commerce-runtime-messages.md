---
title: GetWarehouseDetailsRequest.Columns Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Columns Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetWarehouseDetailsRequest.Columns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getwarehousedetailsrequest.columns(v=AX.60)
ms:contentKeyID: 62210892
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetWarehouseDetailsRequest.Columns
dev_langs:
- CSharp
- C++
- VB
---

# Columns Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the columns.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Columns As ColumnSet
    Get
    Set
'Usage
Dim instance As GetWarehouseDetailsRequest
Dim value As ColumnSet

value = instance.Columns

instance.Columns = value
```

``` csharp
[DataMemberAttribute]
public ColumnSet Columns { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ColumnSet^ Columns {
    ColumnSet^ get ();
    void set (ColumnSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  
Returns [ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[GetWarehouseDetailsRequest Class](getwarehousedetailsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

