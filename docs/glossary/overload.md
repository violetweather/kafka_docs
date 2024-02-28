# Overload Reviews

### Definition
The Overload Review system is used to communicate reviews across several commands using **[MongoDB](https://www.mongodb.com)** as the main database. All the reviews are stored online, these are not visible to anyone with the exception of **[Bot Moderators](/docs/glossary/moderators)** using moderation commands. 

:::info
**[Bot Moderators](/docs/glossary/moderators)** use a separate bot that is only able to find information with Review IDs provided in reports.
:::

The system manages all requests through a class that handles interactions with the commands and database seamlessly. While there are many privacy precautions in place, please do not consider this system private, nearly all of the interactions in Overload Reviews are public.

Reports are taken very seriously, action will be taken in less than 24 hours. That being said, abuse of the report system will have your account placed in the **[K-Block](/docs/glossary/k-block)** list permanently. The actions taken on the report will remain private.

:::note
Appeals can still be made at support@koohii.moe!
:::

### Reviews
Reviews consist of a star rating from 1 to 5 stars and a review comment limited to 30 characters.
Once a review is made, the user reviewed has a review profile made of them. That review profile is shown in multiple places, the **[info command](/docs/context/utility/info)**, and **[reviews command](/docs/context/utility/reviews)** - both of which can access reviews publicly. When participation is toggled off, both of these are not accessible by anyone. If a report is made, toggling participation will not bypass the report.

### Participation
Users can choose to **[opt out](/docs/context/utility/reviews#configurate-overload-reviews)** of the system at any time! This does not delete any review data, all review data can only be deleted by manually requesting deletion from support@koohii.moe.

### Direct Message Notifications
To ensure that users do not receive unwarranted reviews, face possible harrassment, etc - by default, all users will be notified by DM whenever a new review is made to them. This can also be **[toggled off](/docs/context/utility/reviews#configurate-overload-reviews)** to avoid unnecessary DM clutter.