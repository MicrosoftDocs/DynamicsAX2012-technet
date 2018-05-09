---
title: Set up prerequisites for quality orders
TOCTitle: Set up prerequisites for quality orders
ms:assetid: 4056385d-8703-49d5-b72d-f1292f2fb8a6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231353(v=AX.60)
ms:contentKeyID: 42518513
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- set up quality orders
---

# Set up prerequisites for quality orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the basic steps that you must follow to set up prerequisites so that you can use quality orders.

## Set up and use prerequisites for quality orders

To set up and use quality orders, follow these steps.

1.  Define the inventory parameters that are related to quality orders.
    
    In the **Inventory and warehouse management parameters** form, follow these steps:
    
    1.  Click the **Quality management** link, and then select the **Use quality management** check box.
    
    2.  Click **Report setup** to define the type of document that is printed on the certificate of analysis that is associated with a quality order.
        

        > [!TIP]
        > <P>You can define more than one record to print different document types on a report, or to print internal and external notes. It is generally helpful to use the <STRONG>Document types</STRONG> form to define a unique document type for the certificate of analysis. For example, if you enter notes on a certificate of analysis by using a unique document type, you must specify this document type in the report options.</P>
        > <UL>
        > <LI>
        > <P>Click <STRONG>Organization administration</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Document management</STRONG> &gt; <STRONG>Document types</STRONG>.</P></LI></UL>

    
    3.  Click the **Number sequences** link, and then select a number sequence code for the quality order and for the certificate of analysis.

2.  Define the units of measure that are used for quantitative tests.
    
    1.  Click **Organization administration** \> **Setup** \> **Units** \> **Units**.
    
    2.  Click **New** to create a new unit of measure.
    
    The unit of measure defines units of measure and the decimal precision for those units. The unit of measure and decimal precision apply to the acceptable values for test measurements and to the reporting of test results for quantitative tests.

3.  Define the basic information for tests.
    
    1.  Click **Inventory management** \> **Setup** \> **Quality control** \> **Test instruments**.
        
        In the **Test instruments** form, define the information about test instruments that are used in tests. This information is optional.
    
    2.  Click **Inventory management** \> **Setup** \> **Quality control** \> **Tests**.
        
        In the **Tests** form, define each quantitative test, and assign a unit of measure for testing. You can also specify the test instrument for the test.
        
        Additionally, in the **Tests** form, define each qualitative test.
    
    3.  Click **Inventory management** \> **Setup** \> **Quality control** \> **Test variables**.
        
        In the **Test variables** form, and in the **Test variable outcomes** form that opens from the **Test variables** form, define additional information about each test variable for inspection during a qualitative test.
    
    4.  Click **Inventory management** \> **Setup** \> **Quality control** \> **Test groups**.
        
        In the **Test groups** form, link a qualitative test to the test variable for inspection.
    
    5.  Click **Inventory management** \> **Setup** \> **Quality control** \> **Item sampling**.
        
        In the **Item sampling** form, define the various sampling plans. A sampling plan calculates the test quantity for a quality order.

4.  Assign tests to a test group, and complete the definition of test information.
    
      - Click **Inventory management** \> **Setup** \> **Quality control** \> **Test groups**.
        
        In the **Test groups** form, define an identifier for each group of tests. Assign a sampling plan and the acceptable quality level (AQL) to the test group, and specify whether the tests in the group require destructive testing.
        
        Additionally, in the **Test groups** form, assign one or more tests to the test group. When you assign an individual test to a test group, you define additional information, such as the sequence, the acceptable measurement values for a quantitative test, the test variable and default outcome for a qualitative test, the documents, and the validity dates.
    
    The test group that is assigned to a quality order provides the primary basis on which tests must be performed on the specified item. Tests can be added, deleted, or changed on the quality order. Test results are reported for each test on a quality order.

5.  Define quality groups, and assign items to a quality group.
    
    1.  Click **Inventory management** \> **Setup** \> **Quality control** \> **Quality groups**.
        
        In the **Quality groups** form, define quality groups.
    
    2.  Click **Inventory management** \> **Setup** \> **Quality control** \> **Item quality groups**.
        
        In the **Item quality groups** form, assign items to a quality group.
        
        The system generates quality orders based on the information in the **Quality associations** form. You can use quality groups to define how the system generates quality orders for a group of items.

6.  Define the quality guidelines that the system follows to generate quality orders.
    
      - Click **Inventory management** \> **Setup** \> **Quality control** \> **Quality associations**.
        
        In the **Quality associations** form, define the events and conditions that cause the system to generate quality orders.


> [!NOTE]
> <P>Additional steps are required if you want to use nonconformance in the quality inspections.</P>



## See also

[About system-generated quality orders](about-system-generated-quality-orders.md)

[About nonconformance](about-nonconformance.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

