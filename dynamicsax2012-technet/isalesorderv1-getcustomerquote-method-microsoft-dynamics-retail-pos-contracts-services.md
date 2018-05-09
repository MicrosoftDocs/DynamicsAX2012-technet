---
title: ISalesOrderV1.GetCustomerQuote Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetCustomerQuote Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.GetCustomerQuote(System.Boolean@,System.String,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.getcustomerquote(v=AX.60)
ms:contentKeyID: 47343915
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.GetCustomerQuote
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerQuote Method

Gets a sales quote.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetCustomerQuote ( _
    ByRef retValue As Boolean, _
    quoteId As String, _
    <OutAttribute> ByRef comment As String, _
    <OutAttribute> ByRef posTransaction As IRetailTransaction _
)
'Usage
Dim instance As ISalesOrderV1
Dim retValue As Boolean
Dim quoteId As String
Dim comment As String
Dim posTransaction As IRetailTransaction

instance.GetCustomerQuote(retValue, quoteId, _
    comment, posTransaction)
```

``` csharp
void GetCustomerQuote(
    ref bool retValue,
    string quoteId,
    out string comment,
    out IRetailTransaction posTransaction
)
```

``` c++
void GetCustomerQuote(
    bool% retValue, 
    String^ quoteId, 
    [OutAttribute] String^% comment, 
    [OutAttribute] IRetailTransaction^% posTransaction
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - quoteId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

