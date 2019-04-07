# Tech For Better Project Process
- Created by Joe & Simon of T4B1

This outlines the overall recommended process for each Tech For Better (TFB) project. This is an ongoing process and open to iteration as further projects are delivered.

## Project Selection

The following steps must take place before the project can begin

- Project is to be selected from the TFB applicant backlog
- Potential PO must have attended at least the ‘Discovery’ workshop
- TFB London participants to host a ‘Definition’ workshop with the potential POs
- Once selected, all TFB participants have a 2-hour meeting without PO. In this meeting:
  London participants to provide and present a slide deck taking the Gaza participants through the project, including the problem, defined solution so far and potential scope discussed
- All participants to fully understand the project and agree the general scope they are comfortable with in this meeting
- Agree team roles (e.g. Scrum Master, DevOps)
- Agree the project process (i.e. using Github Project Kanban, agreeing how people clearly pick up issues etc)
- PO to sign a project contract (TBC)

## Project Process

### Set up

Due to the remote working and that the London and Gaza participants will likely not have worked together before, there are a number of important bits that must be set up. These should all be set up before the project begins.

#### Gitter team room

#### Google Meeting Link and Calendar Event for the daily stand up and weekly retrospective

#### User Manual

Each participant should fill in their user manual so everyone knows in the team how they like to work

#### Preferred Tech Stack

It is important to highlight what you feel confident in and what you might like to learn during each project

#### Project Mentors

There needs to be 2 mentors per project - one in Gaza and one in London. Both should be added to Gitter and will contribute to the overall team, but are also on hand for any personal help any participant needs. We recommend finding someone who can be a code reviewer maybe specialising in an area you feel best suited for each project.

#### Bio and Image

For marketing purposes and also for the funders of the project, it is important for each team member to supply an image of themselves and short bio answering:
-Quick background of who you are

- How you got into coding
- What brought you to the Tech for Better project

### Timings

The project takes place over 4 working weeks. Working times can vary but generally they are (all times in GMT):

- London: Monday to Friday 10am to 6pm
- Gaza: Sunday to Thursday 6am to 2pm
- Team stand up: Monday to Thursday at 10am
- Weekly retrospective: Thursday at 10.30am (straight after the stand up)
- Code Sharing (Thurs at 11ish, after the retro)
- One or more members present on something the others would like to learn or know about in the code base. This is a great way to learn throughout.
- Daily Stand Up Log:
- This is an Issue that you create in each project repo with the idea that everyone at the end of each day writes up what they did, what they plan to do and any blockers. This means there’s less issues with the team stand up happening midday Gaza time. Example here

### Schedule

Overall recommended schedule for the 4 weeks:

- Week 1: Project set up, Design/Prototyping & User Testing
- Week 2-3: Core build sprint
- Week 4: Debugging, Testing & Bonus features

It is recommended for each project to start on Monday. This ensures you agree the scope and then have enough time that week to do the design, with the aim for London participants to carry out the user testing on the Friday and then synthesize the results for the Gaza participants, who on Sunday do further revisions based on the feedback and/or set up the project environment ahead of the first week of building.

### Key events:

#### Project Kick Off Meeting with the PO (day 1)

This meeting is crucial for the Gaza developers to meet the PO and for everyone to fully agree on the scope of the project. Key outcomes:

- Present what is expected of a PO
- Agree the core features for the scope
- Set up the PO on Github
- Agree the project schedule including project handover

#### Project Handover

This takes place on an agreed date after week 4 and features the whole team plus the PO. Key outcomes:

- Project review
- End of sprint bug list
- Further sprint recommendations
- Any required admin (e.g. database log-in)

#### Final Team Retrospective

- This takes place on an agreed data and features the whole team. Key outcomes:
- Final team retrospective
- Review of the process and what can be improved

### Roles

Due to the client being based in London, it is recommended that the Scrum Master is one of the London participants, and DevOps is one of the Gaza participants. Additional roles can be created if agreed within the team.

### Additional Recommendations for efficient teamwork

With your team split geographically and working different days and times, it is vital to focus on process that everyone fully agrees on and understands.

#### Clear issues and process

It is vital that the whole team can clearly see what needs to be worked on and also that there is a clear process in place so people know at any time (regardless of who is and isn’t working at that point in time) on what issues are being worked on and what issues they can pick up. It is recommended to use the Github Project Kanban so all team members can easily drag into in progress what they’re working on

#### Clear process for PRs:

- Approval criteria (e.g. code coverage %, no console logs)
- Labelling (e.g. ‘Awaiting Review’, ‘In Review’, ‘Do Not Review Yet’)
- Reviewing etiquette (e.g. can the person reviewing make changes or must they raise an issue so the person who created the PR is solely responsible for that branch)
- Eslint and code formatting set up
- Consistent file naming style (e.g. camelCase)