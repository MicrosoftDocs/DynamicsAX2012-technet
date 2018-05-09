---
title: TransactionServiceClient.GetReturnLocationByReasonCode Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetReturnLocationByReasonCode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetReturnLocationByReasonCode(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getreturnlocationbyreasoncode(v=AX.60)
ms:contentKeyID: 65321705
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetReturnLocationByReasonCode
dev_langs:
- CSharp
- C++
- VB
---

# GetReturnLocationByReasonCode Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetReturnLocationByReasonCode ( _
    transaction As SalesTransaction, _
    line As SalesLine, _
    reasonCodeId As String _
) As ReadOnlyCollection(Of Object)
'Usage
Dim instance As TransactionServiceClient
Dim transaction As SalesTransaction
Dim line As SalesLine
Dim reasonCodeId As String
Dim returnValue As ReadOnlyCollection(Of Object)

returnValue = instance.GetReturnLocationByReasonCode(transaction, _
    line, reasonCodeId)
```

``` csharp
public ReadOnlyCollection<Object> GetReturnLocationByReasonCode(
    SalesTransaction transaction,
    SalesLine line,
    string reasonCodeId
)
```

``` c++
public:
ReadOnlyCollection<Object^>^ GetReturnLocationByReasonCode(
    SalesTransaction^ transaction, 
    SalesLine^ line, 
    String^ reasonCodeId
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - reasonCodeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\>  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

