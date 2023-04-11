---
title: MakePaymentResponse.TenderLine Property  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: TenderLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentResponse.TenderLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.makepaymentresponse.tenderline(v=AX.60)
ms:contentKeyID: 65319510
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentResponse.TenderLine
dev_langs:
- CSharp
- C++
- VB
---

# TenderLine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tender line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderLine As TenderLine
    Get
    Private Set
'Usage
Dim instance As MakePaymentResponse
Dim value As TenderLine

value = instance.TenderLine
```

``` csharp
[DataMemberAttribute]
public TenderLine TenderLine { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property TenderLine^ TenderLine {
    TenderLine^ get ();
    private: void set (TenderLine^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[MakePaymentResponse Class](makepaymentresponse-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

