---
title: ServiceResponse Class (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.serviceresponse(v=AX.60)
ms:contentKeyID: 65317387
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# ServiceResponse Class

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class ServiceResponse
'Usage
Dim instance As ServiceResponse
```

``` csharp
[DataContractAttribute]
public class ServiceResponse
```

``` c++
[DataContractAttribute]
public ref class ServiceResponse
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.AddressCollectionResponse](addresscollectionresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.AffiliationLoyaltyTiersResponse](affiliationloyaltytiersresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.BooleanResponse](booleanresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ChannelInfoResponse](channelinforesponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CountryInfoResponse](countryinforesponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CreateSalesOrderResponse](createsalesorderresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerResponse](customerresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse](deliveryoptionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryPreferenceResponse](deliverypreferenceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DemoServiceResponse](demoserviceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.GiftCardResponse](giftcardresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.KitComponentVariantResponse](kitcomponentvariantresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.KitConfigurationResponse](kitconfigurationresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingAvailableQuantityResponse](listingavailablequantityresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingPriceResponse](listingpriceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyCardResponse](loyaltycardresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyCardsResponse](loyaltycardsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyCardTransactionsResponse](loyaltycardtransactionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.NullResponse](nullresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PaymentCardTypesResponse](paymentcardtypesresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.SalesOrderCollectionResponse](salesordercollectionresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.SalesOrderResponse](salesorderresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartCollectionResponse](shoppingcartcollectionresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StateProvinceInfoResponse](stateprovinceinforesponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreLocationResponse](storelocationresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityResponse](storeproductavailabilityresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StringResponse](stringresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.TenderTypesResponse](tendertypesresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListCollectionResponse](wishlistcollectionresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListResponse](wishlistresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

