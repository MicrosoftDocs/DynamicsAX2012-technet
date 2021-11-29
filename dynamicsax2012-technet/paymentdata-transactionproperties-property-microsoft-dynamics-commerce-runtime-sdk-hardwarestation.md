---
title: PaymentData.TransactionProperties Property  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: TransactionProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData.TransactionProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.paymentdata.transactionproperties(v=AX.60)
ms:contentKeyID: 65323102
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData.TransactionProperties
dev_langs:
- CSharp
- C++
- VB
---

# TransactionProperties Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction properties as an XML blob format.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionProperties As String
    Get
    Private Set
'Usage
Dim instance As PaymentData
Dim value As String

value = instance.TransactionProperties
```

``` csharp
[DataMemberAttribute]
public string TransactionProperties { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TransactionProperties {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PaymentData Class](paymentdata-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

