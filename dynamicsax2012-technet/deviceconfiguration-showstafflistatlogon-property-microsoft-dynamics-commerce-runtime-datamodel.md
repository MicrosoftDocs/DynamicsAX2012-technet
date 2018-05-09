---
title: DeviceConfiguration.ShowStaffListAtLogOn Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShowStaffListAtLogOn Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.ShowStaffListAtLogOn
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.showstafflistatlogon(v=AX.60)
ms:contentKeyID: 62207641
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.ShowStaffListAtLogOn
dev_langs:
- CSharp
- C++
- VB
---

# ShowStaffListAtLogOn Property

Gets or sets a value indicating whether show staff list at logon is set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SHOWSTAFFLISTATLOGON")> _
<DataMemberAttribute> _
Public Property ShowStaffListAtLogOn As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.ShowStaffListAtLogOn

instance.ShowStaffListAtLogOn = value
```

``` csharp
[ColumnAttribute("SHOWSTAFFLISTATLOGON")]
[DataMemberAttribute]
public bool ShowStaffListAtLogOn { get; set; }
```

``` c++
[ColumnAttribute(L"SHOWSTAFFLISTATLOGON")]
[DataMemberAttribute]
public:
property bool ShowStaffListAtLogOn {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
The value true if show staff list at logon is set; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

