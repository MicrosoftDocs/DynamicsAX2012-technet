---
title: CartLineData.Status Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Status Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.Status
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.status(v=AX.60)
ms:contentKeyID: 62209931
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.Status
dev_langs:
- CSharp
- C++
- VB
---

# Status Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TRANSACTIONSTATUS")> _
Public Property Status As TransactionStatus
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As TransactionStatus

value = instance.Status

instance.Status = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TRANSACTIONSTATUS")]
public TransactionStatus Status { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TRANSACTIONSTATUS")]
public:
property TransactionStatus Status {
    TransactionStatus get ();
    void set (TransactionStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus](transactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The status.  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

