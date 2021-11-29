---
title: OrderManager.GetCreditMemo Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCreditMemo Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetCreditMemo(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getcreditmemo(v=AX.60)
ms:contentKeyID: 62208753
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetCreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# GetCreditMemo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the credit memo information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCreditMemo ( _
    id As String _
) As CreditMemo
'Usage
Dim instance As OrderManager
Dim id As String
Dim returnValue As CreditMemo

returnValue = instance.GetCreditMemo(id)
```

``` csharp
public CreditMemo GetCreditMemo(
    string id
)
```

``` c++
public:
CreditMemo^ GetCreditMemo(
    String^ id
)
```

#### Parameters

  - id  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CreditMemo](creditmemo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The credit memo information.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

