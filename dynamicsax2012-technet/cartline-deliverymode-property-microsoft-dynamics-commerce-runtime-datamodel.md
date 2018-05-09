---
title: CartLine.DeliveryMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.DeliveryMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.deliverymode(v=AX.60)
ms:contentKeyID: 62211535
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.DeliveryMode
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryMode Property

Gets or sets the delivery mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryMode As String
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As String

value = instance.DeliveryMode

instance.DeliveryMode = value
```

``` csharp
[DataMemberAttribute]
public string DeliveryMode { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeliveryMode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The delivery mode.  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

