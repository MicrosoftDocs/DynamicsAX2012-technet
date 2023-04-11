---
title: Enroll and remove benefits for workers
TOCTitle: Enroll and remove benefits for workers
ms:assetid: 38c5702d-35a6-4619-a7eb-ab894add5b42
ms:mtpsurl: https://technet.microsoft.com/library/Hh242207(v=AX.60)
ms:contentKeyID: 36056627
author: tonyafehr
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- benefits
- benefit
- benefit enrollment
audience: Application User
ms.search.region: Global
---

# Enroll and remove benefits for workers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can enroll and remove workers from benefit plans and specify the dates when a worker is eligible for benefits. You can also maintain dependent coverage and beneficiary designations for benefits that a worker is enrolled in.


> [!NOTE]
> <UL>
> <LI>
> <P>The benefit plan must be set up before you can enroll workers in it.</P>
> <LI>
> <P>If Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed, the worker’s eligibility for a benefit must be determined before you can enroll the worker. For more information, see <A href="key-tasks-determine-benefit-eligibility.md">Key tasks: Determine benefit eligibility</A>.</P>
> <LI>
> <P>If the <STRONG>Payroll - USA</STRONG> configuration key is selected, many benefits affect payroll calculations. These benefits require that deductions and contributions be set up for each worker who is enrolled in the benefit. After you enroll a worker in a benefit that affects payroll calculations, see <A href="worker-and-position-payroll-tasks.md">Worker and position payroll tasks</A> for information about how to set up payroll information for the worker.</P>
> <LI>
> <P>To enroll a worker in a garnishment or tax levy, see <A href="garnishment-and-tax-levy-enrollment-tasks.md">Garnishment and tax levy enrollment tasks</A>.</P></LI></UL>



## Enroll a worker in benefits

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker, and then click **Personal information**.

3.  Click **Benefits**.

4.  Click **Add**.

5.  Select the benefit.
    

    > [!NOTE]
    > <P>After you select a benefit plan and option, the benefit type that is associated with the plan appears in the <STRONG>Type</STRONG> field.</P>



6.  Depending on the version that you are using, do one of the following:
    
      - In versions prior to Microsoft Dynamics AX 2012 R2, in the **Enrollment start** and **Enrollment end** fields, enter the first and last date that the benefit is available to the worker.
    
      - In Microsoft Dynamics AX 2012 R2 or AX 2012 R3, in the **Coverage start date** and **Coverage end date** fields, enter the first and last date that the benefit is available to the worker.
    

    > [!NOTE]
    > <P>The default starting date is either the current date or the effective date of the selected benefit, whichever is later. The default ending date is the expiration date of the benefit option.</P>



7.  To add a dependent:
    
    1.  In the **Dependents** area, select the dependent, and then click **Edit**.
    
    2.  Select the **Covered** check box to indicate that the dependent is covered by the benefit plan, and then click **OK**.
    

    > [!NOTE]
    > <P>Only one spouse or domestic partner can be covered as a dependent under a benefit plan.</P>

    
    For more information about how to add dependents, see [Maintain information for dependents and beneficiaries](maintain-information-for-dependents-and-beneficiaries.md).

8.  To add a beneficiary:
    
    1.  In the **Beneficiaries** area, select the beneficiary, and then click **Edit**. For more information about how to add beneficiaries, see [Maintain information for dependents and beneficiaries](maintain-information-for-dependents-and-beneficiaries.md).
    
    2.  In the **Designated** column, select either **Primary** or **Contingent**.
    
    3.  Type the percentage of the benefit to designate to the beneficiary. All primary designations and contingent designations must equal 100 percent. For example, a single primary designation would be set to 100 percent, and a contingent designation that is divided equally among three beneficiaries would have the following values: 33.33%, 33.33%, and 33.34%.
    
    4.  Click **OK**.

9.  Optional: To view or change the effective dates for a benefit, select the benefit, and then click **Maintain versions**.

## Remove beneficiaries or dependents from a benefit that is assigned to a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker, click **Personal information**, and then click **Benefits**.

3.  Select the benefit to remove the dependent or beneficiary from.

4.  In the **Dependents** or **Beneficiaries** area, click **Edit**.

5.  To remove a dependent, clear the **Covered** check box next to the dependent. To remove a beneficiary, select the **Not designated** check box next to the beneficiary.

6.  Click **OK**.

## See also

[Set up benefits](set-up-benefits.md)

[Maintain benefits (form)](https://technet.microsoft.com/library/hh209235\(v=ax.60\))

[Maintain information for dependents and beneficiaries](maintain-information-for-dependents-and-beneficiaries.md)

  


