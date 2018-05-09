---
title: PurgeSalesTransactionsDataRequest.RetentionDays Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: RetentionDays Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeSalesTransactionsDataRequest.RetentionDays
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.purgesalestransactionsdatarequest.retentiondays(v=AX.60)
ms:contentKeyID: 65317519
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeSalesTransactionsDataRequest.RetentionDays
dev_langs:
- CSharp
- C++
- VB
---

# RetentionDays Property

Gets the number of days transaction data will be retained in Channel DB.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RetentionDays As Integer
    Get
    Private Set
'Usage
Dim instance As PurgeSalesTransactionsDataRequest
Dim value As Integer

value = instance.RetentionDays
```

``` csharp
[DataMemberAttribute]
public int RetentionDays { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property int RetentionDays {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[PurgeSalesTransactionsDataRequest Class](purgesalestransactionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

