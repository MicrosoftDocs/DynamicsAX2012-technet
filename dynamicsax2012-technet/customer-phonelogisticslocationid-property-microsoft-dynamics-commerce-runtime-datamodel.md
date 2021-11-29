---
title: Customer.PhoneLogisticsLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PhoneLogisticsLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PhoneLogisticsLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.phonelogisticslocationid(v=AX.60)
ms:contentKeyID: 62211321
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PhoneLogisticsLocationId
dev_langs:
- CSharp
- C++
- VB
---

# PhoneLogisticsLocationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the phone logistics location id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PHONELOCATIONID")> _
<IgnoreDataMemberAttribute> _
Public Property PhoneLogisticsLocationId As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.PhoneLogisticsLocationId

instance.PhoneLogisticsLocationId = value
```

``` csharp
[ColumnAttribute("PHONELOCATIONID")]
[IgnoreDataMemberAttribute]
public string PhoneLogisticsLocationId { get; set; }
```

``` c++
[ColumnAttribute(L"PHONELOCATIONID")]
[IgnoreDataMemberAttribute]
public:
property String^ PhoneLogisticsLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The phone logistics location id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

