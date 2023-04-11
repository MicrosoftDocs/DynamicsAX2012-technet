---
title: PaymentData.Platform Property  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: Platform Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData.Platform
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.paymentdata.platform(v=AX.60)
ms:contentKeyID: 65316050
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData.Platform
dev_langs:
- CSharp
- C++
- VB
---

# Platform Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the platform type Desktop/WindowsPhone or WindowsRuntime.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Platform As String
    Get
    Set
'Usage
Dim instance As PaymentData
Dim value As String

value = instance.Platform

instance.Platform = value
```

``` csharp
[DataMemberAttribute]
public string Platform { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Platform {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PaymentData Class](paymentdata-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

