---
title: IItemV2.GetProductsByKeyword Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetProductsByKeyword Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItemV2.GetProductsByKeyword(System.Int64,System.String,System.Int64,System.Int64,System.String,System.String,System.Data.DataTable@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iitemv2.getproductsbykeyword(v=AX.60)
ms:contentKeyID: 62202535
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItemV2.GetProductsByKeyword
dev_langs:
- CSharp
- C++
- VB
---

# GetProductsByKeyword Method

Gets list of Products from Product search in AX by Keyword - Transaction Service call.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetProductsByKeyword ( _
    retailChannelRecId As Long, _
    keyword As String, _
    _startPosition As Long, _
    _pageSize As Long, _
    _orderByField As String, _
    _sortOrder As String, _
    ByRef itemsTable As DataTable _
)
'Usage
Dim instance As IItemV2
Dim retailChannelRecId As Long
Dim keyword As String
Dim _startPosition As Long
Dim _pageSize As Long
Dim _orderByField As String
Dim _sortOrder As String
Dim itemsTable As DataTable

instance.GetProductsByKeyword(retailChannelRecId, _
    keyword, _startPosition, _pageSize, _
    _orderByField, _sortOrder, itemsTable)
```

``` csharp
void GetProductsByKeyword(
    long retailChannelRecId,
    string keyword,
    long _startPosition,
    long _pageSize,
    string _orderByField,
    string _sortOrder,
    ref DataTable itemsTable
)
```

``` c++
void GetProductsByKeyword(
    long long retailChannelRecId, 
    String^ keyword, 
    long long _startPosition, 
    long long _pageSize, 
    String^ _orderByField, 
    String^ _sortOrder, 
    DataTable^% itemsTable
)
```

#### Parameters

  - retailChannelRecId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - keyword  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - \_startPosition  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - \_pageSize  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - \_orderByField  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - \_sortOrder  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemsTable  
    Type: [System.Data.DataTable](https://technet.microsoft.com/en-us/library/9186hy08\(v=ax.60\))  

## See Also

#### Reference

[IItemV2 Interface](iitemv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

