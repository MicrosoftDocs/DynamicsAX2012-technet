---
title: DeviceConfiguration.Currency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Currency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.Currency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.currency(v=AX.60)
ms:contentKeyID: 62208449
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.Currency
dev_langs:
- CSharp
- C++
- VB
---

# Currency Property

Gets or sets the currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CURRENCY")> _
<DataMemberAttribute> _
Public Property Currency As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.Currency

instance.Currency = value
```

``` csharp
[ColumnAttribute("CURRENCY")]
[DataMemberAttribute]
public string Currency { get; set; }
```

``` c++
[ColumnAttribute(L"CURRENCY")]
[DataMemberAttribute]
public:
property String^ Currency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the currency.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

