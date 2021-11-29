---
title: Customer.CreatedDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreatedDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CreatedDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.createddatetime(v=AX.60)
ms:contentKeyID: 62212645
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CreatedDateTime
dev_langs:
- CSharp
- C++
- VB
---

# CreatedDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the timestamp the customer was created.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CREATEDDATETIME")> _
<DataMemberAttribute> _
<RequiredToBeUtcAttribute(True)> _
Public Property CreatedDateTime As DateTimeOffset
    Get
    Set
'Usage
Dim instance As Customer
Dim value As DateTimeOffset

value = instance.CreatedDateTime

instance.CreatedDateTime = value
```

``` csharp
[ColumnAttribute("CREATEDDATETIME")]
[DataMemberAttribute]
[RequiredToBeUtcAttribute(true)]
public DateTimeOffset CreatedDateTime { get; set; }
```

``` c++
[ColumnAttribute(L"CREATEDDATETIME")]
[DataMemberAttribute]
[RequiredToBeUtcAttribute(true)]
public:
property DateTimeOffset CreatedDateTime {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
The customer datetime timestamp.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

