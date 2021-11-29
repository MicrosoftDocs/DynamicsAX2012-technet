---
title: GetEmployeeBreakCategoriesByActivityDataRequest.ActivityNames Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ActivityNames Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeBreakCategoriesByActivityDataRequest.ActivityNames
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getemployeebreakcategoriesbyactivitydatarequest.activitynames(v=AX.60)
ms:contentKeyID: 65323228
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeBreakCategoriesByActivityDataRequest.ActivityNames
dev_langs:
- CSharp
- C++
- VB
---

# ActivityNames Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the activity names.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActivityNames As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetEmployeeBreakCategoriesByActivityDataRequest
Dim value As IEnumerable(Of String)

value = instance.ActivityNames
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> ActivityNames { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ ActivityNames {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
The activity names.  

## See Also

#### Reference

[GetEmployeeBreakCategoriesByActivityDataRequest Class](getemployeebreakcategoriesbyactivitydatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

