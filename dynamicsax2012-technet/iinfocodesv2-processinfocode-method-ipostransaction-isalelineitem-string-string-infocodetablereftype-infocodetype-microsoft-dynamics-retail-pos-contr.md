---
title: IInfoCodesV2.ProcessInfoCode Method (IPosTransaction, ISaleLineItem, String, String, InfoCodeTableRefType, InfoCodeType) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessInfoCode Method (IPosTransaction, ISaleLineItem, String, String, InfoCodeTableRefType, InfoCodeType)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IInfoCodesV2.ProcessInfoCode(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,System.String,System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iinfocodesv2.processinfocode(v=AX.60)
ms:contentKeyID: 62201999
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProcessInfoCode Method (IPosTransaction, ISaleLineItem, String, String, InfoCodeTableRefType, InfoCodeType)

ProcessInfoCode for a sale line item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ProcessInfoCode ( _
    posTransaction As IPosTransaction, _
    saleLineItem As ISaleLineItem, _
    refRelation As String, _
    refRelation2 As String, _
    tableRefId As InfoCodeTableRefType, _
    infoCodeType As InfoCodeType _
) As Boolean
'Usage
Dim instance As IInfoCodesV2
Dim posTransaction As IPosTransaction
Dim saleLineItem As ISaleLineItem
Dim refRelation As String
Dim refRelation2 As String
Dim tableRefId As InfoCodeTableRefType
Dim infoCodeType As InfoCodeType
Dim returnValue As Boolean

returnValue = instance.ProcessInfoCode(posTransaction, _
    saleLineItem, refRelation, refRelation2, _
    tableRefId, infoCodeType)
```

``` csharp
bool ProcessInfoCode(
    IPosTransaction posTransaction,
    ISaleLineItem saleLineItem,
    string refRelation,
    string refRelation2,
    InfoCodeTableRefType tableRefId,
    InfoCodeType infoCodeType
)
```

``` c++
bool ProcessInfoCode(
    IPosTransaction^ posTransaction, 
    ISaleLineItem^ saleLineItem, 
    String^ refRelation, 
    String^ refRelation2, 
    InfoCodeTableRefType tableRefId, 
    InfoCodeType infoCodeType
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - refRelation  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - refRelation2  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tableRefId  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType](infocodetablereftype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - infoCodeType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType](infocodetype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IInfoCodesV2 Interface](iinfocodesv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ProcessInfoCode Overload](iinfocodesv2-processinfocode-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

