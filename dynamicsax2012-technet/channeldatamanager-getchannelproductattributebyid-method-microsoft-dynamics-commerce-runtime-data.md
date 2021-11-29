---
title: ChannelDataManager.GetChannelProductAttributeById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelProductAttributeById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetChannelProductAttributeById(System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getchannelproductattributebyid(v=AX.60)
ms:contentKeyID: 49839556
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetChannelProductAttributeById
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelProductAttributeById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product attribute of a given attribute identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelProductAttributeById ( _
    attributeId As Long, _
    columns As ColumnSet _
) As AttributeProduct
'Usage
Dim instance As ChannelDataManager
Dim attributeId As Long
Dim columns As ColumnSet
Dim returnValue As AttributeProduct

returnValue = instance.GetChannelProductAttributeById(attributeId, _
    columns)
```

``` csharp
public AttributeProduct GetChannelProductAttributeById(
    long attributeId,
    ColumnSet columns
)
```

``` c++
public:
virtual AttributeProduct^ GetChannelProductAttributeById(
    long long attributeId, 
    ColumnSet^ columns
) sealed
```

#### Parameters

  - attributeId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The product attribute.  

#### Implements

[IChannelDataManager.GetChannelProductAttributeById(Int64, ColumnSet)](ichanneldatamanager-getchannelproductattributebyid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

