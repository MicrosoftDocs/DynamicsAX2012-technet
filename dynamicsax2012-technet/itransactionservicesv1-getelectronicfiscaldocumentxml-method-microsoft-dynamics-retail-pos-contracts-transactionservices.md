---
title: ITransactionServicesV1.GetElectronicFiscalDocumentXml Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: GetElectronicFiscalDocumentXml Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetElectronicFiscalDocumentXml(System.Boolean@,System.String@,System.Data.DataTable@,System.DateTime,System.DateTime,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.getelectronicfiscaldocumentxml(v=AX.60)
ms:contentKeyID: 49831331
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetElectronicFiscalDocumentXml
dev_langs:
- CSharp
- C++
- VB
---

# GetElectronicFiscalDocumentXml Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetElectronicFiscalDocumentXml ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef xmlTable As DataTable, _
    startDate As DateTime, _
    endDate As DateTime, _
    fiscalEstablishmentId As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim xmlTable As DataTable
Dim startDate As DateTime
Dim endDate As DateTime
Dim fiscalEstablishmentId As String

instance.GetElectronicFiscalDocumentXml(retValue, _
    comment, xmlTable, startDate, endDate, _
    fiscalEstablishmentId)
```

``` csharp
void GetElectronicFiscalDocumentXml(
    ref bool retValue,
    ref string comment,
    ref DataTable xmlTable,
    DateTime startDate,
    DateTime endDate,
    string fiscalEstablishmentId
)
```

``` c++
void GetElectronicFiscalDocumentXml(
    bool% retValue, 
    String^% comment, 
    DataTable^% xmlTable, 
    DateTime startDate, 
    DateTime endDate, 
    String^ fiscalEstablishmentId
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - xmlTable  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - startDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - endDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - fiscalEstablishmentId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

