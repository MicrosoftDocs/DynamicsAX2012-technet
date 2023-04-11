---
title: SalesTransaction.CustomerOrderModeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerOrderModeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.CustomerOrderModeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.customerordermodevalue(v=AX.60)
ms:contentKeyID: 65318986
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.CustomerOrderModeValue
dev_langs:
- CSharp
- C++
- VB
---

# CustomerOrderModeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("CUSTOMERORDERMODE")> _
<DataMemberAttribute> _
Public Property CustomerOrderModeValue As Integer
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Integer

value = instance.CustomerOrderModeValue

instance.CustomerOrderModeValue = value
```

``` csharp
[ReadOnlyAttribute("CUSTOMERORDERMODE")]
[DataMemberAttribute]
public int CustomerOrderModeValue { get; set; }
```

``` c++
[ReadOnlyAttribute(L"CUSTOMERORDERMODE")]
[DataMemberAttribute]
public:
property int CustomerOrderModeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

