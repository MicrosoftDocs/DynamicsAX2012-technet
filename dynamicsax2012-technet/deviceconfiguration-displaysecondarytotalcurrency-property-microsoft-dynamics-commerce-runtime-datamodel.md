---
title: DeviceConfiguration.DisplaySecondaryTotalCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DisplaySecondaryTotalCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.DisplaySecondaryTotalCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.displaysecondarytotalcurrency(v=AX.60)
ms:contentKeyID: 62214472
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.DisplaySecondaryTotalCurrency
dev_langs:
- CSharp
- C++
- VB
---

# DisplaySecondaryTotalCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether display secondary total currency is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISPLAYSECONDARYTOTALCURRENCY")> _
Public Property DisplaySecondaryTotalCurrency As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.DisplaySecondaryTotalCurrency

instance.DisplaySecondaryTotalCurrency = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISPLAYSECONDARYTOTALCURRENCY")]
public bool DisplaySecondaryTotalCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISPLAYSECONDARYTOTALCURRENCY")]
public:
property bool DisplaySecondaryTotalCurrency {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if display secondary total currency is set; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

