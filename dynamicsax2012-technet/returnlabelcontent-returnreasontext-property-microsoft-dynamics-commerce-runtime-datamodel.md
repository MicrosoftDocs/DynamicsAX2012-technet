---
title: ReturnLabelContent.ReturnReasonText Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnReasonText Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReturnLabelContent.ReturnReasonText
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.returnlabelcontent.returnreasontext(v=AX.60)
ms:contentKeyID: 65318291
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReturnLabelContent.ReturnReasonText
dev_langs:
- CSharp
- C++
- VB
---

# ReturnReasonText Property

Gets or sets return reason text.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReturnReasonText As String
    Get
    Set
'Usage
Dim instance As ReturnLabelContent
Dim value As String

value = instance.ReturnReasonText

instance.ReturnReasonText = value
```

``` csharp
[DataMemberAttribute]
public string ReturnReasonText { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReturnReasonText {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The return reason, if any.  

## See Also

#### Reference

[ReturnLabelContent Class](returnlabelcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

