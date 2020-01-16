---
title: About billing code rate scripts (Public sector)
TOCTitle: About billing code rate scripts (Public sector)
ms:assetid: f9b1b4e5-e8dd-4fe7-8364-13dcaad266b1
ms:mtpsurl: https://technet.microsoft.com/library/Hh208611(v=AX.60)
ms:contentKeyID: 36056403
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- public sector
- billing code
- calculate rates
- public sector billing code rate scripts
- rate scripts
audience: Application User
ms.search.region: Denmark, France
---

# About billing code rate scripts (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A billing code is a set of default values and billing rates that are applied automatically to free text invoice lines where the billing code is selected. One of these default values is the billing amount for the invoice line. This billing amount can be derived from one of two locations in the billing code setup: the currency table or the rate script field. The following examples provide rate scripts for typical billing situations.


> [!NOTE]
> <P>Billing code rate scripts must be written in the C Sharp or Visual Basic programming language.</P>



## Examples: C Sharp

**Example 1 – Surcharge for a specified group of customers:** The following example applies a labor cost with a ten percent surcharge for “BUS” group customers.  It also applies an overweight parts charge if the weight is over 100, and then takes a five percent discount off the total for “SENIOR” group customers. 

    decimal LaborCost = 10.0m;
    decimal BusinessLaborFactor = 1.10m;
    decimal PartsCost = 15.5m;
    decimal DiscountRate = 0.05m;
    decimal Discount;
    
    if (InvoiceCustomer.CustGroup == "BUS")
    {
        AddAmount("Labor cost:", LaborCost * BusinessLaborFactor); 
    }
    else
    {
        AddAmount("Labor cost:", LaborCost);
    }
    
    if (InvoiceLine.Weight > 100)
    {
        AddAmount("Overweight parts cost:", PartsCost);
    }
    
    if (InvoiceCustomer.CustGroup == "SENIOR")
    {
        Discount = Amount * DiscountRate;
        AddAmount("Senior discount:", -Discount);
    }
    
    AddTotalLine();

**Example 2 - Fixed amount by currency code:** The following example functions like the currency table in the billing code setup. It specifies a different fixed amount for each currency code.

    if (Invoice.CurrencyCode == "EUR")
    {
        AddAmount("Fixed rate (EUR)", 10);
    }
    if (Invoice.CurrencyCode == "USD")
    {
        AddAmount("Fixed rate (USD)", 15);
    }
    if (Invoice.CurrencyCode == "CAD") 
    {
        AddAmount("Fixed rate (CAD)", 16);
    }
    if (Invoice.CurrencyCode == "DKK")
    {
        AddAmount("Fixed rate (DKK)", 75);
    }

## Examples: Visual Basic

**Example 1 – A base fee with an additional charge for specific customers:** The following example applies a base fee for all customers and adds a usage fee for a specific customers.

    Dim WaterBaseFee As Decimal = 20.0
    Dim WaterUsedFee As Decimal = 150.5
    
    If InvoiceCustomer.AccountNum = "4000" Then
        AddAmount("Water base fee added:", WaterBaseFee)
        AddAmount("Water used fee added:", WaterUsedFee)
    Else
        AddAmount("Water base fee added:", WaterBaseFee)
    End If
    
    AddTotalLine()

**Example 2 – A base service fee with a calculated fee assigned to specified customer groups:** The following example calculates the standard amount for a service and applies a rate factor based on the customer group.

    Dim SewerBaseFee As Decimal = 20.0
    Dim SewerServiceFee As Decimal = 12.5
    Dim StormDrainFee As Decimal = 17.8
    Dim AreaAMultiplier As Decimal = 0.50
    Dim AreaBMultiplier As Decimal = 1.0
    Dim AreaCMultiplier As Decimal = 1.5
    
    Amount = SewerBaseFee + SewerServiceFee + StormDrainFee
    
    If (Customer.CustGroup = "40") Then
        Amount = Amount + Amount * AreaAMultiplier
    End If
    
    If (Customer.CustGroup = "50") Then
        Amount = Amount + Amount * AreaBMultiplier
    End If
    
    If (Customer.CustGroup = "60") Then
        Amount = Amount + Amount * AreaCMultiplier
    End If

## See also

[Billing codes (form) (Public sector)](https://technet.microsoft.com/library/hh208543\(v=ax.60\))

[Set up billing codes (Public sector)](set-up-billing-codes-public-sector.md)

  


