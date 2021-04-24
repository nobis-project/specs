# Features for MVP Nobis

**Introduction**
Below is the breakdown of suggested features to be achieved for an MVP. Features are represented as EPICs and complemented with respective User Stories.
This can considered as the basic representation of the product's roadmap.

## Epics

### *NBS-2: Hashtags*

Hashtags represents the user's points of interests and a set of criterias to find new matches

List of user stories:
##### HT-1: As a user, I want to see a seperate hashtag page
##### HT-2: As a user, I want to see the list of most popular hashtags in the beginning of the hashtag page
##### HT-3: As a user, I want to search a hashtag by keywords
##### HT-4: As a user, I want to create a hashtag
##### HT-5: As a user, I expect no duplication for the same hashtag name
##### HT-6: As a user, I want to add a searched hashtag to my profile
##### HT-7: As a user, I want to see the chosen hashtags
##### HT-8: As a user, I want to delete the chosen hashtags
##### HT-9: As a user, I want to change my hashtags selection
##### HT-10: As a user, I want to receive proposal to change my hashtags biweekly with a set of new hashtags
##### HT-11: As a user, I want to see the list of chosen hashtags


### *NBS-3: User's Profile*

List of user stories:
##### UP-1: As a user, I want to upload my avatar
##### UP-2: As a user, I want to create my nickname
##### UP-3: As a user, I want to see the numbers of chosen hashtags in my profile
##### UP-4: As a user, I want to navigate to hashtags page from my profile
##### UP-5: As a user, I want to set my profile status
##### UP-6: As a user, I want to see the status options in my profile (ready, busy, ghost)
##### UP-7: As a user, I want to see the numbers of new acquintances in my profile
##### UP-8: As a user, I want to navigate to achievements' page from my profile

### *NBS-4: User's Achievments*
The motivation of achievements is in visualizing to user the sense of learning or obtaining new experiences in his/her/their lives

List of user stories:
##### UA-1: As a user, I want to see a separate screen of achievements
##### UA-2: As a user, I want to see divided sections of achievements by topics
##### UA-3: As a user, I want to see my progress for every achievement
##### UA-4: As a user, I want to see nobis' achievements separately from mine generated
##### UA-5: As a user, I want to see nobis' achievements regarding reality inception topic
##### UA-6: As a user, I want to see nobis' achievements regarding profile topic

### Set of nobis' achievements:
#### Profile achievements
1. MVU - Minimum viable user -> Describe yourself enough to be found by others
2. Hashtag Spree -> Choose more then 3 hashtags to your profile
3. Always on Communication -> Stay in "Ready" status for the whole day and get at least 3 new matches during the day, night and midnight
4. Chameleon -> Change your set of hashtags once a week 4 weeks in a row
5. Ghost town -> Stay in "Ghost" status for 2 days in a row

#### Reality Inception
1. Baby Steps to Giant Strides -> Get your first new match
2. "Tony Lip" Mode -> Get 4 new matches during 1 hour
3. Never Miss a Beat -> Accept/Deny 10 new matches in a row
4. "Yes Man" Mode -> Accept 10 new matches in a row
5. Why so nitpicking? -> Deny 5 new matches in a row

### *NBS-5: Reality Inception*
List of user stories:
##### RI-1: As a user, I want to recieve an audio notification on a found match
##### RI-2: As a user, I want to recieve a visual notification on a found match while the mobile phone is locked 
##### RI-3: As a user, I want to recieve a visual notification on a found match while the app is in background mode
##### RI-4: As a user, I want to see a separate screen shown to me for a found match after tapping on the notification
##### RI-5: As a user, I want to see a separate screen shown to me automatically for a found match during active usage of the app
##### RI-6: As a user, I want to have a choice to accept/deny/ignore the new match
    Accept/Deny are states when the user is clicking on either of options. Ignore is a state when the user is doing nothing
##### RI-7: As a user, I want to have limited time to make a decision upon the new match
    To have a more detailed perspective of this story, the user is expecting to see a timeclock visualisation (e.g. 20 seconds)
##### RI-8: As a user, I want to have a visual guidance to my new match in separate screen after acceptance from both sides
    A great example of the implementation is Apple's new UX/UI approach of AirTag system. We need to follow the same guidelines
##### RI-9: As a user, I want to have a cheatsheet while moving towards my new match
    Cheatsheet and Guidance should be switchable between each other, but still providing meaningful information to the user
##### RI-10: As a user, I want to end an active session on the phone
    The session is active if 2 phones are close to each to other, meaning the converstaion is still ongoing. The session can be expired by a)user's interaction or b) distance between 2 phones are far enough
##### RI-11: As a user, I want to review the conversation with my new match afterwards the session expiration
    Need discussion with ML engineers, UX/UI designers and basic research of what data sets are useful


### *NBS-6: Communication Topics aka Cheatsheet* 
List of user stories:
##### CT-1: As a user, I want to have communication topics in a separate screen
##### CT-2: As a user, I want to have visual guidance to the match in the separate screen
    Should be accopmpanied to RI-9
##### CT-3: As a user, I want to have topics devided into groups
##### CT-4: As a user, I want to have a most-relevant sentence-hint below of each group
##### CT-5: As a user, I want see a list of start-sentences after choosing a specific topic
##### CT-6: As a user, I want to leave a review for sentences used during a conversation with a match 
    Same as RI-11
    Need discussion with ML engineers, UX/UI designers and basic research of what data sets are useful



###### tags: `Nobis` `MVP`
