---
title: DeviceConfiguration.NfcEContingencyModeEnabled Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NfcEContingencyModeEnabled Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.NfcEContingencyModeEnabled
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.nfcecontingencymodeenabled(v=AX.60)
ms:contentKeyID: 65319590
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.NfcEContingencyModeEnabled
dev_langs:
- CSharp
- C++
- VB
---

# NfcEContingencyModeEnabled Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NFCECONTINGENCYMNODENABLED")> _
Public Property NfcEContingencyModeEnabled As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.NfcEContingencyModeEnabled

instance.NfcEContingencyModeEnabled = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NFCECONTINGENCYMNODENABLED")]
public string NfcEContingencyModeEnabled { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NFCECONTINGENCYMNODENABLED")]
public:
property String^ NfcEContingencyModeEnabled {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

