---
title: FindTradeAgreementsDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: FindTradeAgreementsDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.FindTradeAgreementsDataServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType,Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode,System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.Decimal,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.findtradeagreementsdataservicerequest.findtradeagreementsdataservicerequest(v=AX.60)
ms:contentKeyID: 65321241
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.FindTradeAgreementsDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# FindTradeAgreementsDataServiceRequest Constructor

Initializes a new instance of the [FindTradeAgreementsDataServiceRequest](findtradeagreementsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    agreementType As PriceDiscountType, _
    itemCode As PriceDiscountItemCode, _
    itemRelation As String, _
    accountCode As PriceDiscountAccountCode, _
    accountRelations As IEnumerable(Of String), _
    unitId As String, _
    currencyCode As String, _
    quantity As Decimal, _
    variant As ProductVariant, _
    activeDate As DateTimeOffset _
)
'Usage
Dim agreementType As PriceDiscountType
Dim itemCode As PriceDiscountItemCode
Dim itemRelation As String
Dim accountCode As PriceDiscountAccountCode
Dim accountRelations As IEnumerable(Of String)
Dim unitId As String
Dim currencyCode As String
Dim quantity As Decimal
Dim variant As ProductVariant
Dim activeDate As DateTimeOffset

Dim instance As New FindTradeAgreementsDataServiceRequest(agreementType, _
    itemCode, itemRelation, accountCode, _
    accountRelations, unitId, currencyCode, _
    quantity, variant, activeDate)
```

``` csharp
public FindTradeAgreementsDataServiceRequest(
    PriceDiscountType agreementType,
    PriceDiscountItemCode itemCode,
    string itemRelation,
    PriceDiscountAccountCode accountCode,
    IEnumerable<string> accountRelations,
    string unitId,
    string currencyCode,
    decimal quantity,
    ProductVariant variant,
    DateTimeOffset activeDate
)
```

``` c++
public:
FindTradeAgreementsDataServiceRequest(
    PriceDiscountType agreementType, 
    PriceDiscountItemCode itemCode, 
    String^ itemRelation, 
    PriceDiscountAccountCode accountCode, 
    IEnumerable<String^>^ accountRelations, 
    String^ unitId, 
    String^ currencyCode, 
    Decimal quantity, 
    ProductVariant^ variant, 
    DateTimeOffset activeDate
)
```

#### Parameters

  - agreementType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType](pricediscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemCode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode](pricediscountitemcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemRelation  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - accountCode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode](pricediscountaccountcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - accountRelations  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - unitId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - variant  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[FindTradeAgreementsDataServiceRequest Class](findtradeagreementsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

