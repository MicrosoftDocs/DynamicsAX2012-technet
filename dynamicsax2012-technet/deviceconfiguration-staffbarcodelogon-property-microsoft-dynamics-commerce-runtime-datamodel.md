---
title: DeviceConfiguration.StaffBarcodeLogOn Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StaffBarcodeLogOn Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StaffBarcodeLogOn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.staffbarcodelogon(v=AX.60)
ms:contentKeyID: 62213725
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StaffBarcodeLogOn
dev_langs:
- CSharp
- C++
- VB
---

# StaffBarcodeLogOn Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether staff barcode logon is set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STAFFBARCODELOGON")> _
<DataMemberAttribute> _
Public Property StaffBarcodeLogOn As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.StaffBarcodeLogOn

instance.StaffBarcodeLogOn = value
```

``` csharp
[ColumnAttribute("STAFFBARCODELOGON")]
[DataMemberAttribute]
public bool StaffBarcodeLogOn { get; set; }
```

``` c++
[ColumnAttribute(L"STAFFBARCODELOGON")]
[DataMemberAttribute]
public:
property bool StaffBarcodeLogOn {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if staff barcode logon is set; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

