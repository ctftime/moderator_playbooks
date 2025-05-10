CTFtime Moderation How-To
=========================

*This repo is community-managed*

Here is a documentation for moderation process at CTFtime.org.


What is a CTF and What is an Event
==================================

A *CTF* is a series of events managed by one or more *Teams*. CTF is an aggregation key for events.
CTFs do not have specific date frames.

An *Event* is a specific event within a CTF series. Events always have specific dates and times.
The same team can manage multiple CTFs or Events.
Events have organizers.

### Event Formats
* Attack-Defense
* Jeopardy
* Hack quest

### Locations
* On-line
* On-site

### Rule Restrictions
* Academic-only
* Individual participation
* Prequalified
* Other unspecified restrictions

### Event Weight
Events can be *casual* – this type of events always has 0 weight.
Events can be *votable* – weight is determined through participant voting.


Moderating CTFs
===============

In most cases, after a team creates a CTF, we just approve it.
Here are some non-standard cases.

### CTF lacks relevant information (e.g., no URL, description)
* We reject the CTF

### CTF has a spammy description
* We reject the CTF

### CTF mistakenly created instead of an Event
* We edit CTF name / slug / description to remove references to specific event, and instruct organizers to create an Event in this CTF.

### Duplicate CTF name
Sometimes organizers forget they've already created a CTF, create a new team and lose control of their existing CTF series.
* We figure out why this happened and change CTF owner if required.


Moderating Events
=================

After a team's CTF is approved, they can create events.
We verify whether:
* the event has relevant information for participants
* dates and times are correct
* the event format, location and restrictions are specified correctly
* the event should have any weight

## Determining Event Approval

We reject events imposing the following restrictions on participants:
 - human race
 - gender (exception: CTFs specifically oriented toward women, unless such events become equal or a majority)
 - religion

We accept other events if they do not look spammy (e.g., a lot of similar events under the same CTF).

## Determining Event Weight

Events should have zero weight in the following cases:

* The event only allows individual participation
* The event only allows academic-affiliated participantion
* The event requires attending a paid conference, except for finals covering entrance for qualified teams
    * However, events allowing on-line participation but awarding prizes only to on-site or academic participants are still eligible for weight
* Event organizer intentionally marked it as "casual"
* Organizer did not upload a scoreboard within the voting period (7 days after the event)
* If the previous event of the CTF was run more than 18 months ago, weight voting starts at 0 instead of previous event's weight (this rule should be reviewed, maybe the weight should be reduced instead)

## On-site Events

There is a discussion on how to assign weight to on-site events. Historically, there were prominent on-site finals with huge weight:
* DEF CON CTF Finals
* HITCON
* 0CTF/TCTF
* Dragon CTF
* Midnight Sun CTF

All these CTFs require passing an online qualification round and cover some expenses for the teams to come on site.

However, there is a lot of non-zero weight on-site events that do not offer any support to participating teams. Some of them restrict participation on national basis. At the moment there are no specific rules on whether to assign weight to such events or not.
These rules should be reviewed.


Team Membership Requests
========================

* If a team already has existing members, only those members can approve new membership requests. They can also share their team invite token with the participants they want to join.

* If a team has no members, anyone can freely join. There are simple anti-spam mechanics to prevent team squatting; suspicious requests require manual moderation.


Team Merge Requests
===================

Sometimes a team plays under a new name without first adding the name as team alias on CTFtime.

New teams are created automatically for every new name in an imported scoreboard. These teams have no members and can be joined freely.

After the team has some members, a "team merge request" can be submitted to claim the results and add the name as an alias to some existing team.

Team merge restrictions:
* The user submitting the merge request must be a member of both teams
* The two teams must not have participated in the same event
* At least one of the teams must have participated in some event in the last 14 days

These rules should be reviewed. Proposed additional restrictions:
* A team can only be merged as an alias during the year of its creation. If a team has event results from previous years, it cannot be merged
* No team merges can happen for two weeks at the end of the season (December 18 to 31)
