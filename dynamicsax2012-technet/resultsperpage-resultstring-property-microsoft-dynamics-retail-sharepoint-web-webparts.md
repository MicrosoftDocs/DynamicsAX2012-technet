---
title: ResultsPerPage.ResultString Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ResultString Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ResultsPerPage.ResultString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.resultsperpage.resultstring(v=AX.60)
ms:contentKeyID: 62205649
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ResultsPerPage.ResultString
dev_langs:
- CSharp
- C++
- VB
---

# ResultString Property

Gets or sets the results number to choose from.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebBrowsableAttribute(True)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedCategoryAttribute("ResultsPerPageCustomPropertiesCategoryName")> _
<LocalizedWebDescriptionAttribute("ResultsPerPageWebDescriptionResultString")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("ResultsPerPageWebDisplayNameResultString")> _
Public Property ResultString As String
    Get
    Set
'Usage
Dim instance As ResultsPerPage
Dim value As String

value = instance.ResultString

instance.ResultString = value
```

``` csharp
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedCategoryAttribute("ResultsPerPageCustomPropertiesCategoryName")]
[LocalizedWebDescriptionAttribute("ResultsPerPageWebDescriptionResultString")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("ResultsPerPageWebDisplayNameResultString")]
public string ResultString { get; set; }
```

``` c++
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedCategoryAttribute(L"ResultsPerPageCustomPropertiesCategoryName")]
[LocalizedWebDescriptionAttribute(L"ResultsPerPageWebDescriptionResultString")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"ResultsPerPageWebDisplayNameResultString")]
public:
property String^ ResultString {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ResultsPerPage Class](resultsperpage-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

