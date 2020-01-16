---
title: GetCurrencyByCodeDataRequest.Columns Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Columns Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCurrencyByCodeDataRequest.Columns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcurrencybycodedatarequest.columns(v=AX.60)
ms:contentKeyID: 65319141
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCurrencyByCodeDataRequest.Columns
dev_langs:
- CSharp
- C++
- VB
---

# Columns Property

Gets the column set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Columns As ColumnSet
    Get
    Private Set
'Usage
Dim instance As GetCurrencyByCodeDataRequest
Dim value As ColumnSet

value = instance.Columns
```

``` csharp
[DataMemberAttribute]
public ColumnSet Columns { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ColumnSet^ Columns {
    ColumnSet^ get ();
    private: void set (ColumnSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  
Returns [ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[GetCurrencyByCodeDataRequest Class](getcurrencybycodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

