CTFtime Moderation how to
--------------------------
*This repo is community-managed*
Here is a documentation for moderation process at CTFtime.org.

# What is a CTF and What is an Event

*CTF* is a serie of events, CTFs are managed by some *Team* (s). CTF is an aggregation key for events.
CTFs does not have specific dataframes.

*Event* is a specific event within the CTF. Event always has specific datetime frames.
Same Team can manage multiple CTFs or Events. 
Events have organizers.

# Event format
* Attack-defence
* Jeopardy
* Hack-quest

# Physical limits
* Online
* On-site

# Rule Restrictions
* Academic-only
* Single player
* Prequalified
* Othen unspecified

# What is event weight
Events can be *casual* - this type of events always have 0 weight.
Events can be *votable* - weight for event of this type is determined by voting.

Moderating CTFs
===============

In most cases after team creates a CTF and we just approve it.
Here are some non-standart cases.

# CTF does not have any relevant information like URL or description
* We reject the CTF

 # CTF has spammy description
* We reject the CTF

# CTF is created instead of Event
* We edit CTF name / slug / description so organizers will create specific event

# CTFs name already exists
Sometimes organizers forget that they created a CTF, create new teams and can not manage their CTF.
* We figure out why this happened and change CTF owners if required.

Moderating Events
=================
After team has approved CTF it can create events.
Important questions are:
* does event have relevant information for participants?
* is datetime correct?
* is event type correctly chosen?
* should the event has any weight?

# How we determine if an event should be confirmed?

Events with those restrictions should be rejected:
 - human race
 - gender (exception: women-oriented CTFs untill the moment there'll be majority or equal amount of them)

Most of over events will be accepted if they do not look spammy (a lot of events of same type and CTF).

# How we determine if an event should have some weight?

 Events will not have any weight in those cases:

 * An event allows only individual participation
 * An event restricts participants to some academic-only participants
 * Event organizer intentionally marked an event as "casual"
 * Last event of this CTF was run more than 18 months ago (this rule should be reviewed, may be weight should be reduced instead)
 * Events run on some conference and only conference attendee can participate
 * Event organizers did not provide any scoreboard within a voting period (7days after the event)

However, events allowing on-line participants, but grant prizes only to on-site or academic-only participants are eligible for some weight.

# On-site events

There is a discussion how to determine the weight of on-site events. Historically there are famous final events with huge weight:
* DEF CON CTF Finals
* HITCON
and some others.

All those CTFs require to pass an online qualification round and support teams to visit on-site events.
Although there are a lot of on-site events which have weight but do not offer any support to participating teams, also some of them can restrict participation on national basis. At the moment there is no specific rule - grant weight for those events or not.
Those rules should be elaborated.


Team membership requests
========================

If some team has existing members - only team members can confirm team membership for new members. Also, they can send an invite token to new team members.

If some team has no existing members then it can be freely joined by some person. There are simple antispam mechanics restricting teamsquotting, and all suspicious requests should me moderated manually.


Team merge requests
===================

New teams can be created automatically during scoreboard import process. Those team will not have any members and can be joined by any person.
After team has any members - "team merge request" can be send.
There are following restrictions:
* Team member sending a merge request should be a member of both teams
* Teams did not participate in the same event
* If some teams did not participate in any event during last 14 days - they can not be merged
Those rules should be reviewed.

Proposal to change restrictions:
* Team member sending a merge request should be a member of both teams
* Teams did not participate in the same event
* If some team participated in the events of the same year only it can be merged to some existing team during the current year
* Teams which participated in event durring before the current years can not be merged
* Disable team merging two weeks before the season ends (31 dec)
