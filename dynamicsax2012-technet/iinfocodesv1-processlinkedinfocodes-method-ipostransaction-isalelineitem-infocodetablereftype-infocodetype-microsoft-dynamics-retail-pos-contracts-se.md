---
title: IInfoCodesV1.ProcessLinkedInfoCodes Method (IPosTransaction, ISaleLineItem, InfoCodeTableRefType, InfoCodeType) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessLinkedInfoCodes Method (IPosTransaction, ISaleLineItem, InfoCodeTableRefType, InfoCodeType)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IInfoCodesV1.ProcessLinkedInfoCodes(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iinfocodesv1.processlinkedinfocodes(v=AX.60)
ms:contentKeyID: 47343833
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProcessLinkedInfoCodes Method (IPosTransaction, ISaleLineItem, InfoCodeTableRefType, InfoCodeType)

Process Linked InfoCodes for SaleLineItem.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ProcessLinkedInfoCodes ( _
    posTransaction As IPosTransaction, _
    saleLineItem As ISaleLineItem, _
    tableRefId As InfoCodeTableRefType, _
    infoCodeType As InfoCodeType _
)
'Usage
Dim instance As IInfoCodesV1
Dim posTransaction As IPosTransaction
Dim saleLineItem As ISaleLineItem
Dim tableRefId As InfoCodeTableRefType
Dim infoCodeType As InfoCodeType

instance.ProcessLinkedInfoCodes(posTransaction, _
    saleLineItem, tableRefId, infoCodeType)
```

``` csharp
void ProcessLinkedInfoCodes(
    IPosTransaction posTransaction,
    ISaleLineItem saleLineItem,
    InfoCodeTableRefType tableRefId,
    InfoCodeType infoCodeType
)
```

``` c++
void ProcessLinkedInfoCodes(
    IPosTransaction^ posTransaction, 
    ISaleLineItem^ saleLineItem, 
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

  - tableRefId  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType](infocodetablereftype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - infoCodeType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType](infocodetype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IInfoCodesV1 Interface](iinfocodesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ProcessLinkedInfoCodes Overload](iinfocodesv1-processlinkedinfocodes-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

