---
title: DeviceConfiguration.StaffBarcodeLogOnRequiresPassword Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StaffBarcodeLogOnRequiresPassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StaffBarcodeLogOnRequiresPassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.staffbarcodelogonrequirespassword(v=AX.60)
ms:contentKeyID: 62210160
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StaffBarcodeLogOnRequiresPassword
dev_langs:
- CSharp
- C++
- VB
---

# StaffBarcodeLogOnRequiresPassword Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether staff barcode logon requires password is set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STAFFBARCODELOGONREQUIRESPASSWORD")> _
<DataMemberAttribute> _
Public Property StaffBarcodeLogOnRequiresPassword As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.StaffBarcodeLogOnRequiresPassword

instance.StaffBarcodeLogOnRequiresPassword = value
```

``` csharp
[ColumnAttribute("STAFFBARCODELOGONREQUIRESPASSWORD")]
[DataMemberAttribute]
public bool StaffBarcodeLogOnRequiresPassword { get; set; }
```

``` c++
[ColumnAttribute(L"STAFFBARCODELOGONREQUIRESPASSWORD")]
[DataMemberAttribute]
public:
property bool StaffBarcodeLogOnRequiresPassword {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if staff barcode logon requires password is set; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

