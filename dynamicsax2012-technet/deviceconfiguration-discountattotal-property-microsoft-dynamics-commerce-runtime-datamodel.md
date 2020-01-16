---
title: DeviceConfiguration.DiscountAtTotal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountAtTotal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.DiscountAtTotal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.discountattotal(v=AX.60)
ms:contentKeyID: 62210473
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.DiscountAtTotal
dev_langs:
- CSharp
- C++
- VB
---

# DiscountAtTotal Property

Gets or sets the discount at total value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCOUNTATTOTAL")> _
<DataMemberAttribute> _
Public Property DiscountAtTotal As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.DiscountAtTotal

instance.DiscountAtTotal = value
```

``` csharp
[ColumnAttribute("DISCOUNTATTOTAL")]
[DataMemberAttribute]
public string DiscountAtTotal { get; set; }
```

``` c++
[ColumnAttribute(L"DISCOUNTATTOTAL")]
[DataMemberAttribute]
public:
property String^ DiscountAtTotal {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The discount at total.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

