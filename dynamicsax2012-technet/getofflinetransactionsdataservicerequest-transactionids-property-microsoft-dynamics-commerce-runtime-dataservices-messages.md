---
title: GetOfflineTransactionsDataServiceRequest.TransactionIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TransactionIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineTransactionsDataServiceRequest.TransactionIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getofflinetransactionsdataservicerequest.transactionids(v=AX.60)
ms:contentKeyID: 65318515
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineTransactionsDataServiceRequest.TransactionIds
dev_langs:
- CSharp
- C++
- VB
---

# TransactionIds Property

Gets the collection of transaction IDs based on which to read transaction related data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetOfflineTransactionsDataServiceRequest
Dim value As IEnumerable(Of String)

value = instance.TransactionIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> TransactionIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ TransactionIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetOfflineTransactionsDataServiceRequest Class](getofflinetransactionsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

