---
title: CheckoutServiceBase.CreateOrder Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CreateOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CheckoutServiceBase.CreateOrder(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TenderDataLine},System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.checkoutservicebase.createorder(v=AX.60)
ms:contentKeyID: 65316495
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CheckoutServiceBase.CreateOrder
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrder Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function CreateOrder ( _
    tenderDataLine As IEnumerable(Of TenderDataLine), _
    emailAddress As String _
) As CreateSalesOrderResponse
'Usage
Dim instance As CheckoutServiceBase
Dim tenderDataLine As IEnumerable(Of TenderDataLine)
Dim emailAddress As String
Dim returnValue As CreateSalesOrderResponse

returnValue = instance.CreateOrder(tenderDataLine, _
    emailAddress)
```

``` csharp
public virtual CreateSalesOrderResponse CreateOrder(
    IEnumerable<TenderDataLine> tenderDataLine,
    string emailAddress
)
```

``` c++
public:
virtual CreateSalesOrderResponse^ CreateOrder(
    IEnumerable<TenderDataLine^>^ tenderDataLine, 
    String^ emailAddress
)
```

#### Parameters

  - tenderDataLine  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[TenderDataLine](tenderdataline-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

<!-- end list -->

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CreateSalesOrderResponse](createsalesorderresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[ICheckoutService.CreateOrder(IEnumerable\<TenderDataLine\>, String)](icheckoutservice-createorder-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[CheckoutServiceBase Class](checkoutservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

