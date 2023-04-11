---
title: (BRA) Set up a custom check layout for a bank
TOCTitle: (BRA) Set up a custom check layout for a bank
ms:assetid: 61457475-101e-4b8b-9ced-6b2ee6bc25bf
ms:mtpsurl: https://technet.microsoft.com/library/JJ911253(v=AX.60)
ms:contentKeyID: 53382668
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up a custom check layout for a bank 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up custom check layouts to print checks. You can then attach a custom check layout to a bank account. You can create different check layouts for different banks in Brazil.

1.  Click **Cash and bank management** \> **Setup** \> **Custom check layout**.

2.  In the **Custom check layout** field, enter an identification code for the custom check layout. In the **Description** field, enter a description for the layout.

3.  In the **Report name** field, enter the name of the report for the custom check layout.

4.  Close the form.

5.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

6.  Select or create a bank account. For more information, see [Bank accounts (form)](https://technet.microsoft.com/library/aa587660\(v=ax.60\)).

7.  On the **Action Pane**, click the **Set up** tab, and then click **Check** to open the **Check layout** form.

8.  In the **Check number method** field, select one of the following options to indicate the method to use to generate check numbers:
    
      - **Free** – Check numbers are automatically generated when you use checks for payment. You can use this method when you do not have preprinted checks.
    
      - **Fixed** – Check numbers are generated based on the fixed check numbers that you set up for the bank account in the **Creation of check** form. For more information, see [Creation of check (form)](https://technet.microsoft.com/library/aa575849\(v=ax.60\)). You can use this method when you have preprinted checks.

9.  In the **Check form** field, select **Brazilian check format**.

10. In the **Custom check layout** field, select the identification code of the custom check layout for the bank account.
    

    > [!NOTE]
    > <P>This field is available only when you select <STRONG>Brazilian check format</STRONG> in the <STRONG>Check form</STRONG> field.</P>



11. In the **Paper length** field, specify the length of the paper that is used to print the check.

You can click **Print test** to open the **Check layout - print test** form, where you can create a test printout of the check to verify the layout.

## See also

[(BRA) Check layout (modified form)](https://technet.microsoft.com/library/jj911263\(v=ax.60\))

[(BRA) Custom check layout (form)](https://technet.microsoft.com/library/jj923393\(v=ax.60\))

[Set up the check layout for a bank account](set-up-the-check-layout-for-a-bank-account.md)

  


