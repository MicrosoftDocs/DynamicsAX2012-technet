---
title: PaymentData Constructor  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: PaymentData Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData.#ctor(System.String,System.String,System.String,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.paymentdata.paymentdata(v=AX.60)
ms:contentKeyID: 65317539
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# PaymentData Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [PaymentData](paymentdata-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    paymentConnectorName As String, _
    merchantProperties As String, _
    transactionProperties As String, _
    isTestMode As Boolean, _
    cardType As CardType, _
    cardTypeName As String, _
    isCardTokenRequired As Boolean _
)
'Usage
Dim paymentConnectorName As String
Dim merchantProperties As String
Dim transactionProperties As String
Dim isTestMode As Boolean
Dim cardType As CardType
Dim cardTypeName As String
Dim isCardTokenRequired As Boolean

Dim instance As New PaymentData(paymentConnectorName, _
    merchantProperties, transactionProperties, _
    isTestMode, cardType, cardTypeName, _
    isCardTokenRequired)
```

``` csharp
public PaymentData(
    string paymentConnectorName,
    string merchantProperties,
    string transactionProperties,
    bool isTestMode,
    CardType cardType,
    string cardTypeName,
    bool isCardTokenRequired
)
```

``` c++
public:
PaymentData(
    String^ paymentConnectorName, 
    String^ merchantProperties, 
    String^ transactionProperties, 
    bool isTestMode, 
    CardType cardType, 
    String^ cardTypeName, 
    bool isCardTokenRequired
)
```

#### Parameters

  - paymentConnectorName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - merchantProperties  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionProperties  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isTestMode  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - cardType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType](cardtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cardTypeName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isCardTokenRequired  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[PaymentData Class](paymentdata-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

