# Module 1: Getting started with Microsoft Azure

# Lab: Using the Azure portals

## Table of Contents

- [Overview](#overview)

- [Pre-requisites](#pre-requisites) 

- [Exercise 1: Customizing the Azure portal interface](#exercise-1-Customizing-the-Azure-portal-interface)
    - [Task 1: Connect to the Azure portal](#Task-1-Connect-to-the-Azure-portal)
    - [Task 2: Explore and customize the Azure portal interface](#Task-2-Explore-and-customize-the-Azure-portal-interface)   
- [Exercise 2: Viewing billing, usage, and quotas data](#Exercise-2-Viewing-billing-usage-and-quotas-data)
    - [Task 1: View resource cost and usage in the Azure portal](#Task1-View-resource-cost-and-usage-in-the-Azure-portal)
    - [Task 2: View billing data in the Azure Account Center](#Task-2-View-billing-data-in-the-Azure-Account-Center)
    - [Task 3: Prepare for the next module](#Task-3-Prepare-for-the-next-module)

## Overview: 

The Aim of this lab is about Azure portal interface customization and viewing billing, usage, and quotas data.
Build, manage, monitor everything from simple to complex. Start now! try popular products free. 25+ products always free. Start with a free credit. Learn by doing. Build your next idea. Types: networking, developer tools, data + analytics, cloud computing, databases.

### Scenario and Objective

XYZ Corporation is a manufacturing company, based in the United States, with satellite offices and 1,000 employees around the world. XYZ does not use cloud-based services for any of its technology needs. Its employees are well-versed in Microsoft technologies and tools, and the IT department is fully proficient in configuring and maintaining Active Directory, and in using SQL Server, Windows Server, and Visual Studio for administrative tasks.

However, XYZ wants to investigate how Azure could help reduce IT deployment, management, and development costs. XYZ managers believe this might drastically reduce the total cost of ownership of their applications and provide simplified world-wide access to these applications. XYZ intends to evaluate which of their IT services can run efficiently in Azure.

To prepare for future deployments to Azure, you plan to become familiar with the interface of the Azure portals, focusing on their customizability and the support for retrieving billing and resource usage data.

After completing this lab, you will be able to:

*	Customize the Azure portal interface.

*	Display billing and usage data for your Azure subscription

**Note:** *The lab steps for this course change frequently due to updates to Microsoft Azure. Microsoft Learning updates the lab steps frequently, so they are not available in this manual. Your instructor will provide you with the lab documentation.*

## Pre-requisites:

*	Azure portal subscription with super admin access.
*	Virtual Machine (Windows Installed)

**Azure portal subscription:**

These EAs provide discounts on Azure pricing and allow users to migrate software licenses from on-premises servers to Azure. Users with an EA also have access to the Azure Enterprise Portal, which provides billing and subscription management features.

**Virtual Machine (Windows Installed):**

The VM runs as a process in a **window** on your current operating system. You can boot an operating system **installer** disc (or live CD) inside the **virtual machine**, and the operating system will be “tricked” into thinking it's running on a real **computer**. It will **install** and run just as it would on a real, physical **machine**.

## Exercise 1: Customizing the Azure portal interface

**Scenario**

As part of exploring the Azure portal interface, you want to customize it so you can find information easily.

The main tasks for this exercise are as follows:

1.	Connect to the Azure portal

2.	Explore and customize the Azure portal interface

### Task 1: Connect to the Azure portal

1.	On Virtual Machine, open Chrome, and then browse to the Azure portal located at http://portal.azure.com.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l1.png)
 
2.	If you receive a prompt, sign in by using the Microsoft account that is the Account Administrator of your Azure subscription.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l2.png)
 
### Task 2: Explore and customize the Azure portal interface

1.	After the Azure portal loads, view the tiles on the dashboard, noting the service health of the Azure datacenters.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l3.png)
 
2.	Explore different views on the service health blade.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l4.png)
 
3.	Return to the dashboard.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l5.png)
 
4.	Expand the hub menu.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l6.png)
 
5.	On the hub menu, click **+ Create a resource** and, then on the **New** blade, review the list of available options, but do not select any.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l7.png)
 
6.	Browse to the **Subscriptions** blade, and then pin the entry that represents your subscription to the dashboard.
 
 ![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l8.png)

 ![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l9.png)

 ![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l10.png)
 
7.	View the corresponding notification, and then verify that the subscription tile was pinned to the dashboard successfully.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l11.png)
 
8.	Return to the dashboard, and then verify that a new tile that represents your subscription appears on the dashboard.
 
 ![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l12.png)

9.	Leave open the Chrome window that shows the Azure portal.

**Result:** Once you completed this exercise, you have signed in to the Azure portal and successfully customized its interface.

## Exercise 2: Viewing billing, usage, and quotas data

**Scenario**

You need to use the Azure portal in order to identify billing, usage, and quotas data for your Azure subscription.

The main tasks for this exercise are as follows:

1.	View resource costs and usage in the Azure portal

2.	View billing data in the Azure Account Center

3.	Prepare for the next module

### Task 1: View resource cost and usage in the Azure portal

1.	In the Chrome window that displays the Azure portal, navigate to the blade that represents your subscription.
 
![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l13.png)

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l14.png)

2.	In the blade that shows your subscription, note the pie chart that shows **Cost by resource**. Click the pie chart to display the **Cost by resource** blade, which shows a detailed breakdown of resource costs.
 
![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l15.png)

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l16.png) 

3.	Navigate to the **Usage + quotas** blade of your subscription.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l17.png)
 
4.	Note the current usage and quotas for different types of resources.

**Note:** *Because this is the beginning of the course, it is likely that the subscription has not incurred any charges and that does not include any resources. In this case, you will see a message that usage or billing data is not available. You should consider revisiting this interface on the second day of the course. Additionally, keep in mind that this interface will allow you to track cost of resources going forward, so you should review it frequently.*

### Task 2: View billing data in the Azure Account Center

1.	From the Azure portal, navigate to the CSP Account Center.

2.	If you receive a prompt, sign in by using the Microsoft account that is the Service Administrator of your Azure subscription.
 
![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l1.png) 

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l2.png)

3.	On the summary page, review the **OVERVIEW** tab and click on the Subscription.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l20.png) 

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l21.png)

4.	Switch to the **INVOICES** tab.
 
![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l22.png)

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l23.png)
 
5.	Click **Download** for the most recent billing period. You have the preview option to see before downloading the file.

6.	Do not download the usage report. To view the report, you must use Microsoft Excel, which is not installed on the lab computer.

7.	Close Chrome.

### Task 3: Prepare for the next module

1.	Unpin the subscription tile from the Azure portal dashboard.

![alt text](https://github.com/sysgain/qloudable-tl-labs/blob/MicrosoftLearnings/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l24.png)
 
2.	Close Chrome.

When you are finished with the lab, do not revert the virtual machines. Keep all the VMs running. The VMs in their current state are required for the next module.

**Result:** Once you completed this exercise, you have viewed your Azure subscription billing and usage data successfully.
