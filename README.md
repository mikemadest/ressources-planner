# ressources-planner
Simple planing tool for team and projects.
This is meant as a code and project management showcase,
also it's inspired on current job realcase needs.

Project started 03/11/2017

Roadmap

1. Finishing first specs
2. Zoning
3. Preparing estimated sprints
4. Developpment !
5. Demo !


1. Specs
The goal is to have a simple tool for giving tasks to users,
having a global overlook on project, teams and users occupations.


** Task **
=> has dependancies
  - previous task needed
  - customer validation

=> has risks
  - may take more time than planned
  - may start later than planned
  - may not work the way we want it (R&D, compatibility)
  - specs unclear (so we did it anyway because we couldn't do otherwise XD)
  - no way to get the client to be clear about his needs (WTF)

=> on the contrary
  - can be pushed back, no problem
  - probably something priority related,
  but this way we will have nice picto so it shows in the planning view for deciding purpose.

=> Priority
  - we have to know it this task is mandatory for following tasks

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
- sprint 1 : REST api (Laravel probably or Lumen/Slim once i've established feature list)
- sprint 2 : Angular front
- sprint x : if needed :)