---
title: MakePaymentRequest.TenderTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: TenderTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentRequest.TenderTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.makepaymentrequest.tendertypeid(v=AX.60)
ms:contentKeyID: 65319633
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentRequest.TenderTypeId
dev_langs:
- CSharp
- C++
- VB
---

# TenderTypeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tender type id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderTypeId As String
    Get
    Private Set
'Usage
Dim instance As MakePaymentRequest
Dim value As String

value = instance.TenderTypeId
```

``` csharp
[DataMemberAttribute]
public string TenderTypeId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TenderTypeId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[MakePaymentRequest Class](makepaymentrequest-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

