---
title: TerminalDataManager.GetPaymentConnector Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPaymentConnector Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TerminalDataManager.GetPaymentConnector(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.terminaldatamanager.getpaymentconnector(v=AX.60)
ms:contentKeyID: 62210734
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TerminalDataManager.GetPaymentConnector
dev_langs:
- CSharp
- C++
- VB
---

# GetPaymentConnector Method

Gets the payment connector setting for the terminal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetPaymentConnector ( _
    terminalId As String _
) As PaymentConnectorConfiguration
'Usage
Dim instance As TerminalDataManager
Dim terminalId As String
Dim returnValue As PaymentConnectorConfiguration

returnValue = instance.GetPaymentConnector(terminalId)
```

``` csharp
public PaymentConnectorConfiguration GetPaymentConnector(
    string terminalId
)
```

``` c++
public:
virtual PaymentConnectorConfiguration^ GetPaymentConnector(
    String^ terminalId
) sealed
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentConnectorConfiguration](paymentconnectorconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The payment connector configuration.  

#### Implements

[ITerminalDataManager.GetPaymentConnector(String)](iterminaldatamanager-getpaymentconnector-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[TerminalDataManager Class](terminaldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

