---
title: CustomClaimsProvider.FillResolve Method (Uri, String , String, List()) (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: FillResolve Method (Uri, String , String, List())
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillResolve(System.Uri,System.String[],System.String,System.Collections.Generic.List{Microsoft.SharePoint.WebControls.PickerEntity})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.fillresolve(v=AX.60)
ms:contentKeyID: 62204047
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# FillResolve Method (Uri, String[], String, List())

Fills the resolve.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub FillResolve ( _
    context As Uri, _
    entityTypes As String(), _
    resolveInput As String, _
    resolved As List(Of PickerEntity) _
)
'Usage
Dim context As Uri
Dim entityTypes As String()
Dim resolveInput As String
Dim resolved As List(Of PickerEntity)

Me.FillResolve(context, entityTypes, _
    resolveInput, resolved)
```

``` csharp
protected override void FillResolve(
    Uri context,
    string[] entityTypes,
    string resolveInput,
    List<PickerEntity> resolved
)
```

``` c++
protected:
virtual void FillResolve(
    Uri^ context, 
    array<String^>^ entityTypes, 
    String^ resolveInput, 
    List<PickerEntity^>^ resolved
) override
```

#### Parameters

  - context  
    Type: [System.Uri](https://technet.microsoft.com/library/txt7706a\(v=ax.60\))  

<!-- end list -->

  - entityTypes  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

<!-- end list -->

  - resolveInput  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - resolved  
    Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<PickerEntity\>  

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

[FillResolve Overload](customclaimsprovider-fillresolve-method-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

