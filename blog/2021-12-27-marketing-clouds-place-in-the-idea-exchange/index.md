---
slug: Marketing Cloud's Place in the Idea Exchange
title: Marketing Cloud's Place in the Idea Exchange
authors: [jordanseeley]
tags: [marketingcloud, ideas]
---

![Salesforce Idea Exchange](./undraw_Connecting_Teams_re_hno7.png)

---

The [Salesforce Idea Exchange](https://ideas.salesforce.com/s/search) is an online community for professionals to provide feedback to the teams developing the products that we use everyday. It’s a way for users to directly influence the roadmap of the products they use by calling out features that would make our lives better while developing in the ecosystem. 

I’ve been a longtime [fan and contributor](https://trailblazer.me/id/jseeley1) to the Idea Exchange, and coming to the end of 2021 I thought of some questions that I wanted to find answers to:

How many total ideas are currently in the Salesforce Idea Exchange?
How many of those ideas are related to Marketing Cloud vs. other Salesforce products?
What are the most popular ideas for Marketing Cloud? What are some of the most promising ideas, and why?
How many winners have been selected so far, and how many of those winners are from the Marketing Cloud Category?
If you are interested in the answers to these and others, you are in the right place.

Skip to the good parts of this article:

Understanding the Current State of the Salesforce Idea Exchange
Where does Marketing Cloud fit into the Picture
My Superlatives from the top 100 Marketing Cloud Ideas
Evaluating Winning Ideas
Salesforce Idea Exchange
At the time of writing, there are ~82,000 unique ideas in the exchange. After some quick data scraping and analysis, I found that the vast majority of Ideas are related to only a few key products in the Salesforce portfolio, with the lion’s share, perhaps fittingly, belonging to their first product – Sales Cloud. That said, ~96% of all ideas are spread across just 10 of the 29 unique categories that Salesforce currently tracks, a pretty consolidated field.

Where does Marketing Cloud fit into the picture?
What was even more surprising to me, though, was that of all posts submitted to the Salesforce Idea Exchange, only 3.7% of ideas belong to the Marketing Category. This also happens to be the 6th most popular category in terms of total ideas submitted. 

While 3.7% might seem small, that actually accounts for over 3,000 different ideas that customers and users have submitted as feedback on Marketing products. My next questions revolved around finding the most compelling and important Ideas submitted so far.

Before I go further, I’ll mention that I played around on the Exchange a little longer than I planned on while trying to figure out how I could acquire, prepare, and slice the data that I wanted to analyze, but that ultimately deserves a followup post at some point in the future. 

That said, the quick and dirty method I took to solve some of these questions wast filtering ideas to only include those within the Marketing Category, sorting by total points descending, and extracting a raw copy of that data before some *ahem* light data cleansing and formatting. 

Here’s a quick table of the top 10 ideas in the Marketing Category by total points.

Title	Subcategory	Points ↓
ExactTarget Developer Edition	Platform	18,040
Make Error Logs Available in ExactTarget/Marketing Cloud	Platform	10,830
Ability to see SQL query results, without dumping results into a data extension	Email Studio	8,210
Report on Super Messages	Email Studio	7,520
Engagement Split – Click – Enable dynamic links to be monitored	Journey Builder	5,700
Add Debugging Support for CloudPages	Web Studio	4,910
Recycle bin in Marketing Cloud	Content Builder	4,440
Journey Builder Date-Based Event Evaluate According to Specified Timezone	Journey Builder	4,310
Marketing Calendar	Platform	3,530
Search Bar Across All Folders	Email Studio	3,500
One thought popped into my mind – what if points on their own were not actually indicative of the most desired ideas due to skewing from when the idea was submitted. In other words – was it possible that some of these ideas started the race much earlier than other ideas and that they had an unfair head start because of it (spoiler alert: they didn’t). 

Enter the points-per-day measurement. I normalized the top 100 ideas based on the number of points each had accrued per day, on average, since they were submitted. Funny enough 8 of the top 10 in this category do overlap with the previous table (highlighted in orange), but the order slightly changes.

Title	Subcategory	PPD↓
ExactTarget Developer Edition	Platform	6.29
Make Error Logs Available in ExactTarget/Marketing Cloud	Platform	5.14
Report on Super Messages	Email Studio	4.59
Ability to see SQL query results, without dumping results into a data extension	Email Studio	4.52
Engagement Split – Click – Enable dynamic links to be monitored	Journey Builder	4.03
Journey Builder Script Activity	Journey Builder	3.50
Add Debugging Support for CloudPages	Web Studio	3.00
Instagram Direct Message	Social Studio	2.63
Recycle bin in Marketing Cloud	Content Builder	2.58
Journey Builder Date-Based Event Evaluate According to Specified Timezone	Journey Builder	2.44

You do also see the emergence of a few dark horses, namely the [Journey Builder Script Activity](https://ideas.salesforce.com/s/idea/a0B8W00000GdjPPUAZ/journey-builder-script-activity), submitted by fellow Marketing Cloud Champion Mateusz Dabrowski, which has accrued over 600 points in the first six months after it was submitted, as well as the Instagram Direct Message.

My Superlatives from the Top 100
Swimming in a world of ideas, I wanted to shout out a few of my favorites but also explain their importance in more detail. You might recognize some of these from the tables above, but I’ve peppered in a few others that I find particularly promising. 

The Most Obvious: ExactTarget Developer Edition
There’s no way around this idea – it’s been a perennial favorite, and it relates to perhaps the most frequently asked question surrounding Marketing Cloud – “how can I practice building in Marketing Cloud”. It’s, in my opinion, the holy grail of getting more users to adopt Marketing Cloud successfully. 

Traditionally, email send platforms (or anything that can communicate directly with end customers) has inherent higher risks associated with providing unfettered access to its services. Think you have enough emails in your inbox already (yes, I’m looking at you Ryan – your inbox count gives me the heebies)? That would likely be much worse if anyone could spin up a Marketing Cloud environment and start sending emails to whoever they wanted.

That said, I would make the argument that one of Salesforce’s best growth strategies has been the investment in the infrastructure and processes that allow individuals the ability to easily and quickly spin up a developer environment for their Core CRM products. It also helped them use the same mechanism to improve their Trailhead ecosystem, which improves the educational opportunities available to end users. If they could find a way to provide access to the User Interface in a somewhat consistent manner with what’s available in a live platform, but disable all sending activities, that would fit the best of both worlds.

Benefits

↑ Increase accessibility to learning Marketing Cloud

↑ Increase customer’s ability to “try before they buy”

↓ Time invested by Salesforce Sales teams demoing Marketing Cloud to customers

Best Cross-Channel Support: Data View for Mobile Push (see also: DataViews for MobileConnect)
Data Views are as powerful as any tool in the Marketing Cloud toolbelt, but they are missing a few key pieces. Data Views act as a way for developers to access information related to customer engagement, but they’re primarily exposed only for the Email Channel currently. The only data views that exist for other channels currently are SMSMessageTracking SMSSubscriptionLog, and GroupConnect Contact Subscriptions, but adding others could greatly increase the different use cases that marketers could build.

Benefits:

↑ Improve ability to adopt cross-channel use cases

↑ Increase consistency between channels and available tools + data access

Most Developer-Friendly: Make Error Logs Available in ExactTarget/ Marketing Cloud
It’s an all too common scenario for developers – you’re minding your own business writing code, and when you go to run it, you are hit with an ever-so-helpful error message telling you where you went wrong. 

It reads something like this: Error Code: 827dj2mds6kj23 

Now I may have years of experience with Marketing Cloud, but error codes are only ever as helpful as they are understandable. I haven’t yet become fluent in the foreign language of error codes – many practitioners are in the same boat – and this idea rightfully focuses on making error messages logs much more accessible to end users, instead of needing to rely on submitting tickets to support in order to help debug issues. See also: Actual Error Messages Available in Automation Studio

Benefits:

↑ Improve adoption and platform usability

↑ Increase development time (more clearly and consistently identifies why an issue is occurring)

Best improvement for Customer Success: Consumption Dashboard (aka Report on SuperMessages)
Across the board, I think customers would benefit from having a dashboard that allowed them to accurately track their subscription, particularly any items that are consumption based (like Contacts, SuperMessages, API calls, etc.)  – while I understand the complexity of implementing this idea, the value seems obvious to me, and there are a number of other vendors that allow for tracking your subscription more easily than Marketing Cloud currently supports.

Benefits:

↑ Helps customers understand and forecast their usage

↑ Increases trust between Salesforce and their customers

Honorable Mentions:

Loops in Journey Builder (while I think this idea could have great applications, I think it also could introduce considerable risks)
Search Bars Across (note: DESelect Search is a great browser add-on that might help in the interim)
Evaluating Winning Ideas

Based on the winning ideas to date, no Marketing Cloud idea has yet been selected for delivery. One Pardot idea has been selected as a winner – the only representation of a Marketing product within Salesforce’s portfolio, but that idea isn’t slated for delivery until Spring of ‘23 (okay, given it was prioritized less than two weeks ago, I think that’s a fair turnaround time).

All in all – let’s try to change the narrative in 2022 by getting additional Marketing Cloud ideas prioritized for delivery. The best ways to make that happen are to:

Submit your own ideas on the Salesforce Idea Exchange
Upvote ideas from other contributors that you think are helpful
Participate in prioritization – the next cycle begins on January 24th, 2022!

---

The blog post date can be extracted from filenames, such as:

- `2019-05-30-welcome.md`
- `2019-05-30-welcome/index.md`

A blog post folder can be convenient to co-locate blog post images:

The blog supports tags as well!

**And if you don't want a blog**: just delete this directory, and use `blog: false` in your Docusaurus config.
