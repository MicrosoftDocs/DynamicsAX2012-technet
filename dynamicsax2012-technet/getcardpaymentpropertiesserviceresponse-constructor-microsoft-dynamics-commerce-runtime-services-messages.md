---
title: GetCardPaymentPropertiesServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCardPaymentPropertiesServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceResponse.#ctor(System.String,System.String,System.String,System.String,System.Decimal,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcardpaymentpropertiesserviceresponse.getcardpaymentpropertiesserviceresponse(v=AX.60)
ms:contentKeyID: 65320288
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetCardPaymentPropertiesServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    accountType As String, _
    approvalCode As String, _
    connectorName As String, _
    providerTransactionId As String, _
    availableBalance As Decimal, _
    infoMessage As String, _
    portablePaymentPropertyXmlBlob As String _
)
'Usage
Dim accountType As String
Dim approvalCode As String
Dim connectorName As String
Dim providerTransactionId As String
Dim availableBalance As Decimal
Dim infoMessage As String
Dim portablePaymentPropertyXmlBlob As String

Dim instance As New GetCardPaymentPropertiesServiceResponse(accountType, _
    approvalCode, connectorName, providerTransactionId, _
    availableBalance, infoMessage, portablePaymentPropertyXmlBlob)
```

``` csharp
public GetCardPaymentPropertiesServiceResponse(
    string accountType,
    string approvalCode,
    string connectorName,
    string providerTransactionId,
    decimal availableBalance,
    string infoMessage,
    string portablePaymentPropertyXmlBlob
)
```

``` c++
public:
GetCardPaymentPropertiesServiceResponse(
    String^ accountType, 
    String^ approvalCode, 
    String^ connectorName, 
    String^ providerTransactionId, 
    Decimal availableBalance, 
    String^ infoMessage, 
    String^ portablePaymentPropertyXmlBlob
)
```

#### Parameters

  - accountType  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - approvalCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - connectorName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - providerTransactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - availableBalance  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - infoMessage  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - portablePaymentPropertyXmlBlob  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetCardPaymentPropertiesServiceResponse Class](getcardpaymentpropertiesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

