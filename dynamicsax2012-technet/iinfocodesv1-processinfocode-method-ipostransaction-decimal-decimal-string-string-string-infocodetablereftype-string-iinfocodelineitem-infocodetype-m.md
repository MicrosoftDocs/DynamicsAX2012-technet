---
title: IInfoCodesV1.ProcessInfoCode Method (IPosTransaction, Decimal, Decimal, String, String, String, InfoCodeTableRefType, String, IInfoCodeLineItem, InfoCodeType) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessInfoCode Method (IPosTransaction, Decimal, Decimal, String, String, String, InfoCodeTableRefType, String, IInfoCodeLineItem, InfoCodeType)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IInfoCodesV1.ProcessInfoCode(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Decimal,System.Decimal,System.String,System.String,System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType,System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iinfocodesv1.processinfocode(v=AX.60)
ms:contentKeyID: 47344373
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProcessInfoCode Method (IPosTransaction, Decimal, Decimal, String, String, String, InfoCodeTableRefType, String, IInfoCodeLineItem, InfoCodeType)

Process the infocode based on its parameters.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ProcessInfoCode ( _
    posTransaction As IPosTransaction, _
    quantity As Decimal, _
    amount As Decimal, _
    refRelation As String, _
    refRelation2 As String, _
    refRelation3 As String, _
    tableRefId As InfoCodeTableRefType, _
    linkedInfoCodeId As String, _
    orgInfoCode As IInfoCodeLineItem, _
    infoCodeType As InfoCodeType _
) As Boolean
'Usage
Dim instance As IInfoCodesV1
Dim posTransaction As IPosTransaction
Dim quantity As Decimal
Dim amount As Decimal
Dim refRelation As String
Dim refRelation2 As String
Dim refRelation3 As String
Dim tableRefId As InfoCodeTableRefType
Dim linkedInfoCodeId As String
Dim orgInfoCode As IInfoCodeLineItem
Dim infoCodeType As InfoCodeType
Dim returnValue As Boolean

returnValue = instance.ProcessInfoCode(posTransaction, _
    quantity, amount, refRelation, refRelation2, _
    refRelation3, tableRefId, linkedInfoCodeId, _
    orgInfoCode, infoCodeType)
```

``` csharp
bool ProcessInfoCode(
    IPosTransaction posTransaction,
    decimal quantity,
    decimal amount,
    string refRelation,
    string refRelation2,
    string refRelation3,
    InfoCodeTableRefType tableRefId,
    string linkedInfoCodeId,
    IInfoCodeLineItem orgInfoCode,
    InfoCodeType infoCodeType
)
```

``` c++
bool ProcessInfoCode(
    IPosTransaction^ posTransaction, 
    Decimal quantity, 
    Decimal amount, 
    String^ refRelation, 
    String^ refRelation2, 
    String^ refRelation3, 
    InfoCodeTableRefType tableRefId, 
    String^ linkedInfoCodeId, 
    IInfoCodeLineItem^ orgInfoCode, 
    InfoCodeType infoCodeType
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - refRelation  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - refRelation2  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - refRelation3  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tableRefId  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType](infocodetablereftype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - linkedInfoCodeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - orgInfoCode  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItem](iinfocodelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - infoCodeType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType](infocodetype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if code is processed; otherwise, false.  

## See Also

#### Reference

[IInfoCodesV1 Interface](iinfocodesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ProcessInfoCode Overload](iinfocodesv1-processinfocode-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

