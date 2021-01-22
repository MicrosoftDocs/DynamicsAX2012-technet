---
title: CustomClaimsProvider.FillSearch Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: FillSearch Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillSearch(System.Uri,System.String[],System.String,System.String,System.Int32,Microsoft.SharePoint.WebControls.SPProviderHierarchyTree)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.fillsearch(v=AX.60)
ms:contentKeyID: 62204488
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillSearch
dev_langs:
- CSharp
- C++
- VB
---

# FillSearch Method

Fills the search.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub FillSearch ( _
    context As Uri, _
    entityTypes As String(), _
    searchPattern As String, _
    hierarchyNodeID As String, _
    maxCount As Integer, _
    searchTree As SPProviderHierarchyTree _
)
'Usage
Dim context As Uri
Dim entityTypes As String()
Dim searchPattern As String
Dim hierarchyNodeID As String
Dim maxCount As Integer
Dim searchTree As SPProviderHierarchyTree

Me.FillSearch(context, entityTypes, _
    searchPattern, hierarchyNodeID, _
    maxCount, searchTree)
```

``` csharp
protected override void FillSearch(
    Uri context,
    string[] entityTypes,
    string searchPattern,
    string hierarchyNodeID,
    int maxCount,
    SPProviderHierarchyTree searchTree
)
```

``` c++
protected:
virtual void FillSearch(
    Uri^ context, 
    array<String^>^ entityTypes, 
    String^ searchPattern, 
    String^ hierarchyNodeID, 
    int maxCount, 
    SPProviderHierarchyTree^ searchTree
) override
```

#### Parameters

  - context  
    Type: [System.Uri](https://technet.microsoft.com/library/txt7706a\(v=ax.60\))  

<!-- end list -->

  - entityTypes  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

<!-- end list -->

  - searchPattern  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - hierarchyNodeID  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - maxCount  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - searchTree  
    Type: SPProviderHierarchyTree  

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
<td><a href="https://technet.microsoft.com/library/6byb74h9(v=ax.60)">NotImplementedException</a></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[CustomClaimsProvider Class](customclaimsprovider-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

