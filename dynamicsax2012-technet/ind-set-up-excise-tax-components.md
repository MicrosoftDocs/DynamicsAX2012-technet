---
title: (IND) Set up excise tax components
TOCTitle: (IND) Set up excise tax components
ms:assetid: 42176eeb-14a2-4ab0-9a33-13973a269c19
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664647(v=AX.60)
ms:contentKeyID: 49385724
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Set up excise tax components 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Use the **Tax components** form to define the components for excise duty and set up the excise claim percentage. You can use the excise credit earned in a purchase transaction to offset the excise liability that is incurred from the sale of goods.

The amount of credit that can be offset is different for capital purchases and for noncapital purchases. For capital purchases, the declared percentage of the credit earned is deferred to the next financial year and you can use the remaining amount in the current financial year. For noncapital goods, the whole amount of excise credit earned is available to offset the excise liability in the current financial year.

You must also define tax setoff, which will offset the amounts of the various components of the excise duty in the excise payable account with the amounts in the recoverable accounts of the tax components, regardless of the tax type.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax components**.

2.  Select **Excise** in the **Tax type** field.

3.  Press CTRL+N to create a new line in the lower pane of the window.

4.  Define the tax component for the excise tax type in the **Tax component** field.

5.  Enter the description for the tax component in the **Description** field.

6.  Click **Claim percentage** to open the **Claim percentage** form.

7.  Enter the starting date of the period for making the excise claim in the **From date** field.

8.  Enter the ending date of the period for making the excise claim in the **To date** field.

9.  Select the RG register in the **RG Register** field from the following options:
    
      - **RG23A** – For noncapital purchases
    
      - **RG23C** – For capital purchases
    

    > [!NOTE]
    > <P>According to the legal requirement, the claim percentage is defined as <STRONG>50%</STRONG> for RG23C and <STRONG>100%</STRONG> for RG23A.</P>



10. Specify the percentage of the earned credit that must be used in the current financial year in the **Percentage** field. The remaining percentage of amount will be deferred to the next financial year.

11. Press CTRL+S or close the form.

12. Click **Tax setoff rule** in the **Tax components** form to open the **Tax setoff rule** form.

13. Enter the order of priority for the tax component used to set off the original excise duty component in the **Column** field.

14. Select an appropriate tax component in the **Setoff component** field to offset the original excise duty component.

## See also

[(IND) Tax components (form)](https://technet.microsoft.com/en-us/library/jj664734\(v=ax.60\))

[(IND) Claim percentage (form)](https://technet.microsoft.com/en-us/library/jj710873\(v=ax.60\))

[(IND) Tax setoff rule (form)](https://technet.microsoft.com/en-us/library/jj677818\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

