---
title: (IND) Create a tax registration group
TOCTitle: (IND) Create a tax registration group
ms:assetid: 01c516a8-8c97-4d04-9054-2e80ae0dbe4b
ms:mtpsurl: https://technet.microsoft.com/library/JJ664429(v=AX.60)
ms:contentKeyID: 49385517
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create a tax registration group 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



A tax registration group includes tax registration numbers of different tax types. You can create a tax registration group to set off the recoverable tax from one tax type to another. Select the tax registration group in the **Sales tax payment** form to process the settlement of the tax to the authority


> [!NOTE]
> <P>You cannot select registration numbers of the same tax type more than once in a tax registration group except for the <STRONG>Sales</STRONG> tax type. You can attach more than one registration number of a <STRONG>Sales</STRONG> tax type in a tax registration group, but cannot repeat the same registration number.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax registration group**.

2.  Click the **Overview** tab and press CTRL+N to create a new tax registration group.

3.  Enter a name for the tax registration group in the **Tax registration group** field.

4.  Enter a description for the tax registration group in the **Description** field.

5.  The **In use** check box is automatically selected only when the tax registration group is selected in the **Sales tax payment** form.
    

    > [!NOTE]
    > <P>If the registration number in use belongs to other groups, then the <STRONG>In use</STRONG> check box is selected for the other groups.</P>

    
      - When the **Sales tax payment** form is open, you cannot clear the **In use** check box for that tax registration group.
    
      - When you close the **Sales tax payment** form either by clicking **OK** or **Cancel**, the **In use** check box of the specific tax registration group and the dependant tax groups are cleared automatically.
    
      - You can clear the **In use** check box in the case of an abrupt system shutdown, such as a power failure. When you clear the **In use** check box for any tax registration group, all the dependant groups are automatically cleared.

6.  Click the **Setup** tab and press CTRL+N to set up tax registration numbers for the tax registration group.

7.  Select the name of the tax type in the **Tax type** field.

8.  Select the tax registration number in the **Tax registration number** field.

9.  Enter a description for the registration number in the **Description** field.

10. Press CTRL+S or close the form.

## See also

[(IND) Tax registration group (form)](https://technet.microsoft.com/library/jj664453\(v=ax.60\))

[(IND) Sales tax payment (modified form)](https://technet.microsoft.com/library/jj664427\(v=ax.60\))

  


