---
title: IShoppingCartService.GetKitComponentVariants Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetKitComponentVariants Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IShoppingCartService.GetKitComponentVariants(System.Int64,System.Int64,System.Int64,System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.ishoppingcartservice.getkitcomponentvariants(v=AX.60)
ms:contentKeyID: 65315941
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IShoppingCartService.GetKitComponentVariants
dev_langs:
- CSharp
- C++
- VB
---

# GetKitComponentVariants Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetKitComponentVariants ( _
    kitComponentProductId As Long, _
    kitComponentParentId As Long, _
    parentKitId As Long, _
    kitComponentLineId As Long, _
    catalogId As Long _
) As KitComponentVariantResponse
'Usage
Dim instance As IShoppingCartService
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
[OperationContractAttribute]
KitComponentVariantResponse GetKitComponentVariants(
    long kitComponentProductId,
    long kitComponentParentId,
    long parentKitId,
    long kitComponentLineId,
    long catalogId
)
```

``` c++
[OperationContractAttribute]
KitComponentVariantResponse^ GetKitComponentVariants(
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

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

