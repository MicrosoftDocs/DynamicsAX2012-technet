---
title: GetOfflineTransactionIdsRequest.NumberOfTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NumberOfTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionIdsRequest.NumberOfTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getofflinetransactionidsrequest.numberoftransactions(v=AX.60)
ms:contentKeyID: 65320730
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionIdsRequest.NumberOfTransactions
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfTransactions Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberOfTransactions As Integer
    Get
    Private Set
'Usage
Dim instance As GetOfflineTransactionIdsRequest
Dim value As Integer

value = instance.NumberOfTransactions
```

``` csharp
[DataMemberAttribute]
public int NumberOfTransactions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property int NumberOfTransactions {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetOfflineTransactionIdsRequest Class](getofflinetransactionidsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

