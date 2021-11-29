---
title: TransactionLogDataManager.GenerateTransactionId Method (String) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GenerateTransactionId Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TransactionLogDataManager.GenerateTransactionId(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.transactionlogdatamanager.generatetransactionid(v=AX.60)
ms:contentKeyID: 62212124
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GenerateTransactionId Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Generates a unique transaction identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function GenerateTransactionId ( _
    orgUnitNumber As String _
) As String
'Usage
Dim orgUnitNumber As String
Dim returnValue As String

returnValue = Me.GenerateTransactionId(orgUnitNumber)
```

``` csharp
protected string GenerateTransactionId(
    string orgUnitNumber
)
```

``` c++
protected:
String^ GenerateTransactionId(
    String^ orgUnitNumber
)
```

#### Parameters

  - orgUnitNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
A new transaction id formatted as "StoreId-TerminalId-SequenceNumber".  

## See Also

#### Reference

[TransactionLogDataManager Class](transactionlogdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GenerateTransactionId Overload](transactionlogdatamanager-generatetransactionid-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

