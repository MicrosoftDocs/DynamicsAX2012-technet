---
title: GetLatestNumberSequenceDataServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetLatestNumberSequenceDataServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLatestNumberSequenceDataServiceResponse.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getlatestnumbersequencedataserviceresponse.getlatestnumbersequencedataserviceresponse(v=AX.60)
ms:contentKeyID: 65321679
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLatestNumberSequenceDataServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLatestNumberSequenceDataServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetLatestNumberSequenceDataServiceResponse](getlatestnumbersequencedataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    numberSequenceForShift As Shift, _
    numberSequenceForTransaction As SalesTransaction, _
    numberSequenceForReceipts As IEnumerable(Of SalesTransaction) _
)
'Usage
Dim numberSequenceForShift As Shift
Dim numberSequenceForTransaction As SalesTransaction
Dim numberSequenceForReceipts As IEnumerable(Of SalesTransaction)

Dim instance As New GetLatestNumberSequenceDataServiceResponse(numberSequenceForShift, _
    numberSequenceForTransaction, numberSequenceForReceipts)
```

``` csharp
public GetLatestNumberSequenceDataServiceResponse(
    Shift numberSequenceForShift,
    SalesTransaction numberSequenceForTransaction,
    IEnumerable<SalesTransaction> numberSequenceForReceipts
)
```

``` c++
public:
GetLatestNumberSequenceDataServiceResponse(
    Shift^ numberSequenceForShift, 
    SalesTransaction^ numberSequenceForTransaction, 
    IEnumerable<SalesTransaction^>^ numberSequenceForReceipts
)
```

#### Parameters

  - numberSequenceForShift  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - numberSequenceForTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - numberSequenceForReceipts  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetLatestNumberSequenceDataServiceResponse Class](getlatestnumbersequencedataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

