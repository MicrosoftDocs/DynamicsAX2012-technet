---
title: IInfoCodeSystemV1.GetInfocodes Method (String) (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: GetInfocodes Method (String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IInfoCodeSystemV1.GetInfocodes(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iinfocodesystemv1.getinfocodes(v=AX.60)
ms:contentKeyID: 47128608
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetInfocodes Method (String)

Gets the list of infocodes for the given infocode ID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetInfocodes ( _
    infoCodeId As String _
) As IInfoCodeLineItem()
'Usage
Dim instance As IInfoCodeSystemV1
Dim infoCodeId As String
Dim returnValue As IInfoCodeLineItem()

returnValue = instance.GetInfocodes(infoCodeId)
```

``` csharp
IInfoCodeLineItem[] GetInfocodes(
    string infoCodeId
)
```

``` c++
array<IInfoCodeLineItem^>^ GetInfocodes(
    String^ infoCodeId
)
```

#### Parameters

  - infoCodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItem](iinfocodelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\[\]  
Returns array of IInfoCodeLineItem.  

## See Also

#### Reference

[IInfoCodeSystemV1 Interface](iinfocodesystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[GetInfocodes Overload](iinfocodesystemv1-getinfocodes-method-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

