---
title: Set up info codes
TOCTitle: Set up info codes
ms:assetid: 8635d420-09dd-47ae-b746-0d29a3bddfba
ms:mtpsurl: https://technet.microsoft.com/library/Hh597158(v=AX.60)
ms:contentKeyID: 39519215
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up info codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to set up info codes to use to capture data at the point of sale when a cashier performs various actions, such as product sales, product returns, or customer selections. By using info codes, you can track data such as the customer’s ZIP code or postal code or the reason that a product was returned.

You can also link subcodes to info codes. Subcodes provide the possible responses that cashiers at registers can select as they perform a specific activity. For example, when a customer purchases a product that requires batteries, you want the cashier to ask whether the customer wants to purchase batteries. If you add a subcode, the cashier can select the customer’s response so that it can be tracked.

In Microsoft Dynamics AX 2012 R3, you can group info codes together so that you can easily reuse them. You can also specify the order in which they are displayed to the user without manually creating dependencies between info codes.


> [!NOTE]
> <P>In versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3, info codes in Retail were called reason codes. This topic refers to info codes, but the information also pertains to Retail reason codes in earlier versions of AX 2012, unless otherwise indicated.</P>



To set up info codes, follow these steps:

1.  Click **Retail** \> **Setup** \> **Info codes**.

2.  In the **Info codes** form, click **New** to create a new info code.

3.  In the **Info code number** field, enter a unique identifier for the info code, and then enter a description.

4.  In the **Prompt** field, enter the text that is displayed on the point of sale (POS) register to prompt the cashier to enter an info code.

5.  In the **Input type** field, select the type of input that the cashier must enter in response to the prompt. For example, if the **Input type** field is set to **Text**, the cashier must enter text. If the cashier enters a numeric value, an error message is displayed. The **Input type** field is used to validate the data that is entered by the cashier, or to trigger a subcode.

6.  On the **General** FastTab, set the following options:
    
      - **Input** – Select whether the cashier is required to enter a response to the prompt for an info code, and the frequency of that input. For example, the cashier must enter a response to the prompt for every transaction, or only for certain types of transactions.
    
      - **Linked info code** – If two info codes are required for a product, select an existing info code to associate with this info code.
        

        > [!NOTE]
        > <P>In AX 2012 R3 with Retail: You can link an info code to an info code group. This can trigger a set of info codes that are displayed in the order that is specified in the info code group.</P>
        > <P>For more information about how to set up info code groups, see <A href="set-up-info-code-groups.md">Set up info code groups</A>.</P>

    
      - **Values** – Set the minimum or maximum numeric value that the cashier can enter in response to the prompt for an info code. You can also set a minimum or maximum number of characters for info codes that require text input.
    
      - **Frequency percent** – Set how frequently the prompt for an info code will appear. For example, if you want the cashier to ask for the customer’s ZIP Code or postal code before the start of every transaction, set **Frequency percent** to **100**.
    
      - **Use for counting** – Select the check box if the info code can be used for inventory counting.

7.  On the **Printing** FastTab, select the info code data to be printed on the register receipt.

8.  In AX 2012 R3 with Retail: Click **Translations**. In the **Text translation** form, enter the translated text for info codes in additional languages. The translated text is displayed on the register at the point of sale.

## See also

[Set up subcodes](set-up-subcodes.md)

[Info codes (form) (Retail)](https://technet.microsoft.com/library/hh580638\(v=ax.60\))

[Set up info code groups](set-up-info-code-groups.md)

  


