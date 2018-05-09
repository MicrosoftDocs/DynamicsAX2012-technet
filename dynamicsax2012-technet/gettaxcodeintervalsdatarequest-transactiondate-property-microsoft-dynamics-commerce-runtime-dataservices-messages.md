---
title: GetTaxCodeIntervalsDataRequest.TransactionDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TransactionDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalsDataRequest.TransactionDate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettaxcodeintervalsdatarequest.transactiondate(v=AX.60)
ms:contentKeyID: 65323110
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalsDataRequest.TransactionDate
dev_langs:
- CSharp
- C++
- VB
---

# TransactionDate Property

Gets the transaction date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionDate As DateTimeOffset
    Get
    Private Set
'Usage
Dim instance As GetTaxCodeIntervalsDataRequest
Dim value As DateTimeOffset

value = instance.TransactionDate
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset TransactionDate { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset TransactionDate {
    DateTimeOffset get ();
    private: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[GetTaxCodeIntervalsDataRequest Class](gettaxcodeintervalsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

