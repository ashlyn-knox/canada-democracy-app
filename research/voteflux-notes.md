# Notes on Social Polling App
## Time tracker
* may 19: 12-1

## Signup notes
* Only legal information
* postal code and address and dob required

## Voting App Examples
* cannot get cause I'm not an Aussie
* Gives the ability to swap votes on issues you don't care about... This is a feature that could easily be abused
  - Allows individuals to gain political capital
  * 

## My Review Notes
* **TODO**: Build in a way that takes the percentage of population voting on a given issue.
  - App should not be able to be overtaken by a small loud minority, or essentially be a tally viewer of groups that feel strongly on a particular issue.
* **TODO**: Address how this app negotiates relationship between voters and their representitive
* **NOTE**: Concern about app concept in pure form being too ahead of its time.
  - UI: It will need to look and feel offical and professional, but still have aspects of social media that are designed to promote usage
  - What will make users care and get excited?
  - What are key motivators? positive feedback system
  - How to keep users on but avoid political burnout

## Tutorial and App Building Methods
* [Social Poll App Tutorial](https://pusher.com/tutorials/social-poll-realtime-counter)
    - MERN or MEVN stack
    - Vote POST and GET request endpoints


### Australian Voting App
* [Voteflux Github](https://github.com/voteflux)
* [Voteflux](https://voteflux.org/about/how/) is a direct democracy voting app used in Australia. it currently has about 8933 members registered.
    - Aimed at redistributing political power and offering citizens a direct way to engage with political policy
* Values of VoteFlux
  - People **all people** and their differences
    - free and open society - freedom of speech, association, and free flow of political ideas
* [Review of Voteflux from 2016](https://catespeaks.com/2016/05/13/meet-the-small-parties-voteflux-upgrade-democracy/)
  - CRITIQUE: While the app is idealistic and probably great for people who are smart and progressive, it can be easily manipulated by special interest groups.
  - POINT: requires that senators who collaborate with flux will commit to vote the will of the people as determined by the app
    - Puts political figures in an uncomfortable position
  - CRITIQUE: Based on what group will best organize themselves to vote 
  - QUESTION: **how to balance between people who have strong/apathetic feelings on an issue to people who are hyperpolitized/disenfranchized?**

#### UI Design Notes
* Users search through different bills organized as cards
* Bills are shown with a basic overview **NOTE WHO WRITES THIS? IS IT COPIED FROM OFFICIAL BILL?**
  - More info setion to full bill text
  - Tags used for showing different interests
  - Visual bar with percentages showing for and against votes at present -- can this be used to positively or manipulatively affect how people think?
    - **social motivation**
#### Financial Stuff
* uses blockchain
#### Build Notes
* Dart, Python are two main languages
* Votes are stored as JSON data
* [Voting app API](https://github.com/voteflux/voting-app-api)
