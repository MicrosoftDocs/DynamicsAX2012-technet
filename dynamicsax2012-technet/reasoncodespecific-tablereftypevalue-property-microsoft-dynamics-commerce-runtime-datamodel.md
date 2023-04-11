---
title: ReasonCodeSpecific.TableRefTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TableRefTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.TableRefTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodespecific.tablereftypevalue(v=AX.60)
ms:contentKeyID: 62213395
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.TableRefTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# TableRefTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the table ref type of the reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<KeyAttribute> _
Public Property TableRefTypeValue As Integer
    Get
    Set
'Usage
Dim instance As ReasonCodeSpecific
Dim value As Integer

value = instance.TableRefTypeValue

instance.TableRefTypeValue = value
```

``` csharp
[DataMemberAttribute]
[KeyAttribute]
public int TableRefTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
[KeyAttribute]
public:
property int TableRefTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The type of the table.  

## See Also

#### Reference

[ReasonCodeSpecific Class](reasoncodespecific-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

