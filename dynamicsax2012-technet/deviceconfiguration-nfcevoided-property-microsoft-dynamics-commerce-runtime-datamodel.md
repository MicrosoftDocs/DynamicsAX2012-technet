---
title: DeviceConfiguration.NfcEVoided Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NfcEVoided Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.NfcEVoided
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.nfcevoided(v=AX.60)
ms:contentKeyID: 65320999
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.NfcEVoided
dev_langs:
- CSharp
- C++
- VB
---

# NfcEVoided Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NFCEVOIDED")> _
<DataMemberAttribute> _
Public Property NfcEVoided As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.NfcEVoided

instance.NfcEVoided = value
```

``` csharp
[ColumnAttribute("NFCEVOIDED")]
[DataMemberAttribute]
public string NfcEVoided { get; set; }
```

``` c++
[ColumnAttribute(L"NFCEVOIDED")]
[DataMemberAttribute]
public:
property String^ NfcEVoided {
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

