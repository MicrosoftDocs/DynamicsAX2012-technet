---
title: ChannelDatabaseAccessor.GetChannelProductAttributeByKey Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelProductAttributeByKey Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetChannelProductAttributeByKey(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getchannelproductattributebykey(v=AX.60)
ms:contentKeyID: 62209475
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetChannelProductAttributeByKey
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelProductAttributeByKey Method

Gets the product attribute of a given attribute identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelProductAttributeByKey ( _
    attributeKey As String, _
    columns As ColumnSet _
) As AttributeProduct
'Usage
Dim instance As ChannelDatabaseAccessor
Dim attributeKey As String
Dim columns As ColumnSet
Dim returnValue As AttributeProduct

returnValue = instance.GetChannelProductAttributeByKey(attributeKey, _
    columns)
```

``` csharp
public AttributeProduct GetChannelProductAttributeByKey(
    string attributeKey,
    ColumnSet columns
)
```

``` c++
public:
AttributeProduct^ GetChannelProductAttributeByKey(
    String^ attributeKey, 
    ColumnSet^ columns
)
```

#### Parameters

  - attributeKey  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The product attribute.  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

