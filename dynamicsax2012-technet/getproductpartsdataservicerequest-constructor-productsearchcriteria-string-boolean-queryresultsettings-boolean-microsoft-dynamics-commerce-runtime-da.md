---
title: GetProductPartsDataServiceRequest Constructor (ProductSearchCriteria, String, Boolean, QueryResultSettings, Boolean) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetProductPartsDataServiceRequest Constructor (ProductSearchCriteria, String, Boolean, QueryResultSettings, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria,System.String,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataservicerequest.getproductpartsdataservicerequest(v=AX.60)
ms:contentKeyID: 65317111
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductPartsDataServiceRequest Constructor (ProductSearchCriteria, String, Boolean, QueryResultSettings, Boolean)

Initializes a new instance of the [GetProductPartsDataServiceRequest](getproductpartsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    criteria As ProductSearchCriteria, _
    languageId As String, _
    fetchProductsOnFutureDate As Boolean, _
    queryResultSettings As QueryResultSettings, _
    isOnline As Boolean _
)
'Usage
Dim criteria As ProductSearchCriteria
Dim languageId As String
Dim fetchProductsOnFutureDate As Boolean
Dim queryResultSettings As QueryResultSettings
Dim isOnline As Boolean

Dim instance As New GetProductPartsDataServiceRequest(criteria, _
    languageId, fetchProductsOnFutureDate, _
    queryResultSettings, isOnline)
```

``` csharp
public GetProductPartsDataServiceRequest(
    ProductSearchCriteria criteria,
    string languageId,
    bool fetchProductsOnFutureDate,
    QueryResultSettings queryResultSettings,
    bool isOnline
)
```

``` c++
public:
GetProductPartsDataServiceRequest(
    ProductSearchCriteria^ criteria, 
    String^ languageId, 
    bool fetchProductsOnFutureDate, 
    QueryResultSettings^ queryResultSettings, 
    bool isOnline
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - fetchProductsOnFutureDate  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - isOnline  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetProductPartsDataServiceRequest Class](getproductpartsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetProductPartsDataServiceRequest Overload](getproductpartsdataservicerequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

