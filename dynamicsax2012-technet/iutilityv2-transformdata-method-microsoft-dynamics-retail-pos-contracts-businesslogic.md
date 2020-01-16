---
title: IUtilityV2.TransformData Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: TransformData Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.TransformData(System.String,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.transformdata(v=AX.60)
ms:contentKeyID: 49823543
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.TransformData
dev_langs:
- CSharp
- C++
- VB
---

# TransformData Method

Linear transform of data.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function TransformData ( _
    data As String, _
    passwordEncryption As String, _
    invariant As String, _
    context As String, _
    cell As String _
) As String
'Usage
Dim instance As IUtilityV2
Dim data As String
Dim passwordEncryption As String
Dim invariant As String
Dim context As String
Dim cell As String
Dim returnValue As String

returnValue = instance.TransformData(data, _
    passwordEncryption, invariant, context, _
    cell)
```

``` csharp
string TransformData(
    string data,
    string passwordEncryption,
    string invariant,
    string context,
    string cell
)
```

``` c++
String^ TransformData(
    String^ data, 
    String^ passwordEncryption, 
    String^ invariant, 
    String^ context, 
    String^ cell
)
```

#### Parameters

  - data  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - passwordEncryption  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - invariant  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - context  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cell  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Transformed data.  

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
<td><a href="https://technet.microsoft.com/library/30ey6wfx(v=ax.60)">CryptographicException</a></td>
<td><p>The transform could not be completed.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

