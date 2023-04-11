---
title: CustomClaimsProvider.FillHierarchy Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: FillHierarchy Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillHierarchy(System.Uri,System.String[],System.String,System.Int32,Microsoft.SharePoint.WebControls.SPProviderHierarchyTree)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.fillhierarchy(v=AX.60)
ms:contentKeyID: 62205063
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillHierarchy
dev_langs:
- CSharp
- C++
- VB
---

# FillHierarchy Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Fills the hierarchy.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub FillHierarchy ( _
    context As Uri, _
    entityTypes As String(), _
    hierarchyNodeID As String, _
    numberOfLevels As Integer, _
    hierarchy As SPProviderHierarchyTree _
)
'Usage
Dim context As Uri
Dim entityTypes As String()
Dim hierarchyNodeID As String
Dim numberOfLevels As Integer
Dim hierarchy As SPProviderHierarchyTree

Me.FillHierarchy(context, entityTypes, _
    hierarchyNodeID, numberOfLevels, _
    hierarchy)
```

``` csharp
protected override void FillHierarchy(
    Uri context,
    string[] entityTypes,
    string hierarchyNodeID,
    int numberOfLevels,
    SPProviderHierarchyTree hierarchy
)
```

``` c++
protected:
virtual void FillHierarchy(
    Uri^ context, 
    array<String^>^ entityTypes, 
    String^ hierarchyNodeID, 
    int numberOfLevels, 
    SPProviderHierarchyTree^ hierarchy
) override
```

#### Parameters

  - context  
    Type: [System.Uri](https://technet.microsoft.com/library/txt7706a\(v=ax.60\))  

<!-- end list -->

  - entityTypes  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

<!-- end list -->

  - hierarchyNodeID  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - numberOfLevels  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - hierarchy  
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

