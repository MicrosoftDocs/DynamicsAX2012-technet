---
title: RichMediaHelper.PopulateProductMediaInformation Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PopulateProductMediaInformation Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.RichMediaHelper.PopulateProductMediaInformation(Microsoft.Dynamics.Commerce.Runtime.DataModel.Product,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.richmediahelper.populateproductmediainformation(v=AX.60)
ms:contentKeyID: 65319554
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.RichMediaHelper.PopulateProductMediaInformation
dev_langs:
- CSharp
- C++
- VB
---

# PopulateProductMediaInformation Method

Populates the product media information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function PopulateProductMediaInformation ( _
    product As Product, _
    propertyTextValue As String, _
    languageId As String _
) As RichMediaLocations
'Usage
Dim product As Product
Dim propertyTextValue As String
Dim languageId As String
Dim returnValue As RichMediaLocations

returnValue = RichMediaHelper.PopulateProductMediaInformation(product, _
    propertyTextValue, languageId)
```

``` csharp
public static RichMediaLocations PopulateProductMediaInformation(
    Product product,
    string propertyTextValue,
    string languageId
)
```

``` c++
public:
static RichMediaLocations^ PopulateProductMediaInformation(
    Product^ product, 
    String^ propertyTextValue, 
    String^ languageId
)
```

#### Parameters

  - product  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - propertyTextValue  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - languageId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations](richmedialocations-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
RichMediaLocations instance.  

## See Also

#### Reference

[RichMediaHelper Class](richmediahelper-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

