---
title: GetTaxCodeIntervalsIndiaDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetTaxCodeIntervalsIndiaDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalsIndiaDataRequest.#ctor(System.String,System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettaxcodeintervalsindiadatarequest.gettaxcodeintervalsindiadatarequest(v=AX.60)
ms:contentKeyID: 65320967
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalsIndiaDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxCodeIntervalsIndiaDataRequest Constructor

Initializes a new instance of the [GetTaxCodeIntervalsIndiaDataRequest](gettaxcodeintervalsindiadatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesTaxGroupId As String, _
    itemTaxGroupId As String, _
    transactionDate As DateTimeOffset _
)
'Usage
Dim salesTaxGroupId As String
Dim itemTaxGroupId As String
Dim transactionDate As DateTimeOffset

Dim instance As New GetTaxCodeIntervalsIndiaDataRequest(salesTaxGroupId, _
    itemTaxGroupId, transactionDate)
```

``` csharp
public GetTaxCodeIntervalsIndiaDataRequest(
    string salesTaxGroupId,
    string itemTaxGroupId,
    DateTimeOffset transactionDate
)
```

``` c++
public:
GetTaxCodeIntervalsIndiaDataRequest(
    String^ salesTaxGroupId, 
    String^ itemTaxGroupId, 
    DateTimeOffset transactionDate
)
```

#### Parameters

  - salesTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[GetTaxCodeIntervalsIndiaDataRequest Class](gettaxcodeintervalsindiadatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

