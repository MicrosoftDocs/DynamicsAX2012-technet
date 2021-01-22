---
title: CustomClaimsProvider.FillEntityTypes Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: FillEntityTypes Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillEntityTypes(System.Collections.Generic.List{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.fillentitytypes(v=AX.60)
ms:contentKeyID: 62207362
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillEntityTypes
dev_langs:
- CSharp
- C++
- VB
---

# FillEntityTypes Method

Fills the entity types.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub FillEntityTypes ( _
    entityTypes As List(Of String) _
)
'Usage
Dim entityTypes As List(Of String)

Me.FillEntityTypes(entityTypes)
```

``` csharp
protected override void FillEntityTypes(
    List<string> entityTypes
)
```

``` c++
protected:
virtual void FillEntityTypes(
    List<String^>^ entityTypes
) override
```

#### Parameters

  - entityTypes  
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
<td><a href="https://technet.microsoft.com/library/6byb74h9(v=ax.60)">NotImplementedException</a></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[CustomClaimsProvider Class](customclaimsprovider-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

