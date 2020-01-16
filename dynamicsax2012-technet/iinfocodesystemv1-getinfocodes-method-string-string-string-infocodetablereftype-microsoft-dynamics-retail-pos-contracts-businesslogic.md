---
title: IInfoCodeSystemV1.GetInfocodes Method (String, String, String, InfoCodeTableRefType) (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: GetInfocodes Method (String, String, String, InfoCodeTableRefType)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IInfoCodeSystemV1.GetInfocodes(System.String,System.String,System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iinfocodesystemv1.getinfocodes(v=AX.60)
ms:contentKeyID: 47128860
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetInfocodes Method (String, String, String, InfoCodeTableRefType)

Gets the infocode information.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetInfocodes ( _
    refRelation As String, _
    refRelation2 As String, _
    refRelation3 As String, _
    refTableId As InfoCodeTableRefType _
) As IInfoCodeLineItem()
'Usage
Dim instance As IInfoCodeSystemV1
Dim refRelation As String
Dim refRelation2 As String
Dim refRelation3 As String
Dim refTableId As InfoCodeTableRefType
Dim returnValue As IInfoCodeLineItem()

returnValue = instance.GetInfocodes(refRelation, _
    refRelation2, refRelation3, refTableId)
```

``` csharp
IInfoCodeLineItem[] GetInfocodes(
    string refRelation,
    string refRelation2,
    string refRelation3,
    InfoCodeTableRefType refTableId
)
```

``` c++
array<IInfoCodeLineItem^>^ GetInfocodes(
    String^ refRelation, 
    String^ refRelation2, 
    String^ refRelation3, 
    InfoCodeTableRefType refTableId
)
```

#### Parameters

  - refRelation  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - refRelation2  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - refRelation3  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - refTableId  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType](infocodetablereftype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItem](iinfocodelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\[\]  
Returns array of IInfoCodeLineItems.  

## See Also

#### Reference

[IInfoCodeSystemV1 Interface](iinfocodesystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[GetInfocodes Overload](iinfocodesystemv1-getinfocodes-method-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

