---
title: ShoppingCartServiceBase.GetKitConfigurationInformation Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetKitConfigurationInformation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.GetKitConfigurationInformation(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.KitLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.shoppingcartservicebase.getkitconfigurationinformation(v=AX.60)
ms:contentKeyID: 65317278
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.GetKitConfigurationInformation
dev_langs:
- CSharp
- C++
- VB
---

# GetKitConfigurationInformation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetKitConfigurationInformation ( _
    kitProductMasterIdentifier As Long, _
    catalogId As Long, _
    kitLines As IEnumerable(Of KitLine) _
) As KitConfigurationResponse
'Usage
Dim instance As ShoppingCartServiceBase
Dim kitProductMasterIdentifier As Long
Dim catalogId As Long
Dim kitLines As IEnumerable(Of KitLine)
Dim returnValue As KitConfigurationResponse

returnValue = instance.GetKitConfigurationInformation(kitProductMasterIdentifier, _
    catalogId, kitLines)
```

``` csharp
public virtual KitConfigurationResponse GetKitConfigurationInformation(
    long kitProductMasterIdentifier,
    long catalogId,
    IEnumerable<KitLine> kitLines
)
```

``` c++
public:
virtual KitConfigurationResponse^ GetKitConfigurationInformation(
    long long kitProductMasterIdentifier, 
    long long catalogId, 
    IEnumerable<KitLine^>^ kitLines
)
```

#### Parameters

  - kitProductMasterIdentifier  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[KitLine](kitline-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.KitConfigurationResponse](kitconfigurationresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IShoppingCartService.GetKitConfigurationInformation(Int64, Int64, IEnumerable\<KitLine\>)](ishoppingcartservice-getkitconfigurationinformation-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ShoppingCartServiceBase Class](shoppingcartservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

