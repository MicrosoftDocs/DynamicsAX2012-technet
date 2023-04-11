---
title: Set up info codes (Retail essentials)
TOCTitle: Set up info codes (Retail essentials)
ms:assetid: 81cb357d-757a-466d-ae0c-dc9f2d7646d5
ms:mtpsurl: https://technet.microsoft.com/library/Dn736910(v=AX.60)
ms:contentKeyID: 62200464
author: tonyafehr
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Set up info codes (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up info codes that prompt the cashier to take some action or capture information at the point of sale. For example, you can use info codes to do the following:

  - Get additional information about a transaction, such as the reason for a return. If one of the reasons is “Damaged,” selecting it could assign the returned item to a specific location in inventory.

  - Prompt the cashier to select from a list of prices for specific products.

  - Prompt the cashier to upsell a product when another product is purchased.

  - Prompt the cashier to select from a list of reasons when they open the cash drawer without performing a transaction.

To set up info codes, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Info codes**.

2.  In the **Info codes** form, click **New** to create a new info code.

3.  In the **Info code number** field, enter a unique identifier for the info code, and then enter a description.

4.  In the **Prompt** field, enter the text that is displayed on the point-of-sale (POS) register to prompt the cashier.

5.  In the **Input type** field, select the type of input that the cashier must enter in response to the prompt. For example, **Input type** is set to **Text**, but the cashier enters a numeric value. In this case, the cashier receives an error message. The **Input type** field is used to validate the data that is entered by the cashier, or to trigger a subcode.

6.  On the **General** FastTab, set the following options:
    
      - **Input required** – Select whether the cashier is required to enter a response to the prompt, and whether more than one response is required for each transaction.
    
      - **Once per transaction** – Select whether the cashier should only receive one prompt regarding the selected info code per transaction.
    
      - **Linked info code** – If two info codes are required for a product, select an existing info code to associate with this info code.
    
      - **Values** – Set the minimum or maximum numeric value that the cashier can enter in response to the prompt. You can also set a minimum or maximum number of characters for info codes that require text input.
    
      - **Frequency percent** – Set the frequency that the prompt appears. For example, you want the cashier to ask for the customer’s ZIP code or postal code before the start of every transaction. In this case, set **Frequency percent** to **100**.
    
      - **Use for counting** – Select this check box if the info code can be used for counting.

7.  Click the **Printing** FastTab to select the info code data that is printed on the register receipt.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Set up subcodes for info codes (Retail essentials)](set-up-subcodes-for-info-codes-retail-essentials.md)

  


