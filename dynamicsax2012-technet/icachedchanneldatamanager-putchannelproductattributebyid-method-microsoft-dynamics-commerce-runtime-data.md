---
title: ICachedChannelDataManager.PutChannelProductAttributeById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChannelProductAttributeById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelProductAttributeById(System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putchannelproductattributebyid(v=AX.60)
ms:contentKeyID: 62207806
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelProductAttributeById
dev_langs:
- CSharp
- C++
- VB
---

# PutChannelProductAttributeById Method

Caches the product attribute of a given attribute identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChannelProductAttributeById ( _
    attributeId As Long, _
    columns As ColumnSet, _
    result As AttributeProduct _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim attributeId As Long
Dim columns As ColumnSet
Dim result As AttributeProduct

instance.PutChannelProductAttributeById(attributeId, _
    columns, result)
```

``` csharp
void PutChannelProductAttributeById(
    long attributeId,
    ColumnSet columns,
    AttributeProduct result
)
```

``` c++
void PutChannelProductAttributeById(
    long long attributeId, 
    ColumnSet^ columns, 
    AttributeProduct^ result
)
```

#### Parameters

  - attributeId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

