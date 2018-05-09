---
title: GlobalCustomer.PartyNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PartyNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.PartyNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.globalcustomer.partynumber(v=AX.60)
ms:contentKeyID: 62204166
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.PartyNumber
dev_langs:
- CSharp
- C++
- VB
---

# PartyNumber Property

Gets or sets the party number

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PARTYNUMBER")> _
<KeyAttribute> _
<DataMemberAttribute> _
Public Property PartyNumber As String
    Get
    Set
'Usage
Dim instance As GlobalCustomer
Dim value As String

value = instance.PartyNumber

instance.PartyNumber = value
```

``` csharp
[ColumnAttribute("PARTYNUMBER")]
[KeyAttribute]
[DataMemberAttribute]
public string PartyNumber { get; set; }
```

``` c++
[ColumnAttribute(L"PARTYNUMBER")]
[KeyAttribute]
[DataMemberAttribute]
public:
property String^ PartyNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The party number.  

## See Also

#### Reference

[GlobalCustomer Class](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

