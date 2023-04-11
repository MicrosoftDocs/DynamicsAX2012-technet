---
title: DeviceConfiguration.ProductDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.ProductDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.productdiscount(v=AX.60)
ms:contentKeyID: 65323192
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.ProductDiscount
dev_langs:
- CSharp
- C++
- VB
---

# ProductDiscount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRODUCTDISCOUNT")> _
Public Property ProductDiscount As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.ProductDiscount

instance.ProductDiscount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRODUCTDISCOUNT")]
public string ProductDiscount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRODUCTDISCOUNT")]
public:
property String^ ProductDiscount {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

