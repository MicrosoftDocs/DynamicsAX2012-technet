---
title: CustomClaimsProvider.FillClaimTypes Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: FillClaimTypes Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillClaimTypes(System.Collections.Generic.List{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.fillclaimtypes(v=AX.60)
ms:contentKeyID: 62205884
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillClaimTypes
dev_langs:
- CSharp
- C++
- VB
---

# FillClaimTypes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Fills the claim types.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub FillClaimTypes ( _
    claimTypes As List(Of String) _
)
'Usage
Dim claimTypes As List(Of String)

Me.FillClaimTypes(claimTypes)
```

``` csharp
protected override void FillClaimTypes(
    List<string> claimTypes
)
```

``` c++
protected:
virtual void FillClaimTypes(
    List<String^>^ claimTypes
) override
```

#### Parameters

  - claimTypes  
    Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

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
<td><p>claimTypes</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[CustomClaimsProvider Class](customclaimsprovider-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

