---
title: GetStoreProductAvailabilityRequest Constructor (QueryResultSettings, String, String, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStoreProductAvailabilityRequest Constructor (QueryResultSettings, String, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getstoreproductavailabilityrequest.getstoreproductavailabilityrequest(v=AX.60)
ms:contentKeyID: 65317732
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoreProductAvailabilityRequest Constructor (QueryResultSettings, String, String, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    itemId As String, _
    variantId As String, _
    barcode As String _
)
'Usage
Dim settings As QueryResultSettings
Dim itemId As String
Dim variantId As String
Dim barcode As String

Dim instance As New GetStoreProductAvailabilityRequest(settings, _
    itemId, variantId, barcode)
```

``` csharp
public GetStoreProductAvailabilityRequest(
    QueryResultSettings settings,
    string itemId,
    string variantId,
    string barcode
)
```

``` c++
public:
GetStoreProductAvailabilityRequest(
    QueryResultSettings^ settings, 
    String^ itemId, 
    String^ variantId, 
    String^ barcode
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - variantId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - barcode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetStoreProductAvailabilityRequest Class](getstoreproductavailabilityrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStoreProductAvailabilityRequest Overload](getstoreproductavailabilityrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

