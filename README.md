# Business-and-AI

Problem statement:

You work for a startup, and your CEO/founder thinks the next big thing is peer-to-peer car sharing.  She believes that with cars spending 90% of their life in a garage or parked on the street people will be interested in renting them to make some extra cash.  She wants you to investigate the idea and develop a proposal for a peer-to-peer car sharing application.  The proposal should include a recommendation for the design of the application, potential applications of AI, the value proposition, and the business model.
Deliverables
The goal of this problem is to better understand how you would approach data science/AI problems with as near to real-life situations as possible. As a deliverable, prepare 1 page document on the topic below. I recognize that you’re working with incomplete information, so I am looking for how you approach breaking down and solving for problems.
Prepare a 1 page write up describing your approach to developing your proposal to the CEO. The write up is not the proposal itself. It should include answers to below questions:
•	What questions would you have, who would you want to ask, and how would you go about trying to find an answer?
•	What do you need to learn and how would you approach learning what you need?
•	What assumptions are you making?
•	How would you measure success?
•	What risks are there in your plan and how would you manage that risk?


Solution:

P2P Car-sharing services
Proposal/Design:
Feeling helpless seeing your car idly parked, knowing there are people out there desperately needing one? Worry not, because we have come up with a unique car sharing application which allows car owners to lend their cars on an hourly basis to folks needing them! This is a 100% safe peer-to-peer car sharing platform that verifies lenders and borrowers once they create their accounts. Any borrower can view cars available in her vicinity or select a location far off in case she plans to travel there in the future. Rental rates are decided by our company based on car type and location, and all transactions take place within the platform. Both lenders and borrowers can be rated, and these ratings are visible to everybody. There is also an in-built chat platform where lender and borrower can communicate with each other, so that they don’t have to exchange personal phone numbers.
Value Proposition:
Car4U is a mobile application that lets you borrow any kind of car from a lender who’s willing to hand over her precious ride so that you can fulfill your commitments without the hassle of booking a cab or opting for public transport. So, be ready to take the control of your life (read, steering wheel) in your hands and travel without any worries. Choose from a wide range of cars in your current city or some other place in the country with just a few clicks! We promise that the cars we suggest to you are in their best condition as they are not owned by a third-party business but real owners who wish to make some money while they are not using their rides. So, go cashless with our in-app digital payment options, rest assured with top-notch identity verification process and travel wherever you want!
Business model:
As a marketplace that connects potential car lenders and borrowers, our app can seek a commission of 10% behind every successful transaction. Cancellations can draw a maximum of 5% from the party who cancelled it, consequently adding to our profits and discouraging cancellations. Offers can be rolled out to customers using the app for enough time. A sort of subscription where lender opts to use a car on some pre-defined days every week can result in reduced overall cost and encourage customer retention. 
AI usage:
1.	Recommendation list can not only be driven by location but can also include showing similar car types and car ratings as the borrower explores the platform.
2.	Collaborative recommender systems can be used to suggest cars based on other users having similar age group, destination, and car make/category interests.
3.	Sentiment analysis to classify car reviews into positive or negative.
4.	Route tracking to warn lender of car straying too far away from promised location which may cause possible delay in car return.
5.	Image recognition for verification of identity during registration and ensuring that the borrower is indeed the same person who requested for the car online.
6.	Text recognition to flag users having inappropriate conversations on the in-app chat platform.
7.	For marketing/advertisement of the app, it can be possible to team up with car sellers to identify new car owners, recognize users surfing websites for buying cars or users from cab sharing apps and recommend our app to them.
Questions/Learnings:
1.	In-app financial gateways: To enable financial transactions within the app, it is important to talk to various banks and fintech companies about ways to integrate their methods in our platform, their compensation, reimbursement for damage caused to our app in case of financial losses or transaction mishaps/failures.
2.	Insurance/deposits: In case of an accident, is the driver or car owner held responsible? Is it wise to have a hefty deposit made for each car lending instance and if yes, what should the cost be? Some data mining and judicial advice can be of help here.
3.	Ethics/law enforcement: What happens if a borrower does not return the car on time or worst case, steals it – can the police department of the respective locality help? Additionally, in case of traffic violations, is there a way to keep the owner completely out of picture although the car was his? Will the police trust the driver when she says she’s borrowed a car using our app and be satisfied with the evidence she provides? Lastly, in case of pollution violations by the car, full ownership must be placed on the owner of the car/lender. Lastly, does the app take full responsibility of any theft or completely stays out of it?
4.	Accidents/health – In the unfortunate events of accidents, who is responsible for medical treatment/compensation – the victim or our organization? Should asking for valid health insurance from borrower’s side be made compulsory?
5.	In-house management: Should cancellations be counted towards ‘app failures’? Is it right to charge whoever from lender/borrowers’ side cancels and if yes, what should the amount be?
6.	In-house management: Who pays for gas? Does the lender have to keep the car ready with a full tank? Some concrete and transparent policy must be made to avoid confusion among users. Tolls can be paid by the drivers/borrowers.
7.	Funding/Finance department: App development, MVP creation and launch would require funds for staffing, licensing, and other overhead costs. We need to find out if the financial department can own this or we would need to raise funds outside the organization.
Risk Management:
1.	Handing over one’s car to a stranger can be intimidating. Thus, some identified risks and their management ideas are as follows-
•	Borrower ran away with car – maintain contact details of car owner/lender, borrower, and maintain some point of contacts from police department.
•	Car damaged by borrower – Check that car is insured before it is lent and sign a contract with borrower beforehand to cover costs not covered in insurance.
•	Lender did not make car available on time due to her personal reasons without intimation – Put some policy together to deduct money earned by lender to discourage such incidents.
•	Borrower did not return car on time – Cut appropriate losses from deposits as some other borrower could have used the car during that time.
•	Fraudulent accounts – Despite having a strong verification process at registration, it is possible that some accounts might still be fake. Updates should be made from time to time to train the AI models to detect more and varying forged documents.
•	To avoid high rates because of app commission, keep more money for themselves despite charging lesser than the app to the borrower, lenders can fake-cancel a car share and ask the borrower to transfer money outside the app. If the number of cancellations doesn’t hamper success metrics, customer retention would still be possible, but customer wouldn’t be able to make use services like personal data privacy and protection that the app provides. However, if customers decide to take their entire business outside the app after initial connection, our retention rate might get affected. To tackle this, timely offers can be rolled out to make sure customers continue using the app even if they know each other outside the platform. Losses from such offers can be recovered from new sign ups as no customer wants to pay less initially and more later, but anyone will be happy to know that they used to pay more earlier and lesser gradually.
•	Server/app downtime or transaction failures: Refund any money transferred during downtime or failures and reach out to service providers and payment gateway enablers to solve problems and avoid them in future.
Assumptions:
•	The app will be launched only in US to start with.
•	The app will have 2 kinds of accounts with different settings for borrowers and lenders.
•	A valid US mobile number would be needed to sign up in the app.
•	The organization continues to remain a marketplace and does not plan to incorporate any other complimentary services soon.
•	The MVP launched would only test the usage of marketplace with out-of-app transactions but in-app verification.
•	The organization ties up with legal advisors for any future concerns.
Measure success:
Success can be measured by metrics like -
•	Increase in number of car shares per week.
•	Increase in number of successful transactions per day.
•	Increase in number of new customer sign-ups per month.
•	Increase in customer retention rate month over month.
•	Decrease in law violations by drivers.

