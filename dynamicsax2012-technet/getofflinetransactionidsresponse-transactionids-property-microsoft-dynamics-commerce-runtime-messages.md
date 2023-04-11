---
title: GetOfflineTransactionIdsResponse.TransactionIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TransactionIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionIdsResponse.TransactionIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getofflinetransactionidsresponse.transactionids(v=AX.60)
ms:contentKeyID: 65315460
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionIdsResponse.TransactionIds
dev_langs:
- CSharp
- C++
- VB
---

# TransactionIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionIds As ReadOnlyCollection(Of String)
    Get
    Private Set
'Usage
Dim instance As GetOfflineTransactionIdsResponse
Dim value As ReadOnlyCollection(Of String)

value = instance.TransactionIds
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<string> TransactionIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<String^>^ TransactionIds {
    ReadOnlyCollection<String^>^ get ();
    private: void set (ReadOnlyCollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[GetOfflineTransactionIdsResponse Class](getofflinetransactionidsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

