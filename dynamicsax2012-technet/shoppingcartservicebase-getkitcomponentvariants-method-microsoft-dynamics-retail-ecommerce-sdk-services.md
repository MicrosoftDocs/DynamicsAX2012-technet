---
title: ShoppingCartServiceBase.GetKitComponentVariants Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetKitComponentVariants Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.GetKitComponentVariants(System.Int64,System.Int64,System.Int64,System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.shoppingcartservicebase.getkitcomponentvariants(v=AX.60)
ms:contentKeyID: 65317856
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.GetKitComponentVariants
dev_langs:
- CSharp
- C++
- VB
---

# GetKitComponentVariants Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetKitComponentVariants ( _
    kitComponentProductId As Long, _
    kitComponentParentId As Long, _
    parentKitId As Long, _
    kitComponentLineId As Long, _
    catalogId As Long _
) As KitComponentVariantResponse
'Usage
Dim instance As ShoppingCartServiceBase
Dim kitComponentProductId As Long
Dim kitComponentParentId As Long
Dim parentKitId As Long
Dim kitComponentLineId As Long
Dim catalogId As Long
Dim returnValue As KitComponentVariantResponse

returnValue = instance.GetKitComponentVariants(kitComponentProductId, _
    kitComponentParentId, parentKitId, _
    kitComponentLineId, catalogId)
```

``` csharp
public virtual KitComponentVariantResponse GetKitComponentVariants(
    long kitComponentProductId,
    long kitComponentParentId,
    long parentKitId,
    long kitComponentLineId,
    long catalogId
)
```

``` c++
public:
virtual KitComponentVariantResponse^ GetKitComponentVariants(
    long long kitComponentProductId, 
    long long kitComponentParentId, 
    long long parentKitId, 
    long long kitComponentLineId, 
    long long catalogId
)
```

#### Parameters

  - kitComponentProductId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitComponentParentId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - parentKitId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitComponentLineId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.KitComponentVariantResponse](kitcomponentvariantresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IShoppingCartService.GetKitComponentVariants(Int64, Int64, Int64, Int64, Int64)](ishoppingcartservice-getkitcomponentvariants-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ShoppingCartServiceBase Class](shoppingcartservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

