---
title: StoreOperationsManager.GetXZReport Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetXZReport Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.GetXZReport(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType,System.String,System.Nullable{System.Int64},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.getxzreport(v=AX.60)
ms:contentKeyID: 65320364
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.GetXZReport
dev_langs:
- CSharp
- C++
- VB
---

# GetXZReport Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetXZReport ( _
    receiptType As ReceiptType, _
    terminalId As String, _
    shiftId As Nullable(Of Long), _
    transactionId As String _
) As Receipt
'Usage
Dim instance As StoreOperationsManager
Dim receiptType As ReceiptType
Dim terminalId As String
Dim shiftId As Nullable(Of Long)
Dim transactionId As String
Dim returnValue As Receipt

returnValue = instance.GetXZReport(receiptType, _
    terminalId, shiftId, transactionId)
```

``` csharp
public Receipt GetXZReport(
    ReceiptType receiptType,
    string terminalId,
    Nullable<long> shiftId,
    string transactionId
)
```

``` c++
public:
Receipt^ GetXZReport(
    ReceiptType receiptType, 
    String^ terminalId, 
    Nullable<long long> shiftId, 
    String^ transactionId
)
```

#### Parameters

  - receiptType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt](receipt-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

