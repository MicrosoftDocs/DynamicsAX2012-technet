---
title: ISalesOrderV1.GetCustomerOrdersForPackSlip Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetCustomerOrdersForPackSlip Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.GetCustomerOrdersForPackSlip(System.Boolean@,System.String@,System.Data.DataTable@,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.getcustomerordersforpackslip(v=AX.60)
ms:contentKeyID: 47343894
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.GetCustomerOrdersForPackSlip
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerOrdersForPackSlip Method

Get Open customer orders for particular customer. If there is no customer then get all open customer orders.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetCustomerOrdersForPackSlip ( _
    <OutAttribute> ByRef retValue As Boolean, _
    <OutAttribute> ByRef comment As String, _
    ByRef salesOrders As DataTable, _
    customerAccount As String _
)
'Usage
Dim instance As ISalesOrderV1
Dim retValue As Boolean
Dim comment As String
Dim salesOrders As DataTable
Dim customerAccount As String

instance.GetCustomerOrdersForPackSlip(retValue, _
    comment, salesOrders, customerAccount)
```

``` csharp
void GetCustomerOrdersForPackSlip(
    out bool retValue,
    out string comment,
    ref DataTable salesOrders,
    string customerAccount
)
```

``` c++
void GetCustomerOrdersForPackSlip(
    [OutAttribute] bool% retValue, 
    [OutAttribute] String^% comment, 
    DataTable^% salesOrders, 
    String^ customerAccount
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - salesOrders  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - customerAccount  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

