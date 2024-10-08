.. _spoc-system-requirements:

*************************
Application requirements
*************************



Web Application
=======================

The Splunk On-Call web app supports the following browsers:

-  Google Chrome (latest version)
-  Mozilla Firefox (latest version)
-  Microsoft Internet Explorer 11
-  Microsoft Edge (latest version)
-  Safari (latest version)

.. note:: Custom browser extensions may interfere with web-client performance.

In the future, Splunk On-Call will support the Chromium version of Microsoft Edge, and eventually discontinue support for IE11.

For IP and Egress Filtering, see :ref:`ip-egress-filtering-spoc`.

Mobile Application
============================

For full mobile functionality, Splunk On-Call recommends keeping up to date with the latest versions of the mobile app for:
- iOS :new-page:`Apple App Store <https://apps.apple.com/us/app/victorops/id696974262>` 
- Android :new-page:`Google Play Store <https://play.google.com/store/apps/details?id=com.victorops.androidclient&hl=en_US>`

Splunk On-Call supports Android devices running Android 6 or newer. Splunk On-Call no longer supports the mobile app for Android versions 5 and below.

Incident Requirements
=========================

A JSON POST request is required to send an alert payload to the Splunk On-Call timeline. For required field variables, see our :ref:`Incident Fields - Glossary <incident-fields-glossary>`.

For requirements regarding specific integrations please refer to the relating integration documentation.
