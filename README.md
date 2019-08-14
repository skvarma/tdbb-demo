Covering
MS Teams Channel - Salesforce Learning
Trailhead login
  - Navigate to Trail mix
Navigating Trailhead 
    - Modules, Trails, Trailmixes
    - Certifications, Career Paths
    - Trailhead Playground Management
Trailmix - Admin , Dev, CRM Basics - https://trailhead.salesforce.com/en/users/svarma/trailmixes/tdbb-sfdc
Starting with building a very basic app
Follow along (questions at end of each module) (Wait 5 - 10 mins)
Channel for questions
Basic Fields created - Query Object - Id field, __c
Create Fields - __c, query
Create App
Create Reports
Metadata Extract
    - sfdx force:source:retrieve -n test

 Pre Session Work
  - Admin Beginner
    - Salesforce Platform Basics
    - Data Modeling
    - Data Management
    - Lightning Experience Customization
  - Admin Intermediate
   - Formulas & Validations
 Next Session
   - review Questions
   - Data Security  




---------------
User u = [Select Id from user where Name like '%kumar%' LIMIT 1];
System.setPassword(u.id,'SFDCpassword1');
