---
title: IInfoCodesV1.ProcessLinkedInfoCodes Method (IPosTransaction, ITenderLineItem, String, InfoCodeTableRefType, InfoCodeType) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessLinkedInfoCodes Method (IPosTransaction, ITenderLineItem, String, InfoCodeTableRefType, InfoCodeType)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IInfoCodesV1.ProcessLinkedInfoCodes(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItem,System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iinfocodesv1.processlinkedinfocodes(v=AX.60)
ms:contentKeyID: 47343970
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProcessLinkedInfoCodes Method (IPosTransaction, ITenderLineItem, String, InfoCodeTableRefType, InfoCodeType)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Process Linked InfoCodes for TenderLineItem.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ProcessLinkedInfoCodes ( _
    posTransaction As IPosTransaction, _
    tenderLineItem As ITenderLineItem, _
    storeId As String, _
    tableRefId As InfoCodeTableRefType, _
    infoCodeType As InfoCodeType _
)
'Usage
Dim instance As IInfoCodesV1
Dim posTransaction As IPosTransaction
Dim tenderLineItem As ITenderLineItem
Dim storeId As String
Dim tableRefId As InfoCodeTableRefType
Dim infoCodeType As InfoCodeType

instance.ProcessLinkedInfoCodes(posTransaction, _
    tenderLineItem, storeId, tableRefId, _
    infoCodeType)
```

``` csharp
void ProcessLinkedInfoCodes(
    IPosTransaction posTransaction,
    ITenderLineItem tenderLineItem,
    string storeId,
    InfoCodeTableRefType tableRefId,
    InfoCodeType infoCodeType
)
```

``` c++
void ProcessLinkedInfoCodes(
    IPosTransaction^ posTransaction, 
    ITenderLineItem^ tenderLineItem, 
    String^ storeId, 
    InfoCodeTableRefType tableRefId, 
    InfoCodeType infoCodeType
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - tenderLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItem](itenderlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

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

