---
title: FilteringCriteria.Item Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: Item Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.Item(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.filteringcriteria.item(v=AX.60)
ms:contentKeyID: 49822315
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.Item
dev_langs:
- CSharp
- C++
- VB
---

# Item Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value associated with the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property Item ( _
    key As String _
) As Object
    Get
    Set
'Usage
Dim instance As FilteringCriteria
Dim key As String
Dim value As Object

value = instance.Item(key)

instance.Item(key) = value
```

``` csharp
public Object this[
    string key
] { get; set; }
```

``` c++
public:
property Object^ Item[String^ key] {
    Object^ get (String^ key);
    void set (String^ key, Object^ value);
}
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
The value associated with the specified key or NULL if the specified key does not exist.  

## See Also

#### Reference

[FilteringCriteria Class](filteringcriteria-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

