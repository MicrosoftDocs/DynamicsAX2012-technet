---
title: (IND) Set up duty drawback (DBK) rates and values
TOCTitle: (IND) Set up duty drawback (DBK) rates and values
ms:assetid: 08cbb79a-c114-4217-8a06-6b9b912095f9
ms:mtpsurl: https://technet.microsoft.com/library/JJ664461(v=AX.60)
ms:contentKeyID: 49385540
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- DBK rates
- DBK values
audience: Application User
ms.search.region: India
---

# (IND) Set up duty drawback (DBK) rates and values 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Create or update the duty drawback rates and values for a product group by specifying the tariff, CENVAT, value cap, and rounding details. Items that are assigned to the product groups use the duty drawback rates and values that you define to calculate the duty drawback amount.

You must create a product group before you can create duty drawback rates and values. For more information about how to create a product group, see [(IND) Create a product group for SION and assign products to the group](ind-create-a-product-group-for-sion-and-assign-products-to-the-group.md).


> [!NOTE]
> <P>You cannot delete a duty drawback value that is linked to a transaction.</P>



1.  Click **General ledger** \> **Setup** \> **EXIM** \> **Duty drawback rates**.
    

    > [!NOTE]
    > <P>This form is available only if you select the <STRONG>Duty drawback</STRONG> check box in the <STRONG>DBK</STRONG> area in the <STRONG>Incentive scheme parameters</STRONG> form.</P>



2.  In the **Duty drawback rates** form, click **New** to create a new duty drawback rate, or select an existing duty drawback rate in the list.

3.  In the **Product group** field, select the product group for which to set up duty drawback rates. The **Description** field is updated with the description of the selected product group.

4.  Click the **Values** button.

5.  In the **Duty drawback values** form, click **New** to create a new duty drawback value.

6.  In the **Start date/time** and **End date/time** fields, select the start and end dates and times for which the drawback rate is effective.

7.  In the **Drawback rate** field, enter the rate that is used to calculate the duty drawback amount.

8.  In the **Value cap** field, enter the drawback value cap per unit that is used to calculate the duty drawback amount.
    

    > [!NOTE]
    > <P>If you have already specified a value cap amount for a combination of a tariff code, CENVAT status, rate type, and date range, you cannot specify a different value cap.</P>



9.  In the **Unit** field, select the unit of measure that is used to calculate the drawback amount.

10. In the **Tariff code** field, select the customs tariff code for which the drawback rate value is defined.
    

    > [!NOTE]
    > <P>You can select the tariff codes only for tariffs for which the <STRONG>Direction</STRONG> field is set to <STRONG>Export</STRONG> in the <STRONG>Customs tariff codes</STRONG> form.</P>



11. In the **CENVAT status** field, select whether the drawback rate value applies to manufacturers based on their CENVAT credit status.
    
    Select from the following options:
    
      - **Availed** – The drawback rate value applies to manufacturers who have taken advantage of the CENVAT credit.
    
      - **Not availed** – The drawback rate value applies to manufacturers who have not taken advantage of the CENVAT credit.

12. In the **Rate type** field, select the type of duty drawback rate.
    
    Select from the following options:
    
      - **All industry rate** – The rate applies to various product categories as a percentage of the Free On Board (FOB) price of the exported products. A value cap is applied to certain product categories.
    
      - **Brand rate** – The rate applies only to special products.
    
      - **Special brand rate** – The rate applies to products when the actual duty that is paid on the input goods is more than the All Industry Rate that is fixed for the product.

13. In the **Round-off** field, enter the lowest unit that is used to round the duty drawback amount.

14. In the **Rounding form** field, select the method that is used to round the duty drawback amount.
    
    Select from the following options:
    
      - **Normal** – Round the duty drawback amount up or down to the nearest amount, depending on whether the amount is more than or less than .50.
    
      - **Downward** – Round the duty drawback amount down to the next lowest amount.
    
      - **Rounding-up** – Round the duty drawback amount up to the next highest amount.

## See also

[(IND) About EXIM duty drawback (DBK) incentive schemes](ind-about-exim-duty-drawback-dbk-incentive-schemes.md)

[(IND) Duty drawback rates (form)](https://technet.microsoft.com/library/jj710927\(v=ax.60\))

[(IND) Duty drawback values (form)](https://technet.microsoft.com/library/jj664528\(v=ax.60\))

  


