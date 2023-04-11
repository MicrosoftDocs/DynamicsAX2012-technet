---
title: (IND) Set up tax components for customs
TOCTitle: (IND) Set up tax components for customs
ms:assetid: 428e1355-9978-44d1-9fb8-d93f1b983e01
ms:mtpsurl: https://technet.microsoft.com/library/JJ664653(v=AX.60)
ms:contentKeyID: 49385771
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up tax components for customs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can set up tax components for customs and define a claim percentage for a tax component in the **Claim percentage** form. You can then create and update a tax setoff rule in the **Tax setoff rule** form to define the setoff components to set off the tax liability for a specific customs tax component.

You can offset the amounts in the excise payable account with the amounts in the recoverable accounts for the tax components of excise, as well as other tax components.

## Define a customs tax component

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax components**.

2.  Select **Customs** in the **Tax type** field.

3.  Press CTRL+N to create a new line.

4.  Enter a unique identification for the customs tax component in the **Tax components** field.

5.  Enter a description for the customs tax component in the **Description** field.

## Define a claim percentage

1.  Click **Claim percentage** to set up the claim percentage in the **Claim percentage** form.

2.  Press CTRL+N to create a new line on the **Overview** tab.

3.  Enter the starting and ending dates of validity for the excise claim percentage in the **From date** and the **To date** fields.

4.  Select the RG register to define the claim percentage in the **RG Register** field. The options are:
    
      - **RG23A** – RG register for noncapital purchases
    
      - **RG23C** – RG register for capital purchases

5.  Enter the recoverable percentage for the RG register in the **Percentage** field.

6.  Close the **Claim percentage** form to return to the **Tax components** form.

## Define a tax setoff rule


> [!NOTE]
> <P>You do not need to define the setoff rule for a customs tax component.</P>



1.  Click **Tax setoff rule** to open the **Tax setoff rule** form to define the setoff components to set off the tax liability for a specific customs tax component.

2.  Press CTRL+N to create a new line on the **Overview** tab.

3.  Select the tax component that the original customs tax component is set off against in the **Setoff component** field.
    

    > [!NOTE]
    > <P>The original customs tax component that the setoff components are defined for is displayed in the <STRONG>Tax component</STRONG> field on the <STRONG>General</STRONG> tab,</P>



4.  Click **Up** or **Down** to change the priority order of setoff components that are defined to set off the tax amount for the customs tax component. The priority is displayed in the **Column** field.

5.  Press CTRL+S or close the form.

## See also

[(IND) Tax components (form)](https://technet.microsoft.com/library/jj664734\(v=ax.60\))

[(IND) Claim percentage (form)](https://technet.microsoft.com/library/jj710873\(v=ax.60\))

[(IND) Tax setoff rule (form)](https://technet.microsoft.com/library/jj677818\(v=ax.60\))

  


