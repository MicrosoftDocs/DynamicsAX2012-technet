---
title: DeviceConfiguration.StoreNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StoreNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StoreNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.storenumber(v=AX.60)
ms:contentKeyID: 62211031
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StoreNumber
dev_langs:
- CSharp
- C++
- VB
---

# StoreNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the store number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<KeyAttribute> _
<ColumnAttribute("STORENUMBER")> _
<DataMemberAttribute> _
Public Property StoreNumber As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.StoreNumber

instance.StoreNumber = value
```

``` csharp
[KeyAttribute]
[ColumnAttribute("STORENUMBER")]
[DataMemberAttribute]
public string StoreNumber { get; set; }
```

``` c++
[KeyAttribute]
[ColumnAttribute(L"STORENUMBER")]
[DataMemberAttribute]
public:
property String^ StoreNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the store number.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

