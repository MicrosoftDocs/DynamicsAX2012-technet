---
title: ReasonCodeRequiredNotification.TransactionRequiredReasonCodeIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionRequiredReasonCodeIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequiredNotification.TransactionRequiredReasonCodeIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncoderequirednotification.transactionrequiredreasoncodeids(v=AX.60)
ms:contentKeyID: 65320642
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequiredNotification.TransactionRequiredReasonCodeIds
dev_langs:
- CSharp
- C++
- VB
---

# TransactionRequiredReasonCodeIds Property

Gets the identifiers of reason codes required at transaction level.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionRequiredReasonCodeIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As ReasonCodeRequiredNotification
Dim value As IEnumerable(Of String)

value = instance.TransactionRequiredReasonCodeIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> TransactionRequiredReasonCodeIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ TransactionRequiredReasonCodeIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ReasonCodeRequiredNotification Class](reasoncoderequirednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

