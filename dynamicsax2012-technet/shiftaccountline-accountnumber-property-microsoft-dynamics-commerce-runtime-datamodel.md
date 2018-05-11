﻿---
title: ShiftAccountLine.AccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftAccountLine.AccountNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shiftaccountline.accountnumber(v=AX.60)
ms:contentKeyID: 62208777
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftAccountLine.AccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# AccountNumber Property

Gets or sets account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INCOMEEXEPENSEACCOUNT")> _
Public Property AccountNumber As String
    Get
    Set
'Usage
Dim instance As ShiftAccountLine
Dim value As String

value = instance.AccountNumber

instance.AccountNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INCOMEEXEPENSEACCOUNT")]
public string AccountNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INCOMEEXEPENSEACCOUNT")]
public:
property String^ AccountNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShiftAccountLine Class](shiftaccountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
