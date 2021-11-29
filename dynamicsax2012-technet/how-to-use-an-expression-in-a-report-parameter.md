---
title: 'How to: Use an Expression in a Report Parameter'
TOCTitle: 'How to: Use an Expression in a Report Parameter'
ms:assetid: 0c2cb581-55d5-4ade-8d68-deed759872e1
ms:mtpsurl: https://technet.microsoft.com/library/Hh533445(v=AX.60)
ms:contentKeyID: 39056461
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Use an Expression in a Report Parameter 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Expressions are used throughout a report definition to control content and format the data in a report. You can use the Edit Expression window to write an expression to do the following parameter related tasks:

  - Set the default value of the parameter in the **Default Value** property.

  - Provide the possible values for the parameter label and value pair in the **Values** property.
    

    > [!NOTE]
    > <P>Localization is not supported if you use an expression to set the Values of the parameter. You must use a value that is bound to a dataset if you are creating localized versions of the report.</P>



The following sections describe how to use an expression in a parameter.

### To set the default value of a parameter by using the Edit Expression window

1.  In Model Editor, open a report that you want to work with.

2.  Expand the **Parameters** node for the report and select the parameter that you want to set the default value for.

3.  In the Properties window, in the **Default Value** property, click the ellipses button **(…)**. The **Select a default value** dialog box opens.

4.  Select the **Non-queried** radio button, and then click the ellipses button **(…)**. The Edit Expression window opens.

5.  Provide an expression to set the default value of the parameter. For example, if the parameter is a **DateTime** data type, you could set the **Default Value** property to =Today().

### To set the possible values for the parameter by using the Edit Expression window

1.  In Model Editor, open a report that you want to work with.

2.  Expand the **Parameters** node for the report and select the parameter for which you want to set the possible value.

3.  In the Properties window, locate the **Values** property, and then click the ellipses button **(…)**. A **Select values** dialog box opens.

4.  Select the **Non-queried** radio button, and then click the ellipses button **(…)** for the **Value** field or **Label** field. The Edit Expression window opens.

5.  Provide an expression to set the possible values of the parameter. For example, if you want to add the **Value** and **Label** pairs for three dates:
    
      - Today
    
      - Last year on this day
    
      - Two years ago on this day
    
    Then you would do the following:
    
    1.  In the **Select values** dialog box, set **Value** to 1.
    
    2.  Click the ellipses button **(…)** for the **Label** field. The Edit Expression window opens.
    
    3.  Set the **Label** expression to **=Today()**, and then click **OK**.
    
    4.  In the **Select values** dialog box, set **Value** to 2.
    
    5.  Click the ellipses button **(…)** for the **Label** field. The Edit Expression window opens.
    
    6.  Set the **Label** expression to **=System.DateTime.today().addYears(-1)** and then click **OK**.
    
    7.  In the **Select values** dialog box, set **Value** to 3.
    
    8.  Click the ellipses button **(…)** for the **Label** field. The Edit Expression window opens.
    
    9.  Set the **Label** expression to **=System.DateTime.today().addYears(-2)** and then click **OK**.

To see the expressions used in the parameter, you must deploy the report to the report server.

## See also

[Working with Parameters](working-with-parameters.md)

[Edit Expression Overview](edit-expression-overview.md)

