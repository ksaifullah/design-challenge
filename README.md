# Design Challenge

This design challege is aimed for screening candidates for Tech Lead or Lead Developer roles.

## Scenario
We have a retail business. During the COVID pandemic our online orders have got a significant increase both in number and size. Our applications are hosted in AWS.

We have a business partner who takes care of shipments to the customer. On every successful order submission by our users, our system makes an API call to the system owned by the shipment business with all necessary information (pick up and delivery locations and so on). The shipment system allows maximum `n` requests per customer per second.

Lately we have been experiencing some failure in our API calls with an error message `api rate limit exceeded`. After further investigation we have found that significant portion of the daytime we are consuming ~90% of that rate limit.

## Expectations
We need to develop/deploy a scallable solution immediately so that we can avoid the api failures and manual work around failure resolution.

As a Tech Lead or Lead Developer, how would you handle the situation, investigate the problem further, prepare solution options, produce a solution design and finally develop/deploy the solution with your team.

Please use a [Miro](https://miro.com/login/) board to capture the lifecycle of the process. The board should contain the details of each stages pretending you have passed through them, of course except the actual development.

*Note: Miro gives a couple of boards with their free subscription. Please use a free subscription for this challenge.*

We would like you to present the Miro board during the interview for an estimated time of 20 mins and another 10 mins for discussions.
