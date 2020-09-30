# Continuous Integration and Continuous Delivery and Continuous Deployment.





## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [Continuous Integration. CI.](#continuous-integration-ci)
* [Continuous Integration Practices.](#continuous-integration-practices)
* [Common Continuous Integration Build Servers.](#common-continuous-integration-build-servers)
* [Continuous Delivery.](#continuous-delivery)
* [Continuous Deployment.](#continuous-deployment)
* [Articles.](#articles)
* [Conferences.](#conferences)
* [Conference Speakers.](#conference-speakers)
* [Courses.](#courses)
* [Books.](#books)
* [Help.](#help)





## About.





## Documentation.





## Continuous Integration. CI.
* Is a development practice that requires developers to integrate code into a shared repository several times a day. 
  Each check-in is then verified by an automated build, allowing teams to detect problems early. - ThoughtWorks
* “Continuous Integration doesn’t get rid of bugs, but it does make them dramatically easier to find and remove.” - Martin 
  Fowler, Chief Scientist, ThoughtWorks





## Continuous Integration Practices.
* CI Practices per Martin Fowler:
  * Maintain a Single Source Repository
  * Automate Build
  * Make Your Build Self-Testing
  * Every Commit Should Build on Integration Machine
  * Fix Broken Builds Immediately Keep the build fast
  * Test in a Clone of the Production Environment
  * Make it Easy for Anyone to get the Latest Executable Version
  * Everyone Can See What is Happening
  
  
  
  
  
  
## Common Continuous Integration Build Servers.
* Self-Hosted:
  * Jenkins, Bamboo, TeamCity, Hudson
  * Fun-Fact - Jenkins forked from Hudson in 2010 due to a legal conflict with Oracle
  
* Cloud Based:
  * CircleCI, TravisCI, Codeship, GitLab CI, AWS CodeBuild
  * And many, many more
  
  
  
  
  
## Continuous Delivery.
* Process to Automatically Deliver code changes directly to the Production Environment
* Involves a High Degree of Automation in Testing and Deployment
* Must have a *VERY* Mature Process
* Can be Difficult in Some Industries due to Regulatory Requirements
* This area is evolving.
  * Few Hard “Rules” - No Standard Way
  * “Best Practices” are maturing, and still a lot of lively debate! 





## Continuous Deployment.
* Continuous Deployment will automatically deploy build artifacts after all CI tests have run.
* Should Happen with every Commit
* Completely Automated
* May Include a Staging Area from which Additional Automated Tests are run
* Easily Confused with Continuous Delivery
* Example: AWS CodePipeline




## Technologies.
* [Canary Deployments.](https://www.google.com/search?q=canary+deployments&oq=Canary+deployments&aqs=chrome.0.0l6.7275j0j7&sourceid=chrome&ie=UTF-8)
* [Blue-Green deployment.](https://www.google.com/search?newwindow=1&safe=active&sxsrf=ALeKk01vx7fsdPZAgxItklPzaPdZ_TXdXQ%3A1585307679825&ei=H-B9XsX5McTMUdqttLgE&q=blue%2Fgreen+deployment&oq=blue%2Fgreen+deployment&gs_l=psy-ab.3..35i39j0l2j0i20i263l2j0l3j0i203j0.989.2810..3601...0.2..0.106.903.10j1......0....1..gws-wiz.......0i71j0i22i30j0i333.EYzS1bOgy_A&ved=0ahUKEwiFhfaow7roAhVEZhQKHdoWDUcQ4dUDCAs&uact=5)
* [Rolling deployment.](https://www.google.com/search?newwindow=1&safe=active&sxsrf=ALeKk01nldH1RbOhJC6LDqsUhp9GNpZZIQ%3A1585308866615&ei=wuR9XrSUJYKWjLsPhOGj0As&q=rolling+deployment&oq=rolling+deployment&gs_l=psy-ab.3..35i39j0j0i20i263j0l7.21355.22044..22959...0.2..0.116.663.7j1......0....1..gws-wiz.......0i71j0i22i30j0i22i10i30j0i333.8whI2wzOzS4&ved=0ahUKEwi0_enex7roAhUCC2MBHYTwCLoQ4dUDCAs&uact=5)





## Articles.





## Conferences.





## Conference Speakers.





## Courses.





## Books.





## Help.
