---
title: DeviceConfiguration.StaffCardLogOn Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StaffCardLogOn Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StaffCardLogOn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.staffcardlogon(v=AX.60)
ms:contentKeyID: 62212968
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StaffCardLogOn
dev_langs:
- CSharp
- C++
- VB
---

# StaffCardLogOn Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether staff card logon is set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STAFFCARDLOGON")> _
Public Property StaffCardLogOn As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.StaffCardLogOn

instance.StaffCardLogOn = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STAFFCARDLOGON")]
public bool StaffCardLogOn { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STAFFCARDLOGON")]
public:
property bool StaffCardLogOn {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if staff card logon is set; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

