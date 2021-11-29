---
title: CartLineData.RequestedDeliveryDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RequestedDeliveryDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.RequestedDeliveryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.requesteddeliverydate(v=AX.60)
ms:contentKeyID: 49831032
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.RequestedDeliveryDate
dev_langs:
- CSharp
- C++
- VB
---

# RequestedDeliveryDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the requested delivery date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REQUESTEDDELIVERYDATE")> _
<DataMemberAttribute> _
Public Property RequestedDeliveryDate As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Nullable(Of DateTimeOffset)

value = instance.RequestedDeliveryDate

instance.RequestedDeliveryDate = value
```

``` csharp
[ColumnAttribute("REQUESTEDDELIVERYDATE")]
[DataMemberAttribute]
public Nullable<DateTimeOffset> RequestedDeliveryDate { get; set; }
```

``` c++
[ColumnAttribute(L"REQUESTEDDELIVERYDATE")]
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> RequestedDeliveryDate {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
The requested delivery date.  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

