---
title: CartLine.RequestedDeliveryDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RequestedDeliveryDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.RequestedDeliveryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.requesteddeliverydate(v=AX.60)
ms:contentKeyID: 62202103
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.RequestedDeliveryDate
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
<DataMemberAttribute> _
Public Property RequestedDeliveryDate As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Nullable(Of DateTimeOffset)

value = instance.RequestedDeliveryDate

instance.RequestedDeliveryDate = value
```

``` csharp
[DataMemberAttribute]
public Nullable<DateTimeOffset> RequestedDeliveryDate { get; set; }
```

``` c++
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

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

