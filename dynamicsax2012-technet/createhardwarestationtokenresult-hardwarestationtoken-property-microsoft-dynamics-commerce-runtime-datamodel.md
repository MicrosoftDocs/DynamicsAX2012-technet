---
title: CreateHardwareStationTokenResult.HardwareStationToken Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HardwareStationToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CreateHardwareStationTokenResult.HardwareStationToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.createhardwarestationtokenresult.hardwarestationtoken(v=AX.60)
ms:contentKeyID: 65321056
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CreateHardwareStationTokenResult.HardwareStationToken
dev_langs:
- CSharp
- C++
- VB
---

# HardwareStationToken Property

Gets or sets the hardware station token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HardwareStationToken As String
    Get
    Set
'Usage
Dim instance As CreateHardwareStationTokenResult
Dim value As String

value = instance.HardwareStationToken

instance.HardwareStationToken = value
```

``` csharp
[DataMemberAttribute]
public string HardwareStationToken { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ HardwareStationToken {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CreateHardwareStationTokenResult Class](createhardwarestationtokenresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

