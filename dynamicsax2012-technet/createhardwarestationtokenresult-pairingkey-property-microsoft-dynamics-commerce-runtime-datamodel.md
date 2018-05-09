---
title: CreateHardwareStationTokenResult.PairingKey Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PairingKey Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CreateHardwareStationTokenResult.PairingKey
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.createhardwarestationtokenresult.pairingkey(v=AX.60)
ms:contentKeyID: 65319585
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CreateHardwareStationTokenResult.PairingKey
dev_langs:
- CSharp
- C++
- VB
---

# PairingKey Property

Gets or sets the pairing key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PairingKey As String
    Get
    Set
'Usage
Dim instance As CreateHardwareStationTokenResult
Dim value As String

value = instance.PairingKey

instance.PairingKey = value
```

``` csharp
[DataMemberAttribute]
public string PairingKey { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ PairingKey {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CreateHardwareStationTokenResult Class](createhardwarestationtokenresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

