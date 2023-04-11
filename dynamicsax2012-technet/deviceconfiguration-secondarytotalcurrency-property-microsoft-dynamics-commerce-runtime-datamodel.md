---
title: DeviceConfiguration.SecondaryTotalCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SecondaryTotalCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.SecondaryTotalCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.secondarytotalcurrency(v=AX.60)
ms:contentKeyID: 62214729
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.SecondaryTotalCurrency
dev_langs:
- CSharp
- C++
- VB
---

# SecondaryTotalCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the secondary total currency value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SECONDARYTOTALCURRENCY")> _
<DataMemberAttribute> _
Public Property SecondaryTotalCurrency As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.SecondaryTotalCurrency

instance.SecondaryTotalCurrency = value
```

``` csharp
[ColumnAttribute("SECONDARYTOTALCURRENCY")]
[DataMemberAttribute]
public string SecondaryTotalCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"SECONDARYTOTALCURRENCY")]
[DataMemberAttribute]
public:
property String^ SecondaryTotalCurrency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the secondary total currency.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

