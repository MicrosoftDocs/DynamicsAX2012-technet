---
title: ShoppingCartController.GetKitConfigurationInformation Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetKitConfigurationInformation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.GetKitConfigurationInformation(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.KitLine},System.String,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.shoppingcartcontroller.getkitconfigurationinformation(v=AX.60)
ms:contentKeyID: 65316540
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.GetKitConfigurationInformation
dev_langs:
- CSharp
- C++
- VB
---

# GetKitConfigurationInformation Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetKitConfigurationInformation ( _
    kitProductMasterIdentifier As Long, _
    catalogId As Long, _
    kitLines As IEnumerable(Of KitLine), _
    customerId As String, _
    searchEngine As ISearchEngine _
) As KitConfigurationInformation
'Usage
Dim instance As ShoppingCartController
Dim kitProductMasterIdentifier As Long
Dim catalogId As Long
Dim kitLines As IEnumerable(Of KitLine)
Dim customerId As String
Dim searchEngine As ISearchEngine
Dim returnValue As KitConfigurationInformation

returnValue = instance.GetKitConfigurationInformation(kitProductMasterIdentifier, _
    catalogId, kitLines, customerId, _
    searchEngine)
```

``` csharp
public virtual KitConfigurationInformation GetKitConfigurationInformation(
    long kitProductMasterIdentifier,
    long catalogId,
    IEnumerable<KitLine> kitLines,
    string customerId,
    ISearchEngine searchEngine
)
```

``` c++
public:
virtual KitConfigurationInformation^ GetKitConfigurationInformation(
    long long kitProductMasterIdentifier, 
    long long catalogId, 
    IEnumerable<KitLine^>^ kitLines, 
    String^ customerId, 
    ISearchEngine^ searchEngine
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

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.KitConfigurationInformation](kitconfigurationinformation-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[ShoppingCartController Class](shoppingcartcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

