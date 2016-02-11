===========================================================
Main repository for the OpenDreamKit H2020 European project
===========================================================

- Website: [OpenDreamKit.org](http://www.OpenDreamKit.org)
- Proposal files: [Proposal/](Proposal/)
- Proposal evaluation: [ProposalEvaluation/](ProposalEvaluation/)
- E-Concertation with other H2020 E-infrastructure projects: [EConcertation/](EConcertation/)
- [![Join the chat at https://gitter.im/OpenDreamKit/discuss](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/OpenDreamKit/discuss?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# Instructions for participants

## General recommendations

- Use existing infrastructure whenever possible (e.g. Sage's trac
  server), and in particular when contributing to existing software.

- Use ODK's github organisation for most public ODK specific
  infrastructure.

## Advertise ODK's activities

Add a post in the [news](http://opendreamkit.org/news/) or [activities](http://opendreamkit.org/activities/) pages of the website or an entry in the [events](http://opendreamkit.org//) section.

Typically a talk at a conference goes in the activities section while an ODK workshop (or related workshop) goes in the events section.

## Acknowledge ODK's support

See our [Acknowledgement web page](http://opendreamkit.org/acknowledge/)

## Project discussions

- The few private discussions (that involve for example nominative
  information) should occur on the relevant private mailing list
  (steering committee, coordination team, ...; see our
  [contact web page](http://opendreamkit.org/follow/)).

  Please make sure any private information is encrypted, especially
  given that some of us use gmail.

- Fine grained public discussions should go on github issues, with
  notices to the appropriate teams and persons.

- When an important such discussion is started, a notice shall be sent
  to participants@opendreamkit.org.

Design goals:

- As much as possible of the discussions is public, centralized,
  easily searchable, linkable, etc.

- People can keep a broad eye view on action happening in other work
  packages, without being flooded by e-mail / notices.

## Sharing and collaborating on documents

You can use this repository (or that of the web page when relevant) to
collaborate on public documents. There is a subdirectory for each work
package.

Private documents can be shared using the private repositories of the
relevant body:

- https://github.com/OpenDreamKit/Steering
- https://github.com/OpenDreamKit/Site-leaders  # Do we need this one?
- https://github.com/OpenDreamKit/Coordinator
- https://github.com/OpenDreamKit/Coordination
- https://github.com/OpenDreamKit/Advisory
- https://github.com/OpenDreamKit/Participants

## Progress tracking

Each ODK task and deliverable is modelled by a public github
issue. They are accessible from the sidebar our our web
page. Furthermore each deliverable has an associated milestone for
tracking its deadline.

The purpose of those issues is:

- To keep track of our progress, both for ourselves, but also for
  outsiders and for our *EU reviewers*.

- To host discussions

A first draft of each issue was created automatically using the
metadata produced in Proposal/final.pdata. It should be further edited
and maintained.

The issue should be assigned to whoever will be leading it (by
default: the work package leader).

The first comment of the issue should contain:
- a description of the task (taken from the proposal) or deliverable
- a brief status overview
- crosslinks to the corresponding task/deliverables
- todo list, sketch of plan, references to relevant resources on the
  web, @mentions of people that could/should be involved.

  Whenever possible, this includes creating issues/tickets on the
  tracking systems of the relevant systems.

For examples, see #50, #87, #72.

Alternatively, when natural, the issue can be just a pointer to an
issue of the relevant software where the actual discussion happens.
In this case, only ODK specific info (link to task, delivery date,
...) needs to be on the issue.

## Submitting a deliverable

For each deliverable, a report should be written and submitted to the
EU portal. Please write the report in latex in WPX/DY.Z/report.tex using
the our [style file](Proposal/LaTeX-proposal/deliverablereport.cls).
For deliverables that are not reports by themselves, and assuming the
status and tracking information is properly written on the github
issue, it's appropriate to have a very short report containing just a
link to that issue. The style file makes this trivial. See
[WP1/D1.1/report.tex](WP1/D1.1/report.tex) for an example.

To submit, login on the [EU portal](http://ec.europa.eu/research/participants/portal/)
and go to My Projects, Manage Project, Continuous Reporting Data, Deliverables.
Uploading a pdf failed for me with firefox (Nicolas); it worked with
chromium, or with firefox by wrapping the pdf in a zip file.
I haven't checked yet whether any participant can submit a deliverable
or if it has to go through the coordinator.

Then send a notice to participants@opendreamkit.org.

## Organizing a workshop

- 1 Create an issue to discuss the organization of the workshop (choosing the date, ...)
- 2 Propose potential dates with potential participants using Framadate/Doodle or any likewise tool -> Send a first mail to participants@opendreamkit.org / community@opendreamkit.org announcing the plan to organize the workshop.
- 3 Decide the date as early as possible (at least 2 months before workshop) -> send a second mail when date is fixed
- 4 Build the agenda  thanks to the related github issue (Coordination Team and the organiser create the agenda for a steering committee meeting)
- 5 Send the agenda and an invitation to the event to all participants

- 6 Use the repository [http://OpenDreamKit.github.io/meetings/](http://OpenDreamKit.github.io/meetings/)
to host the web page and public documents about each meeting



## Recommendations of Collaborative software

- Chat: [http://gitter.im](http://gitter.im)
- Video conferences: [http://appear.in](http://appear.in), [http://hubl.in](http://hubl.in), or [https://rendez-vous.renater.fr/](https://rendez-vous.renater.fr/)
- Temporary collaborative text editing: [framapad.org](framapad.org)
- Polls: [http://framadate.org](http://framadate.org)
- Anonymous votes: [http://adoodle.org](http://adoodle.org)
- Surveys: [http://limesurvey.org](http://limesurvey.org)
- Whiteboard?

## Recommendations for organizing official meetings

Send official e-mail invitations XXX days to all the meeting
participants, with the agenda. Those e-mails are to be kept for later
audits (proving that the attendance was necessary).

For meetings of 4-5 people, RPC-based video conferences as above can
possibly do the job. For a larger number of people, this does not seem
to scale. Here are some recommendations:

- Prepare a signature sheet to collect attendance

- Run a test, e.g. the day before, with the exact same setup as on the
  day of the meeting, asking all remote participants to join briefly.

- Request all participants to have a wired access (not wifi).

- Plan for a backup solution so that participants can join by plain
  phone.

- Make sure that all the support material (e.g. slides of status
  reports, ...) is available in advance (e.g. posted online), linked
  from the agenda, and read by all participants before the
  meeting. This way one can just scan through them quickly during the
  meeting, and focus on discussions.

- Set up a pad (e.g. on framapad) for collaborative editing of the
  minutes during the meeting. Initialize it with the agenda, and links
  to all supporting material.

- Set up a chat room (e.g. gitter) to let remote participants
  interact. Explore if the framapad's chat is good enough for that.

- Explore webcast solutions as an alternative to peer-to-peer video
  conference, so that at least remote participants can follow what's
  going on.

- After the meeting, move the content of the pad into a file in the
  relevant git repository for later editing. Whenever appropriate,
  make this file accessible online.
