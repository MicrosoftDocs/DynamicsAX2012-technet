---
title: CartLine.ElectronicDeliveryEmail Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ElectronicDeliveryEmail Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.ElectronicDeliveryEmail
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.electronicdeliveryemail(v=AX.60)
ms:contentKeyID: 62213548
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.ElectronicDeliveryEmail
dev_langs:
- CSharp
- C++
- VB
---

# ElectronicDeliveryEmail Property

Gets or sets a value for the electronic delivery email address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property ElectronicDeliveryEmail As String
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As String

value = instance.ElectronicDeliveryEmail

instance.ElectronicDeliveryEmail = value
```

``` csharp
[IgnoreDataMemberAttribute]
public string ElectronicDeliveryEmail { get; set; }
```

``` c++
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

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

