---
title: CartLineData.ElectronicDeliveryEmail Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ElectronicDeliveryEmail Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ElectronicDeliveryEmail
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.electronicdeliveryemail(v=AX.60)
ms:contentKeyID: 62210124
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ElectronicDeliveryEmail
dev_langs:
- CSharp
- C++
- VB
---

# ElectronicDeliveryEmail Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value for the electronic delivery email address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ELECTRONICDELIVERYEMAIL")> _
<IgnoreDataMemberAttribute> _
Public Property ElectronicDeliveryEmail As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.ElectronicDeliveryEmail

instance.ElectronicDeliveryEmail = value
```

``` csharp
[ColumnAttribute("ELECTRONICDELIVERYEMAIL")]
[IgnoreDataMemberAttribute]
public string ElectronicDeliveryEmail { get; set; }
```

``` c++
[ColumnAttribute(L"ELECTRONICDELIVERYEMAIL")]
[IgnoreDataMemberAttribute]
public:
property String^ ElectronicDeliveryEmail {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

