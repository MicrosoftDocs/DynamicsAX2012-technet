---
title: SalesTransactionDataManager.GetCustomerLocalPendingBalance Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCustomerLocalPendingBalance Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.GetCustomerLocalPendingBalance(System.String,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salestransactiondatamanager.getcustomerlocalpendingbalance(v=AX.60)
ms:contentKeyID: 62214590
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.GetCustomerLocalPendingBalance
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerLocalPendingBalance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sum of all transaction using tender type "pay to account" for a specific customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerLocalPendingBalance ( _
    accountNumber As String, _
    lastReplicationCounter As Long _
) As Decimal
'Usage
Dim instance As SalesTransactionDataManager
Dim accountNumber As String
Dim lastReplicationCounter As Long
Dim returnValue As Decimal

returnValue = instance.GetCustomerLocalPendingBalance(accountNumber, _
    lastReplicationCounter)
```

``` csharp
public decimal GetCustomerLocalPendingBalance(
    string accountNumber,
    long lastReplicationCounter
)
```

``` c++
public:
Decimal GetCustomerLocalPendingBalance(
    String^ accountNumber, 
    long long lastReplicationCounter
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - lastReplicationCounter  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Customer local balance for transactions not uploaded to AX.  

## See Also

#### Reference

[SalesTransactionDataManager Class](salestransactiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

