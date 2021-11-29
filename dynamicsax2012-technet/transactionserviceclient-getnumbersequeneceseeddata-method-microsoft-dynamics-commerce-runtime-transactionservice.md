---
title: TransactionServiceClient.GetNumberSequeneceSeedData Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetNumberSequeneceSeedData Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetNumberSequeneceSeedData(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getnumbersequeneceseeddata(v=AX.60)
ms:contentKeyID: 65322336
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetNumberSequeneceSeedData
dev_langs:
- CSharp
- C++
- VB
---

# GetNumberSequeneceSeedData Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetNumberSequeneceSeedData ( _
    terminalId As String _
) As IEnumerable(Of NumberSequenceSeedData)
'Usage
Dim instance As TransactionServiceClient
Dim terminalId As String
Dim returnValue As IEnumerable(Of NumberSequenceSeedData)

returnValue = instance.GetNumberSequeneceSeedData(terminalId)
```

``` csharp
public IEnumerable<NumberSequenceSeedData> GetNumberSequeneceSeedData(
    string terminalId
)
```

``` c++
public:
IEnumerable<NumberSequenceSeedData^>^ GetNumberSequeneceSeedData(
    String^ terminalId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[NumberSequenceSeedData](numbersequenceseeddata-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

