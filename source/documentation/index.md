---
title: Before you start | CTC Traders API testing guide
weight: 1
description: Software developers, designers, product owners or business analysts. Verify the compatibility of your software with CTC Traders API and learn how to test your application in our sandbox environment.
---

# Before you start

Learn how to test the compatibility of your software with New Computerised Transit System.

**Note**: Please restrict your testing to the test scenarios in this document. HMRC cannot support tests that are 
not included here.


When you are ready to test your software, first read and understand the
[CTC Traders API service](https://developer.service.hmrc.gov.uk/guides/ctc-traders-service-guide/) guide and 
[NCTS technical interface specification](https://developer.service.hmrc.gov.uk/guides/ctc-traders-tis/).

## Trader Test
Trader Test is a test environment that simulates both automated responses and real-life experience where NCTS support 
staff do the tasks of Border Force personnel. When your testing requires a manual response, NCTS support staff will 
perform the live manual steps of the process. This simulates and tests a full real-life journey from start to finish 
for you.

You can use NCTS Trader Test to test small messages (up to 5MB in size) and large messages (up to 8MB in size) with 
standard departures process, pre-lodged departures process, and arrivals process flows.


## Testing prerequisites
For information about actions that must be completed before testing, see the getting started section of the [CTC Traders 
API phase 6 service guide.](https://developer.service.hmrc.gov.uk/guides/ctc-traders-service-guide/#pre-requisites-ncts-subscription)


## Test environments

### Availability Window

The sandbox environment/Trader Test service will be available **24 hours, 7 days a week until 1 June** to support testing.

From 1 June onwards, availability will revert to **7am–7pm, Monday to Friday (UK time, GMT/BST)**.

You must use our sandbox environment and Trader Test to test the compatibility of your software with CTC Traders API.
