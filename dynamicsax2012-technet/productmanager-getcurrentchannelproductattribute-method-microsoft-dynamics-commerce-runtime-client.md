---
title: ProductManager.GetCurrentChannelProductAttribute Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCurrentChannelProductAttribute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetCurrentChannelProductAttribute(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.productmanager.getcurrentchannelproductattribute(v=AX.60)
ms:contentKeyID: 49853585
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetCurrentChannelProductAttribute
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrentChannelProductAttribute Method

Gets complete schema of product attribute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCurrentChannelProductAttribute ( _
    attributeId As Long _
) As AttributeProduct
'Usage
Dim instance As ProductManager
Dim attributeId As Long
Dim returnValue As AttributeProduct

returnValue = instance.GetCurrentChannelProductAttribute(attributeId)
```

``` csharp
public AttributeProduct GetCurrentChannelProductAttribute(
    long attributeId
)
```

``` c++
public:
AttributeProduct^ GetCurrentChannelProductAttribute(
    long long attributeId
)
```

#### Parameters

  - attributeId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The complete schema of product attribute.  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

