<properties
	pageTitle="Microsoft Azure Subscription and Service Limits, Quotas, and Constraints"
	description="Provides a list of common Azure subscription and service limits, quotas, and constraints. This includes information on how to increase limits along with maximum values."
	services=""
	documentationCenter=""
	authors="rothja"
	manager="jeffreyg"
	editor="mollybos"/>

<tags
	ms.service="multiple"
	ms.workload="multiple"
	ms.tgt_pltfrm="na"
	ms.devlang="na"
	ms.topic="article"
	ms.date="06/25/2015"
	ms.author="jroth"/>

# Azure Subscription and Service Limits, Quotas, and Constraints

## Overview

This document specifies some of the most common Microsoft Azure limits. Note that this does not currently cover all Azure services. Over time, these limits will be expanded and updated to cover more of the platform.

> [AZURE.NOTE] If you want to raise the limit above the **Default Limit**, you can [open an online customer support request at no charge](http://azure.microsoft.com/blog/2014/06/04/azure-limits-quotas-increase-requests/). The limits cannot be raised above the **Maximum Limit** value in the tables below. If there is no **Maximum Limit** column, then the specified resource does not have adjustable limits.

## Limits and the Azure Resource Manager

It is now possible to combine multiple Azure resources in to a single Azure Resource Group. When using Resource Groups, limits that once were global become managed at a regional level with the Azure Resource Manager. For more information about Azure Resource Groups, see [Using resource groups to manage your Azure resources](resource-group-portal.md).

In the limits below, a new table has been added to reflect any differences in limits when using the Azure Resource Manager. For example, there is a **Subscription Limits** table and a **Subscription Limits - Azure Resource Manager** table. When a limit applies to both scenarios, it is only shown in the first table. Unless otherwise indicated, limits are global across all regions.

> [AZURE.NOTE] It is important to emphasize that quotas for resources in Azure Resource Groups are per-region accessible by your subscription, and are not per-subscription, as the service management quotas are. Let's use core quotas as an example. If you need to request a quota increase with support for cores, you need to decide how many cores you want to use in which regions, and then make a specific request for Azure Resource Group core quotas for the amounts and regions that you want. Therefore, if you need to use 30 cores in West Europe to run your application there; you should specifically request 30 cores in West Europe. But you will not have a core quota increase in any other region -- only West Europe will have the 30-core quota. 
<!-- -->
As a result, you may find it useful to consider deciding what your Azure Resource Group quotas need to be for your workload in any one region, and request that amount in each region into which you are considering deployment. See [troubleshooting deployment issues](resource-group-deploy-debug.md##authentication-subscription-role-and-quota-issues) for more help discovering your current quotas for specific regions.

## Subscription Limits

[AZURE.INCLUDE [azure-subscription-limits](../includes/azure-subscription-limits.md)]


## Subscription Limits - Azure Resource Manager 

The following limits apply when using the Azure Resource Manager and Azure Resource Groups. Limits that have not changed with the Azure Resource Manager are not listed below. Please refer to the previous table for those limits.

[AZURE.INCLUDE [azure-subscription-limits-azure-resource-manager](../includes/azure-subscription-limits-azure-resource-manager.md)]


## Resource Group Limits

[AZURE.INCLUDE [azure-resource-groups-limits](../includes/azure-resource-groups-limits.md)]


## Virtual Machines Limits

[AZURE.INCLUDE [azure-virtual-machines-limits](../includes/azure-virtual-machines-limits.md)]


## Virtual Machines Limits - Azure Resource Manager

The following limits apply when using the Azure Resource Manager and Azure Resource Groups. Limits that have not changed with the Azure Resource Manager are not listed below. Please refer to the previous table for those limits.

[AZURE.INCLUDE [azure-virtual-machines-limits-azure-resource-manager](../includes/azure-virtual-machines-limits-azure-resource-manager.md)]


## Networking Limits

[AZURE.INCLUDE [azure-virtual-network-limits](../includes/azure-virtual-network-limits.md)]


## Networking Limits – Azure Resource Manager

The following limits apply when using the Azure Resource Manager and Azure Resource Groups. Limits that have not changed with the Azure Resource Manager are not listed below. Please refer to the previous table for those limits.

[AZURE.INCLUDE [azure-virtual-network-limits-azure-resource-manager](../includes/azure-virtual-network-limits-azure-resource-manager.md)]


## Standard Storage Limits

[AZURE.INCLUDE [azure-storage-limits](../includes/azure-storage-limits.md)]

## Premium Storage Limits

<table cellspacing="0" border="1">
<tr>
   <th align="left" valign="middle">Resource</th>
   <th align="left" valign="middle">Default Limit</th>
</tr>
<tr>
   <td valign="middle"><p>Total Disk capacity per account</p></td>
   <td valign="middle"><p>35 TB</p></td>
</tr>
<tr>
   <td valign="middle"><p>Total Snapshot capacity per account</p></td>
   <td valign="middle"><p>10 TB</p></td>
</tr>
<tr>
   <td valign="middle"><p>Max bandwidth per account (ingress + egress)</p></td>
   <td valign="middle"><p>50 Gbps</p></td>
</tr>
</table>


## Storage Limits - Azure Resource Manager

The following limits apply when using the Azure Resource Manager and Azure Resource Groups. Limits that have not changed with the Azure Resource Manager are not listed below. Please refer to the previous table for those limits.

[AZURE.INCLUDE [azure-storage-limits-azure-resource-manager](../includes/azure-storage-limits-azure-resource-manager.md)]


## Cloud Services Limits

[AZURE.INCLUDE [azure-cloud-services-limits](../includes/azure-cloud-services-limits.md)]


## Web Apps (Websites) Limits

[AZURE.INCLUDE [azure-websites-limits](../includes/azure-websites-limits.md)]


## Batch Preview Limits

[AZURE.INCLUDE [azure-batch-limits](../includes/azure-batch-limits.md)]


## DocumentDB Limits

[AZURE.INCLUDE [azure-documentdb-limits](../includes/azure-documentdb-limits.md)]


## Mobile Engagement Limits

[AZURE.INCLUDE [azure-mobile-engagement-limits](../includes/azure-mobile-engagement-limits.md)]


## SQL Database Limits

[AZURE.INCLUDE [azure-sql-database-limits](../includes/azure-sql-database-limits.md)]


## Media Services Limits

[AZURE.INCLUDE [azure-mediaservices-limits](../includes/azure-mediaservices-limits.md)]


## Service Bus Limits

[AZURE.INCLUDE [azure-servicebus-limits](../includes/azure-servicebus-limits.md)]


## Active Directory Limits

[AZURE.INCLUDE [azure-active-directory-limits](../includes/azure-active-directory-limits.md)]


## RemoteApp Limits

[AZURE.INCLUDE [azure-remoteapp-limits](../includes/azure-remoteapp-limits.md)]

## StorSimple System Limits

[AZURE.INCLUDE [storsimple-limits-table](../includes/storsimple-limits-table.md)]
 
## See Also

[Understanding Azure Limits and Increases](http://azure.microsoft.com/blog/2014/06/04/azure-limits-quotas-increase-requests/)

[Virtual Machine and Cloud Service Sizes for Azure](http://msdn.microsoft.com/library/azure/dn197896.aspx)

