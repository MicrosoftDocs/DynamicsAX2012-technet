---
title: RichMediaHelper.PopulateCatalogMediaInformation Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PopulateCatalogMediaInformation Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.RichMediaHelper.PopulateCatalogMediaInformation(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.richmediahelper.populatecatalogmediainformation(v=AX.60)
ms:contentKeyID: 65322567
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.RichMediaHelper.PopulateCatalogMediaInformation
dev_langs:
- CSharp
- C++
- VB
---

# PopulateCatalogMediaInformation Method

Populates the catalog media information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function PopulateCatalogMediaInformation ( _
    catalog As ProductCatalog, _
    languageId As String, _
    channelName As String, _
    defaultValue As String _
) As RichMediaLocations
'Usage
Dim catalog As ProductCatalog
Dim languageId As String
Dim channelName As String
Dim defaultValue As String
Dim returnValue As RichMediaLocations

returnValue = RichMediaHelper.PopulateCatalogMediaInformation(catalog, _
    languageId, channelName, defaultValue)
```

``` csharp
public static RichMediaLocations PopulateCatalogMediaInformation(
    ProductCatalog catalog,
    string languageId,
    string channelName,
    string defaultValue
)
```

``` c++
public:
static RichMediaLocations^ PopulateCatalogMediaInformation(
    ProductCatalog^ catalog, 
    String^ languageId, 
    String^ channelName, 
    String^ defaultValue
)
```

#### Parameters

  - catalog  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - channelName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - defaultValue  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations](richmedialocations-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
RichMediaLocations object.  

## See Also

#### Reference

[RichMediaHelper Class](richmediahelper-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

