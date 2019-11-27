---
title: Creating a report on a SharePoint List
description: 
author: adamw
ms.reviewer: ''

ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: tutorial
ms.date: 11/27/2019
ms.author: adamw

LocalizationGroup: Visualizations
---
# Creating a report on a SharePoint List

[!INCLUDE [power-bi-visuals-desktop-banner](../includes/power-bi-visuals-desktop-banner.md)]

Many teams and organizations use Lists in SharePoint Online to store data since it is easy to set up and for users to update.  Sometimes a chart is a much easier way for users to quickly understand the data rather than looking at the list itself.  In this tutorial, we will show you how to transform your SharePoint List data into a Power BI Report.

TODO: image

# Step 1: Connect to your SharePoint List

1. If you don't have it already, download and install [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).
2. Open Power BI Desktop and in the Home tab of the ribbon, click *Get Data*.
3. Click *More*.
4. Click *Online Services* on the left, then click *SharePoint Online list*.  Click *Connect*.
5. Find the address (also known as a URL) of your SharePoint Online site that contains your list.  From a page in SharePoint Online, you can usually get to the site address by clicking "Home" in the left navigation or the icon for the site at the top, then copying the address from your web browser's address bar.
6. Copy and paste the address into the Site URL field in Power BI Desktop.
7. Click on *Microsoft Account* on the left hand side of the page.
8. Click Sign In and enter your username and password you use to sign in to Microsoft Office 365.
9. When you are finished the sign in process, click *Connect*.
10. On the left hand side of the page, click the checkbox beside the SharePoint list you want to connect to.
11. Click *Load*.  Power BI will load your list data into a new report.

# Step 2: Create a report

1. On the left hand side, click the *Data* icon to see your SharePoint list data that was loaded.
2. Make sure your list columns with numbers show the Sum icon in the list on the right hand side of the screen.  For any that don't, fix this by clicking the column header in the table view, clicking the *Modeling* tab, then changing the Data type dropdown to Decimal Number or Whole Number, depending on your situation.  If prompted to confirm your change, click *Yes*.  If your number is a special format, like currency, you can also choose that by setting the 'Format'.
3. On the left hand side, click the *Reprot* icon.
4. Select columns you want to visualize by clicking the checkbox beside them on the right hand side of the screen.
5. Change the visual type if you need to.
6. You can create multiple visualizations in the same report by unselecting the existing visual then clicking checkboxes for new columns.
7. Click *Save* to save your report.
