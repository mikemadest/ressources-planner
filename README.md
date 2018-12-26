# ressources-planner
Simple planing tool for team and projects.
Inspired by current job realcase needs.

Important : i won't work on this as long as i'm already working full time.
As it is now, think of this as written ideas on this app that i wanted to keep.

Roadmap

1. Finishing first specs
2. Zoning
3. Preparing estimated sprints
4. Development !
5. Demo !


1. Specs
The goal is to have a simple tool for giving tasks to users,
having a global overlook on project, teams and users occupations.


** Task **
=> has dependencies
  - previous task needed
  - customer validation

=> has risks
  - may take more time than planned
  - may start later than planned
  - may not work the way we want it (R&D, compatibility)
  - specs unclear (so we did it anyway because we couldn't do otherwise XD)
  - no way to get the client to be clear about his needs (WTF)

=> "delayable"
  - can be pushed back, no problem
  - probably something priority related,
  but this way we will have nice picto so it shows in the planning view for deciding purpose.

=> Priority

=> Type
  - new feature
  - bug
  - design
  - etc.

=> start and end time/date : estimated and real ones
maybe it's intersting to know that this task was done quickly,
due to internal pressure, but rushed : no tests, no unit tests... so it's done,
and it look like it works... but : bad code, missing features...

=> this task belong to a project !

=> And it can have a parent task, so we can group tasks


** User **
=> name, surname, group, user type (dev, designer, lead project developper, whatever).

** Project **
=> deadlines
=> client


** Features **
- we want to be able to configure work days
- non worked day, holidays need to be in the planning.
- we want to see deadlines, release dates... Project related infos.
- if a task is sliding, user planning and dependances slides too (checkbox to confirm planning slide).


2. Zoning
... ok, not the point of this demo but i'll try that one, maybe...


3. Sprints
Still to be decided. 
Each sprint has to be something working and i'll probably focus the first one
on mocking the webservice and having a simple UI for the front tool.
Then i'll build the database, webservice. Keeping to the basics.

After that i'll upgrade the app by adding features with the same order :
- mock data + ui
- webservice

So, what's important here is how to start something simple enough
to be made by one guy in 2 - 3 days but still meaningfull.
