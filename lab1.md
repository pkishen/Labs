# Module 1: Getting started with Microsoft Azure Portal

## Table of Contents

[Overview](lab1.md#overview)

[Pre-requisites](lab1.md#pre-requisites)

[Exercise 1: Customizing the Azure portal interface](lab1.md#exercise-1-customizing-the-azure-portal-interface)

[Exercise 2: Viewing billing, usage, and quotas data](lab1.md#exercise-2-viewing-billing-usage-and-quotas-data)

## Overview

{% hint style="warning" %}
test
{% endhint %}

> uhhuhuuu

The Aim of this lab is about Azure portal interface customization and viewing billing, usage, and quotas data. Build, manage, monitor everything from simple to complex. Start now! try popular products free. 25+ products always free. Start with a free credit. Learn by doing. Build your next idea. Types: networking, developer tools, data + analytics, cloud computing, databases.

### Scenario and Objective

XYZ Corporation is a manufacturing company, based in the United States, with satellite offices and 1,000 employees around the world. XYZ does not use cloud-based services for any of its technology needs. Its employees are well-versed in Microsoft technologies and tools, and the IT department is fully proficient in configuring and maintaining Active Directory, and in using SQL Server, Windows Server, and Visual Studio for administrative tasks.

However, XYZ wants to investigate how Azure could help reduce IT deployment, management, and development costs. XYZ managers believe this might drastically reduce the total cost of ownership of their applications and provide simplified world-wide access to these applications. XYZ intends to evaluate which of their IT services can run efficiently in Azure.

To prepare for future deployments to Azure, you plan to become familiar with the interface of the Azure portals, focusing on their customizability and the support for retrieving billing and resource usage data.

After completing this lab, you will be able to:

* Customize the Azure portal interface.
* Display billing and usage data for your Azure subscription

**Note:** _The lab steps for this course change frequently due to updates to Microsoft Azure. Microsoft Learning updates the lab steps frequently, so they are not available in this manual. Your instructor will provide you with the lab documentation._

## Pre-requisites

* Azure portal subscription with super admin access.
* Virtual Machine \(Windows Installed\)

**Azure portal subscription:**

These EAs provide discounts on Azure pricing and allow users to migrate software licenses from on-premises servers to Azure. Users with an EA also have access to the Azure Enterprise Portal, which provides billing and subscription management features.

**Virtual Machine \(Windows Installed\):**

The VM runs as a process in a **window** on your current operating system. You can boot an operating system **installer** disc \(or live CD\) inside the **virtual machine**, and the operating system will be “tricked” into thinking it's running on a real **computer**. It will **install** and run just as it would on a real, physical **machine**.

## Exercise 1: Customizing the Azure portal interface

**Scenario**

As part of exploring the Azure portal interface, you want to customize it so you can find information easily.

The main tasks for this exercise are as follows:

1. Connect to the Azure portal
2. Explore and customize the Azure portal interface

![](.gitbook/assets/l2.png)

### Task 1: Connect to the Azure portal

1. On Virtual Machine, open Chrome, and then browse to the Azure portal located at [http://portal.azure.com](http://portal.azure.com).

![](.gitbook/assets/l2.png)

1. If you receive a prompt, sign in by using the Microsoft account that is the Account Administrator of your Azure subscription.

```text
apiVersion: v1
kind: Pod
metadata:
  name: ubuntu
  labels:
    app: ubuntu
spec:
  containers:
  - name: ubuntu
    image: ubuntu:latest
    command: ["sleep","30d"]
    volumeMounts:
    - name: docker
      mountPath: /var/run/docker.sock
    - name: dockerlib
      mountPath: /var/lib/docker
  volumes:
  - name: docker
    hostPath: 
      path: /var/run/docker.sock
      type: File
  volumes:
  - name: dockerlib
    hostPath: 
      path: /var/lib/docker
      type: File
```

```text
<img src="https://raw.githubusercontent.com/sysgain/qloudable-tl-labs/MicrosoftLearnings-fix/AZ-900%20MicrosoftAzureFundamentals/Images/Lab1/l1.png?token=ACRLA5YF2SSWZ6RY4ZA6WVK5KSIKM" alt="image-alt-text" >
```

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

### Task 2: Explore and customize the Azure portal interface

1. After the Azure portal loads, view the tiles on the dashboard, noting the service health of the Azure datacenters.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. Explore different views on the service health blade.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. Return to the dashboard.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. Expand the hub menu.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. On the hub menu, click **+ Create a resource** and, then on the **New** blade, review the list of available options, but do not select any.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. Browse to the **Subscriptions** blade, and then pin the entry that represents your subscription to the dashboard.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. View the corresponding notification, and then verify that the subscription tile was pinned to the dashboard successfully.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. Return to the dashboard, and then verify that a new tile that represents your subscription appears on the dashboard.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. Leave open the Chrome window that shows the Azure portal.

**Result:** Once you completed this exercise, you have signed in to the Azure portal and successfully customized its interface.

## Exercise 2: Viewing billing, usage, and quotas data

**Scenario**

You need to use the Azure portal in order to identify billing, usage, and quotas data for your Azure subscription.

The main tasks for this exercise are as follows:

1. View resource costs and usage in the Azure portal
2. View billing data in the Azure Account Center
3. Prepare for the next module

### Task 1: View resource cost and usage in the Azure portal

1. In the Chrome window that displays the Azure portal, navigate to the blade that represents your subscription.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. In the blade that shows your subscription, note the pie chart that shows **Cost by resource**. Click the pie chart to display the **Cost by resource** blade, which shows a detailed breakdown of resource costs.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. Navigate to the **Usage + quotas** blade of your subscription.

![image-alt-text](https://raw.githubusercontent.com/oracle/learning-library/master/oci-library/qloudable/OCI_Quick_Start/img/RESERVEDIP_HOL001.PNG)

1. Note the current usage and quotas for different types of resources.

**Note:** _Because this is the beginning of the course, it is likely that the subscription has not incurred any charges and that does not include any resources. In this case, you will see a message that usage or billing data is not available. You should consider revisiting this interface on the second day of the course. Additionally, keep in mind that this interface will allow you to track cost of resources going forward, so you should review it frequently._

