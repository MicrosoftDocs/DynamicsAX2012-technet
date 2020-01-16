---
title: IDialogV2.Search Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Search Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV2.Search(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.SearchType,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idialogv2.search(v=AX.60)
ms:contentKeyID: 49842660
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV2.Search
dev_langs:
- CSharp
- C++
- VB
---

# Search Method

Searches the specified search term.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Search ( _
    searchType As SearchType, _
    searchTerm As String, _
    showUIForEmptyResult As Boolean _
) As ISearchResult
'Usage
Dim instance As IDialogV2
Dim searchType As SearchType
Dim searchTerm As String
Dim showUIForEmptyResult As Boolean
Dim returnValue As ISearchResult

returnValue = instance.Search(searchType, _
    searchTerm, showUIForEmptyResult)
```

``` csharp
ISearchResult Search(
    SearchType searchType,
    string searchTerm,
    bool showUIForEmptyResult
)
```

``` c++
ISearchResult^ Search(
    SearchType searchType, 
    String^ searchTerm, 
    bool showUIForEmptyResult
)
```

#### Parameters

  - searchType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.SearchType](searchtype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - searchTerm  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - showUIForEmptyResult  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISearchResult](isearchresult-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Selected result if found, null otherwise.  

## See Also

#### Reference

[IDialogV2 Interface](idialogv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

