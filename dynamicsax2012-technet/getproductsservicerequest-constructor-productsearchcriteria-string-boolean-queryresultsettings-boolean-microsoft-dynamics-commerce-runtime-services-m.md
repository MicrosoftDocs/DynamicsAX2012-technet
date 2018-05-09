---
title: GetProductsServiceRequest Constructor (ProductSearchCriteria, String, Boolean, QueryResultSettings, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetProductsServiceRequest Constructor (ProductSearchCriteria, String, Boolean, QueryResultSettings, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductsServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria,System.String,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getproductsservicerequest.getproductsservicerequest(v=AX.60)
ms:contentKeyID: 65323219
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductsServiceRequest Constructor (ProductSearchCriteria, String, Boolean, QueryResultSettings, Boolean)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    criteria As ProductSearchCriteria, _
    languageId As String, _
    fetchProductsAvailableInFuture As Boolean, _
    queryResultSettings As QueryResultSettings, _
    retrieveDefaultImage As Boolean _
)
'Usage
Dim criteria As ProductSearchCriteria
Dim languageId As String
Dim fetchProductsAvailableInFuture As Boolean
Dim queryResultSettings As QueryResultSettings
Dim retrieveDefaultImage As Boolean

Dim instance As New GetProductsServiceRequest(criteria, _
    languageId, fetchProductsAvailableInFuture, _
    queryResultSettings, retrieveDefaultImage)
```

``` csharp
public GetProductsServiceRequest(
    ProductSearchCriteria criteria,
    string languageId,
    bool fetchProductsAvailableInFuture,
    QueryResultSettings queryResultSettings,
    bool retrieveDefaultImage
)
```

``` c++
public:
GetProductsServiceRequest(
    ProductSearchCriteria^ criteria, 
    String^ languageId, 
    bool fetchProductsAvailableInFuture, 
    QueryResultSettings^ queryResultSettings, 
    bool retrieveDefaultImage
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - languageId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - fetchProductsAvailableInFuture  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - retrieveDefaultImage  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetProductsServiceRequest Class](getproductsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetProductsServiceRequest Overload](getproductsservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

