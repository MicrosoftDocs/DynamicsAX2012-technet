---
title: Create Commerce Runtime Workflows
TOCTitle: Create Commerce Runtime Workflows
ms:assetid: 8e77e897-be62-4e1a-80c4-0d33f0183c15
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ916618(v=AX.60)
ms:contentKeyID: 50934008
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Create Commerce Runtime Workflows 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The commerce runtime includes workflow business logic that enforces rules for your business. For example, after a customer places an order, you could use workflow to make sure there is sufficient quantity available, validate the tax calculation, check for credit approval, and then place the order. You can use the workflows that are included in commerce runtime or create your own.

A service encapsulates operations to accomplish one atomic task, while workflow accomplishes a set of tasks. A workflow contains a set of steps that calls into one or more services.

## Creating a Workflow

Just like services, workflow uses the request and response pattern. The request object inherits from the base commerce runtime [Request](request-class-microsoft-dynamics-commerce-runtime-messages.md) class. The response object inherits from the base commerce runtime [Response](response-class-microsoft-dynamics-commerce-runtime-messages.md) class. A workflow also has a request handler class that extends the [WorkflowRequestHandler\<TRequest, TResponse\>](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md) class. To create a workflow, you create a request class and a response class, and then create a request handler class that contains the business logic for your workflow.

### To create a request

  - Create a class that inherits from the base commerce runtime [Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)class, and create any incoming parameters that you need for your workflow. The following example shows the GetPromotionsRequest class from the Promotions workflow:
    
        namespace Extensions.Promotions.Workflow
        {
            using Microsoft.Dynamics.Commerce.Runtime.Messages;
        
            /// <summary>
            /// Request Object for the PromotionsWorkFlowRequestHandler class.
            /// </summary>
            public class GetPromotionsRequest : Request
            {
                /// <summary>
                /// Initializes a new instance of the <see cref="GetPromotionsRequest"/> class.
                /// </summary>
                public GetPromotionsRequest()
                {
                }
        
                /// <summary>
                /// Gets or sets the channel identifier.
                /// </summary>
                public long ChannelId { get; set; }
        
                /// <summary>
                /// Gets or sets the catalog identifier.
                /// </summary>
                public long CatalogId { get; set; }
        
                /// <summary>
                /// Gets or sets a value indicating whether to get the summarized data set.
                /// </summary>
                public bool HasPromotionData { get; set; }
            }
        }

### To create a response

  - Create a class that inherits from the base commerce runtime [Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)class. The following example shows the GetPromotionsResponse class from the Promotions workflow:
    
        namespace Extensions.Promotions.Workflow
        {
            using System.Collections.Generic;
            using System.Collections.ObjectModel;
            using Extensions.Promotions.Data;
            using Microsoft.Dynamics.Commerce.Runtime;
            using Microsoft.Dynamics.Commerce.Runtime.Messages;
            
            /// <summary>
            /// Creates the response object for the Workflow.
            /// </summary>
            public class GetPromotionsResponse : Response
            {
                /// <summary>
                /// Initializes a new instance of the <see cref="GetPromotionsResponse"/> class.
                /// </summary>
                /// <param name="promotions">The summerized promotions.</param>
                public GetPromotionsResponse(IEnumerable<ChannelPromotionsSummarizedData> promotions)
                {
                    this.SummarizedPromotions = promotions.AsReadOnly();
                }
        
                /// <summary>
                /// Initializes a new instance of the <see cref="GetPromotionsResponse"/> class.
                /// </summary>
                /// <param name="promotions">The promotions.</param>
                public GetPromotionsResponse(IEnumerable<PromotionDetails> promotions)
                {
                    this.Promotions = promotions.AsReadOnly();
                }
        
                /// <summary>
                /// Gets all the summarized channel promotions.
                /// </summary>
                public ReadOnlyCollection<ChannelPromotionsSummarizedData> SummarizedPromotions { get; private set; }
                
                /// <summary>
                /// Gets non-summarized channel promotions.
                /// </summary>
                public ReadOnlyCollection<PromotionDetails> Promotions { get; private set; }
            }
        }

### To create a request handler

  - Create a class that inherits from the base commerce runtime [WorkflowRequestHandler\<TRequest, TResponse\>](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md) class. The following example shows the GetPromotionsResponse class from the Promotions workflow:
    
        namespace Extensions.Promotions.Workflow
        {
            using System;
            using System.Collections.Generic;
            using System.Linq;
            using Extensions.Promotions.Data;
            using Extensions.Promotions.Service;
            using Microsoft.Dynamics.Commerce.Runtime.DataModel;
            using Microsoft.Dynamics.Commerce.Runtime.Workflow;
            using Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition;
        
            /// <summary>
            /// Helper Class to call neccessary Services and perform Data Manipulation on it.
            /// </summary>
            [RequestHandlerMetadata(HandledRequestType = typeof(GetPromotionsRequest))]
            internal class PromotionsWorkflowRequestHandlerRaw : WorkflowRequestHandler<GetPromotionsRequest, GetPromotionsResponse>
            {
                /// <summary>
                /// Executes the workflow to get the promotions.
                /// </summary>
                /// <param name="request">The request.</param>
                /// <returns>The response.</returns>
                protected override GetPromotionsResponse Process(GetPromotionsRequest request)
                {
                    if (request == null)
                    {
                        throw new ArgumentNullException("request");
                    }
        
                    var serviceRequest = new GetPromotionsServiceRequest(this.Context);
                    IPromotions promotionsService = this.Context.Runtime.GetService<IPromotions>();
                    
                    List<PromotionDetails> response = new List<PromotionDetails>();
                    List<ChannelPromotionsSummarizedData> summarizedResponse = new List<ChannelPromotionsSummarizedData>();
                    serviceRequest.ChannelId = request.ChannelId;
                    serviceRequest.CatalogId = request.CatalogId;
        
                    foreach (PeriodicDiscountOfferType discount in Enum.GetValues(typeof(PeriodicDiscountOfferType)))
                    {
                        serviceRequest.PromotionType = discount;
                        var serviceReply = promotionsService.Execute<GetPromotionsServiceResponse>(serviceRequest).Promotions;
        
                        if (request.HasPromotionData)
                        {
                            summarizedResponse.AddRange(ConvertToSummarizedData(serviceReply, discount));
                        }
                        else
                        {
                            response.AddRange(serviceReply);
                        }
                    }
        
                    if (request.HasPromotionData)
                    {
                        var summarizedResult = from s in summarizedResponse
                                               orderby s.DiscountName
                                               select s;
        
                        return new GetPromotionsResponse(summarizedResult);
                    }
                    else
                    {
                        var result = from s in response
                                     orderby s.DiscountName
                                     select s;
        
                        return new GetPromotionsResponse(result);
                    }
                }
        
                /// <summary>
                /// Iterates through a list of promotions for:
                ///     1. Generating a list of discount codes associated with an Item. This generates duplicate records where the only difference is the discount codes.
                ///     2. Removing above duplicates.
                ///     3. Summarize the Promotion data into English Text for every unique record being considered.
                /// </summary>
                /// <param name="promotionDetailsCollection">List containing promotion details.</param>
                /// <param name="typeOfDiscount">Discount Type associated with the list (eg. MultiBuy/ MixNMatch, etc).</param>
                /// <returns>A collection of summarized promotions.</returns>
                private static List<ChannelPromotionsSummarizedData> ConvertToSummarizedData(IEnumerable<PromotionDetails> promotionDetailsCollection, PeriodicDiscountOfferType typeOfDiscount)
                {
                    var returnObject = new List<ChannelPromotionsSummarizedData>();
        
                    var allDiscountOfferNames = promotionDetailsCollection
                            .Select(i => new { i.DiscountName })
                            .Distinct();
        
                    foreach (var currentOffer in allDiscountOfferNames)
                    {
                        var discountLineItems = from s in promotionDetailsCollection where s.DiscountName == currentOffer.DiscountName orderby s.ItemId select s;
        
                        var lineItemsAfterPass1 = Pass1ConsolidateDiscountCodes(discountLineItems);
                        var lineItemsAfterPass2 = Pass2GenerateSummarizedPromotionStatement(lineItemsAfterPass1, typeOfDiscount);
                        var lineItemsAfterPass3 = Pass3GenerateConsolidatedPromotionStatement(lineItemsAfterPass2, typeOfDiscount);
                        returnObject.AddRange(lineItemsAfterPass3);
                    }
        
                     return returnObject;
                }
        
                /// <summary>
                /// Consolidate all the discount codes available for a discount and then remove redundant line items.
                /// </summary>
                /// <param name="offerCollection">Contains set of all Line Items for a particular discount Offer.</param>
                /// <returns>A collection of promotion details..</returns>
                private static List<PromotionDetails> Pass1ConsolidateDiscountCodes(IEnumerable<PromotionDetails> offerCollection)
                {
                    var returnObject = new List<PromotionDetails>();
                    var element = new PromotionDetails();
                    var iterator = offerCollection.ToList();
        
                    for (int counter = 0; counter < offerCollection.Count(); counter++)
                    {
                        element = iterator.ElementAt(counter);
                        if (element.IsDiscountCodeRequired)
                        {
                            int index = 1;
                            while (counter + index < offerCollection.Count() && iterator.ElementAt(counter + index).ItemId == element.ItemId && iterator.ElementAt(counter + index).IsDiscountCodeRequired == element.IsDiscountCodeRequired)
                            {
                                element.DiscountCode += ", " + iterator.ElementAt(counter + index).DiscountCode;
                                index++;
                            }
        
                            counter += index;
                        }
        
                        returnObject.Add(element);
                    }
        
                    return returnObject;
                }
                
                /// <summary>
                /// Generates a Summarized Promotion Statement for every line item, But its still not usable by the End-User.
                /// </summary>
                /// <param name="offerCollection">Contains set of all Line Items for a particular discount Offer.</param>
                /// <param name="typeOfDiscount">Is it MultiBuy/ Mix-n-Match/ Discount/ Price Adjustment.</param>
                /// <returns>A collection of summarized promotions.</returns>
                private static List<ChannelPromotionsSummarizedData> Pass2GenerateSummarizedPromotionStatement(IEnumerable<PromotionDetails> offerCollection, PeriodicDiscountOfferType typeOfDiscount)
                {
                    var returnObject = new List<ChannelPromotionsSummarizedData>();
                    ChannelPromotionsSummarizedData element;
        
                    foreach (var lineItem in offerCollection)
                    {
                        element = new ChannelPromotionsSummarizedData();
        
                        element.OfferId = lineItem.OfferId;
                        element.DiscountName = lineItem.DiscountName;
                        element.DiscountDescription = lineItem.DiscountDescription;
                        element.Disclaimer = lineItem.Disclaimer;
        
                        element.ProductName = lineItem.ProductName;
                        element.ProductOfferDescription = lineItem.ProductOfferDescription;
                        element.ProductImageLink = lineItem.ProductImageLink;
                        
                        element.IsDiscountCodeRequired = lineItem.IsDiscountCodeRequired;
                        element.DiscountCodes = lineItem.DiscountCode;
        
                        switch (lineItem.DiscountMethod)
                        {
                            case 0: // Percentage Discount
                                if (lineItem.DiscountPercent == 0)
                                {
                                    element.ProductPromotionStatement = String.Empty;
                                }
                                else if (lineItem.DiscountPercent == 100)
                                {
                                    element.ProductPromotionStatement = "Get " + element.ProductName + " for free";
                                }
                                else
                                {
                                    element.ProductPromotionStatement = (typeOfDiscount == PeriodicDiscountOfferType.MultipleBuy) ? "Buy atleast " + Decimal.ToInt32(lineItem.MinimumQuantity) + " and " : String.Empty;
                                    element.ProductPromotionStatement += "Get " + decimal.ToInt32(lineItem.DiscountPercent) + "% Off on all " + lineItem.ProductName + "(s)";
                                }
        
                                break;
                            case 1: // Discount Amount
                                element.ProductPromotionStatement = "Get each " + lineItem.ProductName + " for $" + decimal.Round(lineItem.DiscountAmount, 2, MidpointRounding.AwayFromZero) + " less";
                                break;
                            case 2: // Offer Price
                                element.ProductPromotionStatement = (typeOfDiscount == PeriodicDiscountOfferType.MultipleBuy) ? "Buy atleast " + lineItem.MinimumQuantity + " " : "Buy ";
                                element.ProductPromotionStatement = lineItem.ProductName + "(s) for $" + decimal.Round(lineItem.OfferPrice, 2, MidpointRounding.AwayFromZero) + "each";
                                break;
                            case 3: // Offer Price Inclusive Of Tax
                                bool isDealPrice = ((from s in offerCollection where s.DiscountMethod != 3 select s).Count() == 0) ? true : false;
                                element.ProductPromotionStatement = "Get " + (isDealPrice ? lineItem.DiscountName : lineItem.ProductName) +
                                    " for $" + decimal.Round(lineItem.OfferPriceInclusiveOfTax, 2, MidpointRounding.AwayFromZero) + "(Inclusive of Taxes)";
                                break;
                        }
        
                        returnObject.Add(element);
                    }
        
                    return returnObject;
                }
                
                /// <summary>
                /// Consolidates and converts the Summarized Promotion Statement to an End-User understandable format.
                /// </summary>
                /// <param name="offerCollection">Contains set of all Line Items for a particular discount Offer.</param>
                /// <param name="typeOfDiscount">Is it MultiBuy/ Mix-n-Match/ Discount/ Price Adjustment.</param>
                /// <returns>A collection of summarized promotions.</returns>
                private static List<ChannelPromotionsSummarizedData> Pass3GenerateConsolidatedPromotionStatement(IEnumerable<ChannelPromotionsSummarizedData> offerCollection, PeriodicDiscountOfferType typeOfDiscount)
                {
                    var returnObject = new List<ChannelPromotionsSummarizedData>();
                    var iterator = offerCollection.ToList();
                    
                    string appendText = " when you buy a ";
                    string productStatement = String.Empty;
                    bool appendFlag = false;
        
                    for (int counter = 0; counter < offerCollection.Count(); counter++)
                    {
                        if (string.IsNullOrEmpty(iterator.ElementAt(counter).ProductPromotionStatement))
                        {
                            appendFlag = true;
                            appendText += ((string.Compare(appendText, " when you buy a ", StringComparison.OrdinalIgnoreCase) == 0) ? String.Empty : " and ") + iterator.ElementAt(counter).ProductName;
                        }
        
                        productStatement = (string.IsNullOrEmpty(iterator.ElementAt(counter).ProductPromotionStatement)) ? productStatement : iterator.ElementAt(counter).ProductPromotionStatement;
                    }
        
                    foreach (var lineItem in offerCollection)
                    {
                        lineItem.ProductPromotionStatement = appendFlag ? productStatement + appendText : lineItem.ProductPromotionStatement;
                        returnObject.Add(lineItem);
                    }
        
                    return returnObject;
                }
            }
        }

## Modifying the CRT Configuration File

You cannot customize the workflow that is included with the CRT, but you can replace it with your own custom workflow or you can add additional workflows. The CRT configuration file determines the workflow to load. If you add a new workflow with the same name as a default workflow above the default workflow, the new workflow replaces the default workflow.

### To modify the CRT configuration file

1.  Open commerceRuntime.config in your solution.
    

    > [!NOTE]
    > <P>The location of this file varies based on your deployment. If you are customizing the SharePoint starter store, you can find the file by using the Internet Information Services (IIS) Manager. In IIS Manager, find the starter store under the <STRONG>Sites</STRONG> node. Right-click the public starter store, and then click <STRONG>Explore</STRONG>.</P>



2.  Add a line for your new workflow to the list of assemblies. For example:
    
        <add source="assembly" value="ContosoWorkflow, Version=1.0.0.0, Culture=neutral, PublicKeyToken=6598494e9dab8361, processorArchitecture=MSIL" />

## See also

[Integrate a Service into the Commerce Runtime](integrate-a-service-into-the-commerce-runtime.md)

[Online Store](online-store.md)

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  


