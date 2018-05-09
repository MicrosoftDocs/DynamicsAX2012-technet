---
title: ReasonCodeSpecific.InputRequiredTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InputRequiredTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.InputRequiredTypeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodespecific.inputrequiredtypevalue(v=AX.60)
ms:contentKeyID: 62211335
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.InputRequiredTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# InputRequiredTypeValue Property

Gets or sets the input required type of the reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InputRequiredTypeValue As Integer
    Get
    Set
'Usage
Dim instance As ReasonCodeSpecific
Dim value As Integer

value = instance.InputRequiredTypeValue

instance.InputRequiredTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int InputRequiredTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int InputRequiredTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The input required type value.  

## See Also

#### Reference

[ReasonCodeSpecific Class](reasoncodespecific-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

