---
title: Add other content providers for Microsoft Viva Learning
ms.author: chucked
author: chuckedmonson
manager: pamgreen
ms.reviewer: chrisarnoldmsft
ms.date: 10/27/2021
audience: admin
ms.topic: article
ms.service: 
ms.prod: microsoft-365-enterprise
search.appverid: 
ms.collection: 
    - enabler-strategic
    - m365initiative-viva-learning
localization_priority: medium
description: Learn how to configure other content providers as a learning content source for Microsoft Viva Learning.
---

# Add other content providers for Microsoft Viva Learning

A growing set of learning content providers are available through Viva Learning. This set may change at any time as more providers join or change their status with the program.

Some learning sources will be enabled by default and will be available without a premium Viva Learning license. These learning sources include:

- LinkedIn Learning select 125 courses
- Microsoft Learn
- Microsoft 365 Training

Third-party content sources are not enabled by default. To enable these sources, you will need to [add them in the Microsoft 365 admin center](content-sources-365-admin-center.md#configure-settings-for-the-learning-content-sources) and follow the specific instructions shown in the following table.

>[!NOTE]
>You'll need a Premium license to connect external content sources, with the exception of the select LinkedIn Learning free courses. [Learn more about licensing](https://www.microsoft.com/microsoft-viva/learning).

>[!NOTE]
>It can take 24 to 48 hours for Viva Learning users to see content for the sources you enabled in the admin portal. It can also take 24 to 48 hours to hide content from LinkedIn Learning, Microsoft Learn and Microsoft 365 trainings from Viva Learning after you have disabled them in the admin portal.

|Content provider  |Configuration instructions  |
|---------|---------|
|Go1     |[Configure Go1 as a content source](configure-go1-content-source.md)         |
|Skillsoft     |[Configure Skillsoft as a content source](configure-skillsoft-content-source.md)         |
|Udemy   |[Configure Udemy as a content source](configure-udemy-content-source.md)         |
|edX    |Follow the steps below to add edX in your Microsoft 365 admin center.    |
|Coursera    |Follow the steps below to add Coursera in your Microsoft 365 admin center.    |
|Pluralsight    |Follow the steps below to add Pluralsight in your Microsoft 365 admin center.    |
|Infosec    |Follow the steps below to add Infosec in your Microsoft 365 admin center.    |
|Josh Bersin Academy    |Follow the steps below to add Josh Bersin Academy in your Microsoft 365 admin center.    |

1. Log in to your [Microsoft 365 admin center](https://admin.microsoft.com).
2. Navigate to **Settings**, then **Org settings**. Select Viva Learning, and enable your chosen content provider or learning management system in the panel.
3. Fill in your details.
4. Select **Save**.

>[!NOTE]
>Available content providers are subject to change. Depending on your organization, you may have access to more content providers than are listed here.

## Content ingestion errors

If you experience any errors in your Microsoft 365 admin center during content ingestion, refer to the table below for next steps. Please note that this is an exhaustive list and may contain more error codes in the future.

|Content provider |Error code |Error code description |
|:----------------|:----------|:----------------------|
|All providers |USR_ERROR_INVALID_RESOURCE_CREDENTIALS |The authentication credentials you provided are Invalid. Make sure you enter the correct credentials. You can contact Microsoft customer support for more details. |
|All providers |USR_ERROR_ACCESS_DENIED |Access denied by partner. Confirm that the credentials you entered are correct or contact the content provider's support team. |

## Content consumption for end users

Once you've added a content provider as a content source from the Microsoft 365 admin center, content from the provider will flow to the Viva Learning app and will be visible to end users.

Once a user chooses to play a course in Viva Learning, they will be directed to the content provider's webpage and will need to enter the login credentials on the provider's sign in page. [Learn more about how to consume content with Viva Learning](https://support.microsoft.com/office/01bfed12-c327-41e0-a68f-7fa527dcc98a).
