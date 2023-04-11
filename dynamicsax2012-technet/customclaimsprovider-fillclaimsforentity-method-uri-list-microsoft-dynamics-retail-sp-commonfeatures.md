---
title: CustomClaimsProvider.FillClaimsForEntity Method (Uri, , List()) (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: FillClaimsForEntity Method (Uri, , List())
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillClaimsForEntity(System.Uri,Microsoft.SharePoint.Administration.Claims.SPClaim,System.Collections.Generic.List{Microsoft.SharePoint.Administration.Claims.SPClaim})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.fillclaimsforentity(v=AX.60)
ms:contentKeyID: 62204436
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# FillClaimsForEntity Method (Uri, , List())


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Augment the claims for a user/entity.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub FillClaimsForEntity ( _
    context As Uri, _
    entity As SPClaim, _
    claims As List(Of SPClaim) _
)
'Usage
Dim context As Uri
Dim entity As SPClaim
Dim claims As List(Of SPClaim)

Me.FillClaimsForEntity(context, entity, _
    claims)
```

``` csharp
protected override void FillClaimsForEntity(
    Uri context,
    SPClaim entity,
    List<SPClaim> claims
)
```

``` c++
protected:
virtual void FillClaimsForEntity(
    Uri^ context, 
    SPClaim^ entity, 
    List<SPClaim^>^ claims
) override
```

#### Parameters

  - context  
    Type: [System.Uri](https://technet.microsoft.com/library/txt7706a\(v=ax.60\))  

<!-- end list -->

  - entity  
    Type: SPClaim  

<!-- end list -->

  - claims  
    Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<SPClaim\>  

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
<td><p>entity or claims</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[CustomClaimsProvider Class](customclaimsprovider-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[FillClaimsForEntity Overload](customclaimsprovider-fillclaimsforentity-method-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

