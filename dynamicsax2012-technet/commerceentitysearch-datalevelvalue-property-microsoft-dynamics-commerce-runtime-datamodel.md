---
title: CommerceEntitySearch.DataLevelValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataLevelValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearch.DataLevelValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentitysearch.datalevelvalue(v=AX.60)
ms:contentKeyID: 62206634
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearch.DataLevelValue
dev_langs:
- CSharp
- C++
- VB
---

# DataLevelValue Property

Gets or sets the data level of the entity to be retrieved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property DataLevelValue As Integer
    Get
    Set
'Usage
Dim instance As CommerceEntitySearch
Dim value As Integer

value = instance.DataLevelValue

instance.DataLevelValue = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public int DataLevelValue { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property int DataLevelValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The data level to be retrieved.  

## See Also

#### Reference

[CommerceEntitySearch Class](commerceentitysearch-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

