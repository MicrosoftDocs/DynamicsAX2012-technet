---
title: ResultsPerPage.TargetWebPartId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: TargetWebPartId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ResultsPerPage.TargetWebPartId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.resultsperpage.targetwebpartid(v=AX.60)
ms:contentKeyID: 62206968
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ResultsPerPage.TargetWebPartId
dev_langs:
- CSharp
- C++
- VB
---

# TargetWebPartId Property

Gets or sets the target web part ID.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebBrowsableAttribute(True)> _
<LocalizedCategoryAttribute("ResultsPerPageCustomPropertiesCategoryName")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("ResultsPerPageWebDisplayNameTargetWebPartId")> _
<LocalizedWebDescriptionAttribute("ResultsPerPageWebDescriptionTargetWebPartId")> _
Public Property TargetWebPartId As String
    Get
    Set
'Usage
Dim instance As ResultsPerPage
Dim value As String

value = instance.TargetWebPartId

instance.TargetWebPartId = value
```

``` csharp
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute("ResultsPerPageCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("ResultsPerPageWebDisplayNameTargetWebPartId")]
[LocalizedWebDescriptionAttribute("ResultsPerPageWebDescriptionTargetWebPartId")]
public string TargetWebPartId { get; set; }
```

``` c++
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute(L"ResultsPerPageCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"ResultsPerPageWebDisplayNameTargetWebPartId")]
[LocalizedWebDescriptionAttribute(L"ResultsPerPageWebDescriptionTargetWebPartId")]
public:
property String^ TargetWebPartId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ResultsPerPage Class](resultsperpage-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

