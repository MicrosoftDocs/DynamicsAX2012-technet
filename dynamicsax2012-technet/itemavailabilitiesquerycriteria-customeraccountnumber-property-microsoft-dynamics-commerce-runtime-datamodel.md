---
title: ItemAvailabilitiesQueryCriteria.CustomerAccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerAccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.CustomerAccountNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailabilitiesquerycriteria.customeraccountnumber(v=AX.60)
ms:contentKeyID: 65323218
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.CustomerAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAccountNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerAccountNumber As String
    Get
    Private Set
'Usage
Dim instance As ItemAvailabilitiesQueryCriteria
Dim value As String

value = instance.CustomerAccountNumber
```

``` csharp
[DataMemberAttribute]
public string CustomerAccountNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerAccountNumber {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The customer account number.  

## See Also

#### Reference

[ItemAvailabilitiesQueryCriteria Class](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

