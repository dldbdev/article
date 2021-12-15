# Let’s talk about privacy, behavioural analytics and mobile apps

In 2019, two tech companies Fidzup and Teemo were struck hard for breaching GDPR. In total, more than 20M investment was in danger while both companies were at risk of bankruptcy. Both companies were collecting and analyzing location data from end-users. Even if the location data was nameless, it can never be anonymous. Teemo was able to resolve the situation by investing all R&D effort into GDPR compliance. Fidzup ceased to exist and so did more than 3M € investor money plus multiple jobs.

We are used to reading about privacy protection importance and challenges from the end-users perspective. However, the companies analyzing their customer data to provide better products and services are facing multiple investment-heavy challenges and limited options. Especially, to be more efficient when it comes to end-user data analysis. The most common approach is to invest in a centralised data lake and run the queries. This inherits several challenges, but the most critical one is being able to maintain the system throughout your service or solution lifecycle. I am not just talking about technical maintenance, which itself isn’t cheap, but also organisational maintenance -being ready to comply with all the rules and regulations and also end-user requests. Due to these challenges, many companies have either refused to start or have stopped deeply analyzing their customer behaviour.

Until now companies needed to collect their data to know their customers. But customer data was actually a means to an end. The real need is for information and answers. Data itself is a liability posing several technical challenges. For example, when you have a large customer base storing and querying it, data gets slower and more expensive.  Moreover, centralised data collection often includes masses of unnecessary and excessive information,  as data aggregation and normalization is hard or even impossible during the data collection phase. Companies thus end up with data that is never needed or will never be used with a direct negative impact on cost and efficiency. 

One good example to illustrate this “overcollection” is the location data. If we think about a single person, then most likely they are really only in three to five different places across any given day, mostly at a standstill. There is no need to collect the data repeatedly from the same place. However, with centralized data collection, you have no good alternative.

All technicalities aside, privacy protection is important for companies for several reasons. If the information they have collected is misused, it might generate bad publicity. In a worst-case scenario, it could result in millions of euros of fines or, if privacy is actually breached, even bankruptcy. During the past few years, there have been hundreds of GDPR fines and cases when companies have been shut down. As the examples in the first paragraph.

At DLDB we have been working on a way to still make use of interesting customer information as securely, privately and simply as possible. Welcome distributed behavioural analytics where data will not be collected into centralised data lakes or cloud platforms. The data is stored on the mobile devices where it is generated, but the queries will also run there. This solves not one, but three problems:
Privacy - you are not fetching any personal data
Scalability - no matter how many devices there are, queries are very fast and data volume is not an issue
Efficiency - no more high maintenance costs

There are approximately 3.5 billion smartphones globally. On average, a person has more than 80 apps on their phone.  Most of the apps collect the user data and send the data “somewhere”. Simply put, it is a real waste of resources.

# Introducing DLDB:

At DLDB we are building this device-based approach to behavioural analytics. Many companies spend several man-years to develop privacy-aware systems and spend thousands of hours maintaining their privacy compliant services. Using DLDB, every company can embed our SDK into their application with less than ten lines of code. DLDB is not only cheaper but provides peace of mind for app developers and companies.

DLDB stores the raw data in the end-user device executes all the analytical queries there, and only sends the answers to the analytics dashboard. This keeps the raw data private, removes the need to have any external data storage, and makes the queries incredibly fast. The SDK in the application allows the application itself to use the data safely and on-demand.

# In four statements:
DLDB takes care of GDPR and privacy requirements
DLDB storage and queries are distributed, so no additional storage or query costs
DLDB scales indefinitely
DLDB can collect, store, and analyze behavioural data on Android, iOS, or IoT devices

My co-founder Christophe and I have been in the data, location, GIS, and development business for more than two decades. Challenges with private data have been haunting us since the beginning. This spring we interviewed more than 80 developers globally from small startups to big corporations and unsurprisingly we heard the same issues and concerns. 

Want to become a beta tester? Please visit https://dldb.io/#Beta
