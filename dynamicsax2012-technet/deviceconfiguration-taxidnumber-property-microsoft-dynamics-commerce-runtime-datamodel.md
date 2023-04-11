---
title: DeviceConfiguration.TaxIdNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxIdNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TaxIdNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.taxidnumber(v=AX.60)
ms:contentKeyID: 62211388
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TaxIdNumber
dev_langs:
- CSharp
- C++
- VB
---

# TaxIdNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax id number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXIDENTIFICATIONNUMBER")> _
Public Property TaxIdNumber As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.TaxIdNumber

instance.TaxIdNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXIDENTIFICATIONNUMBER")]
public string TaxIdNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXIDENTIFICATIONNUMBER")]
public:
property String^ TaxIdNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the tax id number.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

