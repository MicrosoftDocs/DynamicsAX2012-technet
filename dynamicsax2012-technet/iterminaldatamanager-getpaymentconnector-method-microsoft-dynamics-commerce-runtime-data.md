---
title: ITerminalDataManager.GetPaymentConnector Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPaymentConnector Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ITerminalDataManager.GetPaymentConnector(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.iterminaldatamanager.getpaymentconnector(v=AX.60)
ms:contentKeyID: 62214245
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ITerminalDataManager.GetPaymentConnector
dev_langs:
- CSharp
- C++
- VB
---

# GetPaymentConnector Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetPaymentConnector ( _
    terminalId As String _
) As PaymentConnectorConfiguration
'Usage
Dim instance As ITerminalDataManager
Dim terminalId As String
Dim returnValue As PaymentConnectorConfiguration

returnValue = instance.GetPaymentConnector(terminalId)
```

``` csharp
PaymentConnectorConfiguration GetPaymentConnector(
    string terminalId
)
```

``` c++
PaymentConnectorConfiguration^ GetPaymentConnector(
    String^ terminalId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentConnectorConfiguration](paymentconnectorconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ITerminalDataManager Interface](iterminaldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

