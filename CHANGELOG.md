## Introduction

The purpose of this document is to be transparent about the changes that have been made to the [App Mining program](https://app.co/mining) since its launch. The program is a work in progress, and we encourage everyone to participate in the evolution of App Mining by discussing and opening [issues](https://github.com/blockstack/app-mining/issues) in our GitHub.

### Format of the Changelog

Because App Mining operates in monthly cycles, we have broken down the changelog into monthly groups. Each month has three sections:

- **Operational Changes:** Updates that have made an actual change in the program. This might be new documentation, changes to payout structure, changes to reviewers, changes to ranking calculations, etc.
- **Dry Run:** These are changes that have been made, but will not have an effect in that month’s final rankings. When we make a big change, like adding a new reviewer, we usually run a “dry run” so that we can see what the results would be, without actually making them final. This allows the community to evaluate the changes before they’re finalized.
- **Discussions Finalized:** These are largely discussions made from GitHub issues that have been debated, but no actual operational changes were made. These discussions all influence potential decisions in the future of the program, but will not be actualized at this time.

## Changelog by Month

## August 2019 
- Operational Changes: 

  - Payout Schedule [#116](https://github.com/blockstack/app-mining/issues/116) 
      - **Result:** Changed the app mining audit period to last through a week after the 15th (or the next weekday). Payouts are now 7 days following the start of the audit period. (E.g. for August 2019, payouts will be on the 22nd.)
  -  Audit Period Changes and Payout Criteria [#126](https://github.com/blockstack/app-mining/issues/126) 
     - **Result:** With an extended audit period, app founders must report necessary changes within the audit period. Outside of the audit period, if an error is found, the error should be updated but no difference in payment will be made unless the error was egregious at the discretion of Blockstack PBC.  
     
  

### July 2019 
- Operational Changes:

  - Audit Results Changelog[#124](https://github.com/blockstack/app-mining/issues/124) 
      - **Result:** Changes to the App Mining audit results can be found [here](https://docs.google.com/spreadsheets/d/1WrsyBdrqapZN-fv5VeD8SgU15CVnqAmnKVUHUMYiNkY/edit#gid=0). 




### June 2019 
- Operational Changes:

  - Audit and Payout Schedule [#116](https://github.com/blockstack/app-mining/issues/116)  
    - **Result:** Extending the app mining audit period to the end of the month, payouts are now ~at the end of the month~ 7 days following the start of the audit period. (E.g. for August 2019, payouts will be on the 31st.)




### May 2019

- Operational Changes:
  - TryMyUI Audiences [#1](https://github.com/blockstack/app-mining/issues/1)  
    - **Result:** App Miners have the option to add product based audience filters to their TryMyUI testing. 
  - Product Hunt Scoring [#106](https://github.com/blockstack/app-mining/issues/106) 
    - **Result:** Implementing a Decay score for Product Hunt ranking: the new score is your 'total upvotes' score, but with a monthly decay function of 90%. So if you have a total of 100 upvotes, and you launched 1 month ago, you have 90 total upvotes. The final score is total_credible_upvotes*0.9^months_since_launched.
  - Pause Democracy Earth as an App Reviewer [#92](https://github.com/blockstack/app-mining/issues/92) 
    - **Result:** Democracy Earth has been paused as an app reviewer and will not be included in May's ranking or moving forward until further notice.
  - All apps must be https secure and have a dedicated domain [#105](https://github.com/blockstack/app-mining/issues/105)
    - **Result:** All apps must be https secure and have a dedicated domain in order to be eligible for App Mining. Apps that were not https secure or who lacked a dedicated domain were emailed about the change starting in June.  
  - Awario results to be shared at the start of each audit period [#108](https://github.com/blockstack/app-mining/issues/108) 
    - **Result:** The Awario results of the previous month will be emailed to app miners at the start of each audit period until App Miners are able to login to explore the data on Awario directly. 
  - TryMyUI Tests Upgraded [#90](https://github.com/blockstack/app-mining/issues/90)
    - **Result:** App Miners receive 10 TryMyUI testing videos. The highest and lowest scores get dropped. 
  - Communicate Important Information via Email [#110](https://github.com/blockstack/app-mining/issues/110)
    - **Result:** App Miners will receive an email at the start of each month with that month's scoring criteria. 

- Discussions Finalized:
  - All apps reviewed by all reviewers [#91](https://github.com/blockstack/app-mining/issues/91)
    - **Result:** All apps must be reviewed by all app reviewers. It will be up to the discretion of the app reviewers how they will review unconventional apps. 
  - Awario scoring to continue as is [#109](https://github.com/blockstack/app-mining/issues/109) 
    - **Result:** All apps will continue to receive Awario scores from all publications found, both centralized and decentralized. 
  - Blockstack PBC to exclude clone apps from App Mining [#113](https://github.com/blockstack/app-mining/issues/113) 
    - **Result:** It is at the discretion of Blockstack PBC to identify an app as a clone (not having significant upgrades) and can exclude clone apps from registering for the program. 
 

    

### April 2019

- Operational Changes:
  - Adding our digital rights reviewer into final scores. 
  - Decrease weight of memory function [#69](https://github.com/blockstack/app-mining/issues/69)
    - **Result:** The memory function has been decreased from 45% to 25%. You can read more about the memory function and algorithm in this [blog post](https://blog.blockstack.org/app-mining-game-theory-algorithm-design/).
  - Implement community audit [#50](https://github.com/blockstack/app-mining/issues/50)
    - **Result:** Blockstack PBC will share the App Mining Results with App Miners via email two business days before implementing payouts for full community audit.  
- Dry Run:
  - Product Hunt to change ranking input to number of upvotes that month [#78](https://github.com/blockstack/app-mining/issues/78)
    - **Result:** Decided to run a test on this for the month of April (not to be included on Rankings).
  - Adding a new awareness app reviewer with Awario [#30](https://github.com/blockstack/app-mining/issues/30)
- Discussions Finalized:
  - Include open source in ranking criteria [#42](https://github.com/blockstack/app-mining/issues/42)
    - **Result:** Digital Rights App Reviewer can consider adding to their ranking.
  - Digital Rights Reviewer Criteria [#79](https://github.com/blockstack/app-mining/issues/79)
    - **Result:** Shared reviewer scoring [pdf](https://github.com/blockstack/app-mining/blob/master/DigitalRightsAuthScoringCriteria.pdf). 
  - Digital Rights Reviewer Score Format [#83](https://github.com/blockstack/app-mining/issues/83). 
    - **Result:** Apps are rated in consecutive integer format.
  - Gaia treatment by Digital Rights App Reviewer [#59](https://github.com/blockstack/app-mining/issues/59)  
    - **Result:** Digital Rights App Reviewer set up a custom gaia hub so that mobile apps are treated fairly.
  - Digital Rights App Reviewer Authentication Assesment [#60](https://github.com/blockstack/app-mining/issues/60)  
      - **Result:** Digital rights reviewer will not provide an exact testing environment, but will test various environments changing month to month. Review will be conducted on the current public release of mac, windows, ios or android with either the default browser on the platform or the current release of chrome or firefox. If your app fails this test, by definition you're not eligible for App Mining since your app does not have working Blockstack auth. For April App Mining, the Digital Rights reviewer will test all apps, then notify all the apps that fail via email. Then 48 hours later, the failing apps will be retested. Only then will they be disqualified for the April cohort. We may reevaluate if needed. 

### March 2019

- Operational Changes:
  - Publish guide on best practices for App Mining [#21](https://github.com/blockstack/app-mining/issues/21)
    - **Result:** [Published the guide](https://docs.blockstack.org/community/app-miners-guide.html) and shared with App Miners.
  - Hello-World Apps Not Qualifying for App Mining [#34](https://github.com/blockstack/app-mining/issues/34)
    - **Result:** Clarified in our [docs](https://github.com/blockstack/app-mining/issues/34) that Test Flight apps, hello-world apps, and apps created through Blockstack tutorials (e.g. animal kingdom apps) do not qualify for App Mining.
  - Digital Rights Reviewer: Evaluation of Indexers [#58](https://github.com/blockstack/app-mining/issues/58)
    - **Result:** Digital Rights Reviewer will not dock points for using gaia with indexers.
  - Removed Product Hunt’s “Team Score” from app rankings
  - Only calculate Product Hunt’s “Community Score” from credible upvotes
  - Announce Awario [#57](https://github.com/blockstack/app-mining/issues/57)
    - **Result:** Awario is officially an app reviewer! Full details in [announcement](https://blog.blockstack.org/introducing-awario-app-reviewer/).
- Dry Run:
  - Shipped v1 of Digital Rights Reviewer [#8](https://github.com/blockstack/app-mining/issues/8) also [#56](https://github.com/blockstack/app-mining/issues/56)
    - **Result:** [Announced](https://blog.blockstack.org/introducing-new-internet-labs-the-digital-rights-reviewer-for-app-mining/) New Internet Labs as digital rights reviewer.
- Discussions Finalized:
  - App Miners can submit more than one app for app mining [#39](https://github.com/blockstack/app-mining/issues/39)
    - **Result:** Yes, App Miners can continue to submit more than one app per person/team.
  - Reward Apps that solve the same problem only once [#37](https://github.com/blockstack/app-mining/issues/37)
    - **Result:** Issue closed in favor of free-reign and development. There are issues with the complexity around accurately sorting and comparing apps.
  - App Mining Rules for Hardware Apps [#35](https://github.com/blockstack/app-mining/issues/35)
    - **Result:** Determined hardware apps are eligible but in some cases cannot be reviewed with the same methodology. Revised the review methodology so that the app is neither penalized nor rewarded for exclusion from being reviewed and updated the [FAQ](https://blog.blockstack.org/free-blockchain-application-ideas/).
  - TryMyUI assessment of App Flow [#52](https://github.com/blockstack/app-mining/issues/52)
    - **Result:** Apps need to be designed for app users who do not know anything about Blockstack. Every app is in the same boat on the assessment.
  - Product Hunt feedback on reviews: [#3](https://github.com/blockstack/app-mining/issues/3) and [#55](https://github.com/blockstack/app-mining/issues/55)
    - **Result:** Product Hunt added feedback for new apps the month of February. That led to a larger decision of removing the internal product hunt scoring component.
  - TryMyUI to focus on UX of app vs. onboarding [#71](https://github.com/blockstack/app-mining/issues/71)
    - **Result:** Confirmed with TryMyUI that tests are reviewed and audited. App developers will be tested on their onboarding flow as part of this.
  - Blockstack PBC employees helping Apps [#48](https://github.com/blockstack/app-mining/issues/48)
    - **Result:** Discussed, no real problem with this yet and many open questions. Closed until it needs to be readdressed.
  - Apps awarded that do not show active product development [#64](https://github.com/blockstack/app-mining/issues/64)
    - **Result:** Discussed, and concluded that judging on product development was subjective and not always a sign of good progress.
  - Product Hunt score only rewards a good launch, not quality over time [#73](https://github.com/blockstack/app-mining/issues/73)
    - **Result:** Product Hunt scores will decay over time. Apps can be rehunted as well with new releases. We will also include a score based on the change in your app’s upvotes from month to month.

### February 2019

- Operational Changes:
  - Publish App Mining Readme [#29](https://github.com/blockstack/app-mining/issues/29)
    - **Result:** Published a [first draft](https://github.com/blockstack/app-mining/blob/master/README.md).
  - Add Product Hunt Process Info and Contact Email [#20](https://github.com/blockstack/app-mining/issues/20)
    - **Result:** [A](https://github.com/blockstack/app-mining/issues/20)[dded](https://github.com/blockstack/app-mining/issues/20) to App Mining FAQ.
  - Clear App Mining registration deadlines/timelines [#22](https://github.com/blockstack/app-mining/issues/22)
    - **Result:** Added a [timeline](https://docs.blockstack.org/community/app-miners-guide.html) and calendar to App Mining FAQ.
  - Add FAQ for Investors on Democracy Earth [#19](https://github.com/blockstack/app-mining/issues/19)
    - **Result:** [P](https://docs.blockstack.org/develop/vote-blockstack.html)[ublished docs](https://docs.blockstack.org/develop/vote-blockstack.html) on the Democracy Earth voting process.
  - TryMyUI Testing Methodology for Mobile Apps [#16](https://github.com/blockstack/app-mining/issues/16)
    - **Result:** Apps that support both Android and iOS receive 4 tests of each environment..
  - TryMyUI Instructions for Mobile Apps [#15](https://github.com/blockstack/app-mining/issues/15)
    - **Result:** Confirmed that Android apps are able to direct TryMyUI testers to their app homepage instead of the Android Play Store. Cannot be solved on iOS, so TryMyUI testers are sent directly to the app page in the Apple app store.
  - Ensure that no apps can purchase feature position on PH [#4](https://github.com/blockstack/app-mining/issues/4)
    - **Result:** PH has confirmed that they are blacklisting the apps in App Mining from purchasing this feature. It is still manual, so App Miners please flag if they are seeing otherwise.
  - TryMyUI instructions improved: [#2](https://github.com/blockstack/app-mining/issues/2)
    - **Result:** Shipped new instructions that are less biased toward certain app behaviors.
- Discussions Finalized:
  - Reference Principles of Blockstack apps [#38](https://github.com/blockstack/app-mining/issues/38)
    - **Result:** Closed in favor of Digital Rights Reviewer partnership.
  - Criteria for Democracy Earth voting to be based on stage of product [#54](https://github.com/blockstack/app-mining/issues/54)
    - **Result:** Discussed, agreed that there is room for improvement in the impact of voters and apps but that this specific change was not desired.

### January 2018

- Began sharing full results publicly as a spreadsheet, so you can look at calculations and audit results
- Added TryMyUI as an app reviewer, with app developers getting access to user testing videos.

### December 2018

- Moved to \$100,000 for total amount of payouts
- Ran an internal dry run with TryMyUI to evaluate adding them as a new reviewer

### Alpha run (September 2018)

- Added Product Hunt as an app reviewer
- Added democracy earth as an app reviewer
- Started the total amount of payouts as \$25,000
