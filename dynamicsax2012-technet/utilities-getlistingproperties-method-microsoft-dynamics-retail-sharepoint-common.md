---
title: Utilities.GetListingProperties Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetListingProperties Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetListingProperties(System.Boolean,System.Int64,System.String[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.utilities.getlistingproperties(v=AX.60)
ms:contentKeyID: 62207038
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetListingProperties
dev_langs:
- CSharp
- C++
- VB
---

# GetListingProperties Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets Listing's URL for given Listing AX Record ID.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetListingProperties ( _
    isResultMandatory As Boolean, _
    listingRecordId As Long, _
    ParamArray propertyNames As String() _
) As IDictionary(Of String, Object)
'Usage
Dim isResultMandatory As Boolean
Dim listingRecordId As Long
Dim propertyNames As String()
Dim returnValue As IDictionary(Of String, Object)

returnValue = Utilities.GetListingProperties(isResultMandatory, _
    listingRecordId, propertyNames)
```

``` csharp
public static IDictionary<string, Object> GetListingProperties(
    bool isResultMandatory,
    long listingRecordId,
    params string[] propertyNames
)
```

``` c++
public:
static IDictionary<String^, Object^>^ GetListingProperties(
    bool isResultMandatory, 
    long long listingRecordId, 
    ... array<String^>^ propertyNames
)
```

#### Parameters

  - isResultMandatory  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - listingRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - propertyNames  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

#### Return Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  
Properties of given listing as key value pairs. For instance: (Path, /Sites/RetailPublishingPortal/12345/67890).  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>propertyNames</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

