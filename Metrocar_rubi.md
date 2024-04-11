![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.001.png)

**Metrocar**

ByReuvenBermant

31\.10.2023

1
**Contents**

Executive Summary……………………………………………………………………………………..3

1. Context…………………………………………………………………………………………………….4-5
1. Metrocars funnel……………………………………………………………………………………..6
1. Business questions…………………………………………………………………………………..7
1. DataSet…………………………………………………………………………………………………….8
1. Funnel research & improvement……………………………………………………………..9-11
1. Market budgeting…………………………………………………………………………………….12-14
1. Age Group performance………………………………………………………………………….15-16
1. Price Surging……………………………………………………………………………………………17-18
1. Funnel Digging & Solutions……………………………………………………………………..19-20
1. Additional Insights…………………………………………………………………………………21-22 11.Final Conclusion……………………………………………………………………………………..23

Appendix…………………………………………………………………………………………………….24



**Executive Summary**

This report details a funnel analysis conducted for Metrocar - a state of the art ride-sharing app that utilizes smartphones to connect riders with drivers.

The customer funnel of Metrocar includes the following stages: App-download -> signup -> request ride -> driver acceptance ->ride -> payment -> review.

The goal of this analysis is to identify areas for improvement and optimization the company can focus on in each step of the funnel.

Several insights were identified:

First, there is a huge user drop off between ride accepted and ride completed - a substantial 50% drop off.

Second, a 25% drop off was identified between

app download -> signup and signup ->request ride, which directly correlates to users aged between 35-44 years that may experience tech related problems.

This report recommends a number of solutions to the problems that were identified,

such as adding more drivers in busy hours, and trying to improve the app for a more user-friendly interface for the main audience whose age

group is between 35-44.

Conclusion: Metrocar should invest more in the iOS platform and adapt the user interface for the 35-44 age group users while surge prices should be focused on high prices at busy hours.

**App**

Metrocar's business model is based on a platform that connects riders with drivers through a mobile application. Metrocar acts as an intermediary between riders and drivers, providing a user-friendly platform to connect them and facilitate the ride-hailing process.

**The Funnel Analysis**

In any user journey, it is entirely expected to encounter a drop-off at various stages. Not all individuals who download the app will proceed to sign up, and not all signed-up users will actively engage with the service. This attrition, commonly referred to as drop-off, is an inherent aspect of the user acquisition and retention process, underscoring the importance of conducting a comprehensive funnel analysis.

Several key reasons underscore the significance of this analysis:

**Quantifying Drop-off**

The primary goal of a funnel analysis is to precisely quantify the drop-off occurring at each stage of the user journey. By meticulously tracking conversion rates from one stage to the next, we can pinpoint where and how users are exiting the funnel. This data-driven approach provides valuable insights into identifying bottlenecks and areas requiring improvement.

**Identifying Causes**

Beyond merely quantifying drop-off, the funnel analysis serves to uncover the underlying causes of attrition. It enables the identification of patterns and trends shedding light on user behavior and the specific pain points experienced at each

3

stage. These insights are invaluable for designing interventions that directly address the root causes of drop-off.

**Taking the Right Actions**

Armed with an understanding of the causes of drop-off, the funnel analysis empowers us to develop data-informed strategies to mitigate attrition. These strategies may involve optimizing the user experience, enhancing app features, or offering targeted incentives to users at critical stages of the funnel.

**Focused Energy**

Recognizing that not all stages of the funnel are equal, the analysis helps pinpoint where it makes the most sense to concentrate efforts. By directing attention to stages with the highest drop-off or those most critical to business objectives, resources can be allocated effectively to enhance the overall user journey.

Through a thorough funnel analysis, we gain valuable insights into user behavior, systematically enhancing the customer experience. This data-driven approach empowers us to make informed decisions that drive user engagement, conversion, and ultimately foster business growth.

5

**Metrocar’s Funnel**

The Metrocar funnel includes 2 funnels that we can analyze. First user funnel goes as follow:

A.app Download: Auser downloads the Metrocar app from App Store or Google Play Store.

2. Signup: The user creates an account in the Metrocar app, including their name, email, phone number, and payment information.
2. Request Ride: The user opens the app and requests a ride by entering their pickup location, destination, and ride capacity.
2. Driver Acceptance: Anearby driver receives the ride request and accepts the ride.
2. Ride: The driver arrives at the pickup location, and the user gets in the car and rides to the destination.
2. Payment: After the ride, the user is charged automatically through the app, and a receipt is sent to their email.
2. Review: The user is prompted to rate their driver and leave a review of their ride experience.

   Second ride funnel goes as follow:

   A.Ride Requested: The count of rides requested through the entire time dataset given.

2. Ride Accepted: The count of rides that got accepted out of all rides requested.
2. Ride Complete: The count of rides that got complete out of all rides accepted.
2. Ride paid: The count of rides that got paid out of all rides were complete.
2. Ride reviewed: Number of reviews the user wrote about their ride experience.

**Business Questions**

The analysis of the data and all my recommendations are based on the following business questions:

1. What steps of the funnel should we research and improve? Are there any specific drop-off points preventing users from completing their first ride?
1. Metrocar currently supports 3 different platforms: ios, android, and web. Where should we focus our marketing budget for the upcoming year? What insights can we make based on the platform?
1. What age groups perform best at each stage of our funnel? Which age group likely contains our target customers?
1. Ifwe want to adopt a price-surging strategy, What does the distribution of ride requests look like throughout the day?
1. What part of our funnel has the lowest conversion rate? What can we do to improve this part of the funnel?

**DataSet** The company dataset comprises of 5 tables:

1. App Downloads: Contains unique download key, a download timestamp, and the Platform the user downloads the app with.
1. Signups: signup table contains a unique user ID, user age group, a timestamp of the signup data & hour, and the session IDwhich refers to the App Download table unique download key.
1. ride requests: ride requests table contains all the information we can gather

about the ride, ride ID(number of ride), user ID, driver ID, all timestamp of the main stage of the service: request - accept -cancel/pickup -dropoff.

The table includes pick-up and drop-off points.

4. Transactions: Transactions table contains the transaction ID, ride ID, amount usd the user paid and transaction timestamp.
4. Reviews: reviews table contains a review ID, ride ID,user ID, driver ID, a rating between 1 to 5, and a text review if the user wants to add more info about the ride experience.

**QuestionA**

The steps we want to research the most are the drop-off between ride request and ride completion as we can see a drop of 49.23% (12,278 ride accepted to 6,233 rides complete), also we want to investigate the drop off which happens in the amount of reviews we get out of all rides (30.24% drop off), as a tool to improve our service.

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.002.jpeg)For further investigation we should dig down at what happens that prevents the user from completing their first.

The main problem is the driver availability at peak hours, which causes the customer to cancel his ride due to long waiting time.

Pale Blue: ride requests Orange:available driver Green: ride complete Red : ride canceled

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.003.jpeg)

The visualization included above also indicates on specific hours that have more traffic , 8:00 AM- 10:00 AM

16:00 PM - 19:00 PM.

As Idug more for the reason Ifound out that cancellation time is a big factor of

rides accepted to rides complete, the waiting time for accepting the ride spreading between 3-21 minutes, a huge time difference that the customer would rather choose an alternative riding option.

The longer the customer is waiting there is more chance of him to cancel the ride and not complete the funnel steps of the ride.

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.004.jpeg)

As for the reviews amount we see a drop off with 30.24% (4,438 reviews out of 6,233 rides complete),

Low amount of reviews make us understand less about the service of the customer side and the experience he gets from the service.

Making the review more accessible to the customer and **consider profit for more detailed review.**

**My recommendation for the biggest drop off point of the funnel is to increase the number of drivers which will make waiting time shorter and prevent the cancellation rate which grows as the customer waits more time.**

**QuestionB**

Where should we focus our marketing budget this year based on platform?

When talking about platform based budgets we should investigate in 3 directions. Total number of users, total number of rides and average spent per user/ride. The number of users in Metrocar is divided into 14,290 iOS users, 6,935 Android users and 2,383 Web users.

In terms of profit we can see there is a huge difference between iOS and the rest of the platforms as iOS takes 60% of total profits, Android is almost 30% of total profits and 10% are Web users.

Although there is a difference in profit amount, the amount paid per user is almost the same.

For example: iOS average 190$ per user, Web user spends 185$ and Android 188$ per user.

There is a major difference in the amount of rides across the platform where there is once again a big lead for iOS users with 70K more rides, but the amount spent per ride is still the same as the users with 20$ a ride for each platform.

In terms of Age group we can see that across all 3 platforms Metrocar is supporting there is a clear line of sight that 22-34 and 35-44 groups are leading , while there is a lot of unknown information which can make the results look different if this data was known by us.

It's important to notice that in terms of growth in last year distribution:

Q1-Q2: we got a decrease in revenues, iOS lost 40% Android 43.61% and Web 32.79%.

Q2-Q3: iOS increased revenues by 109.17% while Android and Web got 108% increase.

Q3-Q4: iOS leads with 50.57% growth, not far behind Android with 48.82% and Web got a smaller increase of 39.95%.

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.005.jpeg)

**Side Note:**

The result of comparing the amount of iOS vs Android total users across the US is almost 50%/50% and which **eliminates the option** that the iOS profits are the result of **more users across the US** and indicates that Metrocar is more popular across iOS users, Web users are negligible compared to the 2 major platforms.

**My recommendation for investment based on platform for the upcoming year’s marketing budget is as follows:**

**Half of the total investment budget should be spent on the iOS platform, the remaining 50% should be invested 35% and 15% on Android and Web respectively.**

**The recommendation above considers the comprehensive analysis of profits per user and profits per ride.**

**Finally, it is important to consider that although the profits are the same across all platforms, the exposure is substantially more beneficial in the iOS platform.**

**PLATFORM DASHBOARD**

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.006.jpeg)

**QuestionC**

Which age group performs best at each stage of the funnel? Which age group should we focus more as our target customer?

To answer business question C, we need to look at this question as 2.

First, the age group that performs best we can see at the Platform Dashboard

above that the age groups of 25-34 and 35-44 are performing the best at the revenue part, which can indicate to us that these age groups will perform better at each stage of our funnel.

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.007.jpeg)

Blue : Downloads Green: Signups

Pale Blue: ride requests Orange: ride accept Red: rides complete

Our target age groups should be 25-34 and 35-44 as our main source of income and the best performing age groups at each stage.

There is also a huge gap between these two age groups and the rest in terms of rides completed.

While these two groups made 110,974 rides together the rest of the groups made 46,721rides 58% drop off. (Unknown age was 65,957 rides).

**\*Notice: there is equal amount of unknown information as known about our best performing age groups, knowing this information can change the whole perspective at our age group Funnel, IRecommend to make it a must fill information while signup to the app.**

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.008.jpeg)

**QuestionD**

What if we want to adopt a price surging strategy?

Price surging strategy is a dynamic pricing method where prices are temporarily increased as a reaction to increased demand and mostly limit supply.

To adopt this strategy we have looked at the distribution of ride requests throughout the day and what specific hours of the day we can increase the price and which hours to lower the price for greater outcome.

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.009.jpeg)

As we can see at the graph Ishown above, if we want to adopt the surge pricing strategy the right hours to increase will be at 7:30 AM- 10:00 AM,

and 4:00 PM - 7:30 PM.

Surge pricing is sensitive topic for number of reasons:

First, the product must be well designed with minimal room to improve, and the best service we can give for the company to use this strategy and execute it well.

Second, the customer may not love this strategy and leave the app for good and find some better alternative which can make it harder for him to return for using the app considering we have supply demand issues.

Third, there is also a great opportunity for the service to make up for lack of drivers at peak hours in the first and second part of the day and make waiting time as minimal as it can be.

**To conclude, my recommendation to the price surge strategy is to find the solution to the biggest problem of the funnel, the lack of drivers through the day which deny the passenger complete their drive. (Almost 50% do not complete.)**

**After finding the solution to the problem above i Recommend to use surge pricing strategy to maximize profits at peak hours.**

**QuestionE**

What part of the funnel has the lowest conversion rate? What can we do to improve it?

The lowest conversion rate of our funnel is between rides accepted to rides complete.

Only 49% conversion rate, at the most critical part of the funnel

For better understanding of this specific part I'llshow the funnel of this specific part.

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.010.jpeg)

The funnel above shows the biggest drop off point and the lowest conversion rate with only 49% of users completing the ride after the ride got accepted.

Ifwe look at the user conversion rate it's 12,304 accepted to 6,233 rides complete for unique users.

Ifthe conversation rate did better in 50% we would see approximately 25% more revenue which will make the company more profitable.

For better improvement at this point we should add more drivers to the product, the more drivers we have the more rides will be complete and revenue will grow. Another action we can take to make drivers more available is to use surge pricing for drivers only, which will make the customer pay the same amount but the profit the driver would make increase it by 20%, this may look like money lose for the company but at looking at the bigger picture the more rides will complete the more revenue the company will make and more users will use the service and increase the revenue in non busy times of the day, the less busy hours in the middle of the day, early morning and late night rides.

In conclusion, my recommendation to this part of the funnel will affect all the other parts of the funnel.

- Add more drivers at peak hours.
- Do surge pricing for drivers only to add more drivers.
- Make an survey for the users that do not completed their first ride and ask what prevented them for better knowledge

**AdditionalAnalysis**

Another part of the funnel that might seem less important as it's not related to the ride funnel is the review part.

Reviews can give us more insight about the customer experience of the ride and the service we provide and give us more specific indicators and aspects we can improve on.

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.011.jpeg)

For this part Ihave chosen some specific words that can describe the ride experience.

The most common adjective word was used is unfamiliar (8,732 times) as the service is new and need to be tested across more users and drives to get better information, also there is important words that highlighted such as “poor” (7,581 times) that can indicate that the user is not experience a good ride and might consider

not using our service in the future.

The word “last” (6,242 times), also got a high count of uses as part of the term “last time”, and “last ride”.

Allof these are written reviews that are not part of the 1-5 rating.

**Preserve point**

One of the best conversion rates Ifound out is the funnel of rides and not users. While most users do not complete their first ride and struggle to use the service, the rest of the users that do complete their ride tend to use it frequently and enjoy the service with impressive numbers and conversion rates.

![](Aspose.Words.108809dc-eaf7-4b0b-8622-33ce394ed4fe.012.jpeg)

Only 2% drop rate of rides that got accepted to rides complete in total rides over 14 months of service.

These conversion rates are indicating that if the company could get a useful

solution as i mentioned above and convert the rest of the users the company revenues can keep growing as the last 2 quarters.

**FinalConclusions**

Overall the company is on a good path towards success with great revenues and great conversion rate with the rides that do get accepted, while the company performs well there are a couple of points to get it even better and make the company great and to dominate the market.

- Increase the number of drivers through the day and mostly at peak hours.
- Budget priority should go towards iOS service with increased revenues through the year, and bigger exposure.
- Age groups **must fill** information, too much unknown information that prevents making better decisions based on age group.
- Price surge should be implemented after solving the problems for better revenues.
- Written reviews should get more attention, and get surveys for the users that do not complete their first ride for better understanding.
- Subscriptions option that give priority to some users who had great experience using Metrocar, use it more and recommend that way the company can make more profit and preserve loyal customers.

**Appendix**

1. Visualization on tableau <https://public.tableau.com/app/profile/rubi.bermant/vizzes>
1. Queries used on this analysis attached as word document
1. Presentation attached as pdf file.
23
