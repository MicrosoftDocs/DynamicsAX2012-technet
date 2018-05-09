---
title: RichMediaHelper.PopulateVariantMediaInformation Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PopulateVariantMediaInformation Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.RichMediaHelper.PopulateVariantMediaInformation(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.richmediahelper.populatevariantmediainformation(v=AX.60)
ms:contentKeyID: 65322983
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.RichMediaHelper.PopulateVariantMediaInformation
dev_langs:
- CSharp
- C++
- VB
---

# PopulateVariantMediaInformation Method

Populates the variant media information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function PopulateVariantMediaInformation ( _
    variant As ProductVariant, _
    propertyTextValue As String, _
    languageId As String _
) As RichMediaLocations
'Usage
Dim variant As ProductVariant
Dim propertyTextValue As String
Dim languageId As String
Dim returnValue As RichMediaLocations

returnValue = RichMediaHelper.PopulateVariantMediaInformation(variant, _
    propertyTextValue, languageId)
```

``` csharp
public static RichMediaLocations PopulateVariantMediaInformation(
    ProductVariant variant,
    string propertyTextValue,
    string languageId
)
```

``` c++
public:
static RichMediaLocations^ PopulateVariantMediaInformation(
    ProductVariant^ variant, 
    String^ propertyTextValue, 
    String^ languageId
)
```

#### Parameters

  - variant  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

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

