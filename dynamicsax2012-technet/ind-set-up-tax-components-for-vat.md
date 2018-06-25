---
title: (IND) Set up tax components for VAT
TOCTitle: (IND) Set up tax components for VAT
ms:assetid: 67259b6a-661c-4048-b86d-76ccd8201743
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677878(v=AX.60)
ms:contentKeyID: 49385842
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Set up tax components for VAT [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax components**.

2.  Select **VAT** in the **Tax type** field.

3.  On the **Overview** tab, press CTRL+N to create a new tax component.

4.  Enter the name for the tax component of VAT in the **Tax component** field and a description in the **Description** field.

5.  Click **Tax setoff rule** to open the **Tax setoff rule** form. Define the setoff components for the tax component.

6.  Press CTRL+N to create a new line and enter the order of priority for the setoff component in the **Column** field.

7.  Select the setoff component in the **Setoff component** field to offset against the original VAT component.
    

    > [!NOTE]
    > <P>The same setoff component cannot be selected twice for a tax component in the <STRONG>Tax setoff rule</STRONG> form.</P>



8.  You can change the order of priority of the setoff components by using **Up** and **Down**.

9.  Click the **General** tab to view the details of the setoff component.

10. Press CTRL+S or close the form.

## See also

[(IND) Tax components (form)](https://technet.microsoft.com/en-us/library/jj664734\(v=ax.60\))

[(IND) Tax setoff rule (form)](https://technet.microsoft.com/en-us/library/jj677818\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

