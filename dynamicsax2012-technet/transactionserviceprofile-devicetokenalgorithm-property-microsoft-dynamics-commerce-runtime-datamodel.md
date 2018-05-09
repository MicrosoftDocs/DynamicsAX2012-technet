---
title: TransactionServiceProfile.DeviceTokenAlgorithm Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceTokenAlgorithm Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.DeviceTokenAlgorithm
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.devicetokenalgorithm(v=AX.60)
ms:contentKeyID: 62210249
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.DeviceTokenAlgorithm
dev_langs:
- CSharp
- C++
- VB
---

# DeviceTokenAlgorithm Property

Gets the device token encryption/decryption algorithm name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("DEVICETOKENALGORITHM")> _
Public ReadOnly Property DeviceTokenAlgorithm As String
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As String

value = instance.DeviceTokenAlgorithm
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("DEVICETOKENALGORITHM")]
public string DeviceTokenAlgorithm { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"DEVICETOKENALGORITHM")]
public:
property String^ DeviceTokenAlgorithm {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransactionServiceProfile Class](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

