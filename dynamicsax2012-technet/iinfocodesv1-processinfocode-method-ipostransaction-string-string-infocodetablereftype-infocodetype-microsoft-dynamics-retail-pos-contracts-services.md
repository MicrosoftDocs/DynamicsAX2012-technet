---
title: IInfoCodesV1.ProcessInfoCode Method (IPosTransaction, String, String, InfoCodeTableRefType, InfoCodeType) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessInfoCode Method (IPosTransaction, String, String, InfoCodeTableRefType, InfoCodeType)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IInfoCodesV1.ProcessInfoCode(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.String,System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iinfocodesv1.processinfocode(v=AX.60)
ms:contentKeyID: 47344312
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProcessInfoCode Method (IPosTransaction, String, String, InfoCodeTableRefType, InfoCodeType)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Process the infocode based on its parameters.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ProcessInfoCode ( _
    posTransaction As IPosTransaction, _
    refRelation As String, _
    refRelation2 As String, _
    tableRefId As InfoCodeTableRefType, _
    infoCodeType As InfoCodeType _
) As Boolean
'Usage
Dim instance As IInfoCodesV1
Dim posTransaction As IPosTransaction
Dim refRelation As String
Dim refRelation2 As String
Dim tableRefId As InfoCodeTableRefType
Dim infoCodeType As InfoCodeType
Dim returnValue As Boolean

returnValue = instance.ProcessInfoCode(posTransaction, _
    refRelation, refRelation2, tableRefId, _
    infoCodeType)
```

``` csharp
bool ProcessInfoCode(
    IPosTransaction posTransaction,
    string refRelation,
    string refRelation2,
    InfoCodeTableRefType tableRefId,
    InfoCodeType infoCodeType
)
```

``` c++
bool ProcessInfoCode(
    IPosTransaction^ posTransaction, 
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
true if code is processed; otherwise, false.  

## See Also

#### Reference

[IInfoCodesV1 Interface](iinfocodesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ProcessInfoCode Overload](iinfocodesv1-processinfocode-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

