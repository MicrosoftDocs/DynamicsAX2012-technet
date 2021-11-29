---
title: CustomClaimsProvider.FillSchema Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: FillSchema Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillSchema(Microsoft.SharePoint.WebControls.SPProviderSchema)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.fillschema(v=AX.60)
ms:contentKeyID: 62207192
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.FillSchema
dev_langs:
- CSharp
- C++
- VB
---

# FillSchema Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Fills the schema.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub FillSchema ( _
    schema As SPProviderSchema _
)
'Usage
Dim schema As SPProviderSchema

Me.FillSchema(schema)
```

``` csharp
protected override void FillSchema(
    SPProviderSchema schema
)
```

``` c++
protected:
virtual void FillSchema(
    SPProviderSchema^ schema
) override
```

#### Parameters

  - schema  
    Type: SPProviderSchema  

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

