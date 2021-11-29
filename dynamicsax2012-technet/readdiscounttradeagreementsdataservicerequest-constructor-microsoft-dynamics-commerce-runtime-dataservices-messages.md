---
title: ReadDiscountTradeAgreementsDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ReadDiscountTradeAgreementsDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadDiscountTradeAgreementsDataServiceRequest.#ctor(System.Collections.Generic.ISet{System.String},System.String,System.DateTimeOffset,System.DateTimeOffset,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.readdiscounttradeagreementsdataservicerequest.readdiscounttradeagreementsdataservicerequest(v=AX.60)
ms:contentKeyID: 65320005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadDiscountTradeAgreementsDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ReadDiscountTradeAgreementsDataServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ReadDiscountTradeAgreementsDataServiceRequest](readdiscounttradeagreementsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemIds As ISet(Of String), _
    customerAccount As String, _
    minActiveDate As DateTimeOffset, _
    maxActiveDate As DateTimeOffset, _
    currencyCode As String _
)
'Usage
Dim itemIds As ISet(Of String)
Dim customerAccount As String
Dim minActiveDate As DateTimeOffset
Dim maxActiveDate As DateTimeOffset
Dim currencyCode As String

Dim instance As New ReadDiscountTradeAgreementsDataServiceRequest(itemIds, _
    customerAccount, minActiveDate, _
    maxActiveDate, currencyCode)
```

``` csharp
public ReadDiscountTradeAgreementsDataServiceRequest(
    ISet<string> itemIds,
    string customerAccount,
    DateTimeOffset minActiveDate,
    DateTimeOffset maxActiveDate,
    string currencyCode
)
```

``` c++
public:
ReadDiscountTradeAgreementsDataServiceRequest(
    ISet<String^>^ itemIds, 
    String^ customerAccount, 
    DateTimeOffset minActiveDate, 
    DateTimeOffset maxActiveDate, 
    String^ currencyCode
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - customerAccount  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - minActiveDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - maxActiveDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ReadDiscountTradeAgreementsDataServiceRequest Class](readdiscounttradeagreementsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

