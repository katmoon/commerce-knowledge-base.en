---
title: 'Adobe Commerce 2.4.1: empty page when dotdigital Page Builder form saved'
description: This article provides a workaround for a known issue in Adobe Commerce 2.4.1 for showing an empty webpage after saving a dotdigital Page Builder form in the Admin Panel when using the Safari browser.
exl-id: 682eac73-1ad2-4093-acfb-6a8da4c05cf5
---
# Adobe Commerce 2.4.1: empty page when dotdigital Page Builder form saved

This article provides a workaround for a known issue in Adobe Commerce 2.4.1 for showing an empty webpage after saving a dotdigital Page Builder form in the Admin Panel when using the Safari browser.

## Affected products and versions

* Adobe Commerce on-premises 2.4.1
* Adobe Commerce on cloud infrastructure 2.4.1

## Issue

<u>Steps to reproduce</u>

1. Go to **Admin Panel** > **Content** > **Pages**, and select **Edit** of any page.
1. Go to **Content** and click on the **Edit with Page Builder** button.
1. Drag the **dotdigital form** block and select **Edit**.
1. Select one of the test forms, then pick **Embedded** mode and save the form.
1. Save the page modification.

<u>Expected result:</u>

The webpage should be saved successfully.

<u>Actual result:</u>

The webpage is empty. After reloading the webpage, the changes are applied.

## Workaround

The workaround is to use an alternative browser to Safari. The issue is scheduled to be fixed in the next release, Adobe Commerce 2.4.2, in Q1 2021.

## Related reading

* [What is Page Builder?](https://devdocs.magento.com/page-builder/docs/) in our developer documentation.
* [Page Builder Setup](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/setup.html?lang=en) in our developer documentation.
* [Page Builder](https://docs.magento.com/user-guide/cms/page-builder.html) in our user guide.
* [Page Builder - Elements](https://docs.magento.com/user-guide/cms/page-builder-elements.html) in our user guide.
