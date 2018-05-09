---
title: CartLineData.DeliveryMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.DeliveryMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.deliverymode(v=AX.60)
ms:contentKeyID: 49835762
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.DeliveryMode
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
<ColumnAttribute("DELIVERYMODE")> _
<DataMemberAttribute> _
Public Property DeliveryMode As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.DeliveryMode

instance.DeliveryMode = value
```

``` csharp
[ColumnAttribute("DELIVERYMODE")]
[DataMemberAttribute]
public string DeliveryMode { get; set; }
```

``` c++
[ColumnAttribute(L"DELIVERYMODE")]
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

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

