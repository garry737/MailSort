# MailSort

## Inspiration
The steady march of incoming emails from class websites, reminders from school, spam emails, promotions, notifications, confirmations, invitations, and updates make sifting through email a huge hassle, not to mention the ease with which emails that actually matter tend to disappear in the mix. With this in mind, and with the current crisis meaning email feeds are more crowded than ever. 

This allows emails that are actually relevant to be sorted through and presented to the user in an easy to use fashion that will eliminate the suffocating feeling of sifting through spam and missing those important notices. 

## What it does
Uses an automated robot to sort emails from your inbox into labels.

## How we built it
We built a robot using the Robot Process Automation (RPA) platform UIPath. We integrated GSuite APIs through the Google Cloud Platform (GCP) to access and edit a users Google Drive, Google Sheets, and GMail. We did this through OAuth so it is secure and the user will be prompted individually. 

We sorted the emails into labels through a certain set of keywords the emails' body contains. The set of keywords is easily accessible and personalized, which will be automatically retrieved by our robot. 

## Challenges we ran into
UIPath's documentation and resources were limited so we had to rely on ourselves to develop and debug. This was especially true as we used the GSuite package which is not a part of the core packages of UIPath.

## Accomplishments that we're proud of
- We are able to 100% automate the sorting of emails based on our parameters.
- We got it to work on anybody's Gmail account
- We were able to learn a new technology in under 24 hours
- We were able to work together as a team despite physical boundaries due to the current Coronavirus situation

## What we learned
- We learnt new concepts regarding robots and automation
- We learnt the ability to utilize Google Cloud Platform securely and to its full potential
- We learnt that we are able to tackle any new and difficult challenges if we are determined and worked as a team

## What's next for MailSort
- We hope to implement a sorting algorithm using Machine Learning rather than keywords
- We hope to expand to other email services other than GMail.
