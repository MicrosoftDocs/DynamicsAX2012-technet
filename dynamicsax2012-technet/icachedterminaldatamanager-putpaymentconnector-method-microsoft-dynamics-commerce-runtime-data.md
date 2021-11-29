---
title: ICachedTerminalDataManager.PutPaymentConnector Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutPaymentConnector Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTerminalDataManager.PutPaymentConnector(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentConnectorConfiguration)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedterminaldatamanager.putpaymentconnector(v=AX.60)
ms:contentKeyID: 62215128
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTerminalDataManager.PutPaymentConnector
dev_langs:
- CSharp
- C++
- VB
---

# PutPaymentConnector Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Puts the payment connector setting for the terminal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutPaymentConnector ( _
    terminalId As String, _
    result As PaymentConnectorConfiguration _
)
'Usage
Dim instance As ICachedTerminalDataManager
Dim terminalId As String
Dim result As PaymentConnectorConfiguration

instance.PutPaymentConnector(terminalId, _
    result)
```

``` csharp
void PutPaymentConnector(
    string terminalId,
    PaymentConnectorConfiguration result
)
```

``` c++
void PutPaymentConnector(
    String^ terminalId, 
    PaymentConnectorConfiguration^ result
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentConnectorConfiguration](paymentconnectorconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedTerminalDataManager Interface](icachedterminaldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

