---
title: GetOfflineTransactionIdsDataServiceRequest.NumberOfTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: NumberOfTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineTransactionIdsDataServiceRequest.NumberOfTransactions
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getofflinetransactionidsdataservicerequest.numberoftransactions(v=AX.60)
ms:contentKeyID: 65320969
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineTransactionIdsDataServiceRequest.NumberOfTransactions
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfTransactions Property

Gets the number of transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberOfTransactions As Integer
    Get
    Private Set
'Usage
Dim instance As GetOfflineTransactionIdsDataServiceRequest
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

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[GetOfflineTransactionIdsDataServiceRequest Class](getofflinetransactionidsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

