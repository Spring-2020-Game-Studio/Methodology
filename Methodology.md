# Methodology Specification

## Introduction

This document describes the shared methodology among all teams in the CS490
Software Production Studio course in Spring 2020.

### Definitions

It will help our communication to establish some definitions. We are one
_studio_ that contains different _teams_. The students are therefore _team
members_. The professor wears a few different hats: as a _project mentor_, he
coaches you toward productive success; as an _executive producer_, he tries to
keep you on track; as an _instructor_, he tries to teach you new things that
will be useful to you and is responsible for reporting a grade and assessment
data to the university.

A _production day_ is a day after the preproduction period that is not set aside
for any other purpose. An _iteration_ or a _sprint_ is a period of time during
which the team makes progress on a set of goals. Each iteration begins with a
_planning meeting_, during which that iteration's goals are set. Each iteration
ends with a _review meeting_, during which the results of the iteration are
compared against the goals, and a _retrospective meeting_, during which the team
reflects upon and improves their processes. Each iteration produces an
_increment_, also known as a _potentially shippable product_ or an _executable
release_.

There will be opportunities to update the methodology as part of
each retrospective meeting.

### Background and References

We recognize and seek [the seven properties of Crystal
Clear](https://www.projectsmart.co.uk/7-properties-of-highly-successful-projects-from-crystal-clear.php),
which are summarized below:
1. Frequent Delivery
2. Reflective Improvement
3. Osmotic Communication
4. Personal Safety
5. Focus
6. Easy Access to Expert Users
7. Technical Environment with Automated Tests, Configuration Management, and
   Frequent Integration

We uphold the value of safety through practices inspired by
[Anzeneering](https://www.industriallogic.com/blog/anzeneering/).
In particular, [Joshua Kerievsky's articulation of Stop Work Authority
in software](https://medium.com/@JoshuaKerievsky/stop-work-authority-d853f6a3c42d)
provides guidance to us on how to maintain safety in the studio.

We take an _iterative_ and _incremental_ to building software.
- _Iterative_ means that we work in iterations, with each iteration of
  production being bookended by a planning meeting at the beginning and review
  and retrospective meetings at the end.
- _Incremental_ means that each iteration produces an increment that is an
  executable release or potentially shippable product. That is, each iteration
  produces a playable game.

We believe that software (including games) are made by human beings and so we
respect [the Heart of Agile](https://heartofagile.com).

## Rules

1. The team owns the project. There are many kinds of work to be done, and any
   work can be done by any team member. You are authorized to contribute in any
   way to the project. Some people will tend to work on particular aspects of
   the game, but that is by choice, not by constraint.

    - We foster [T-shaped
      skills](https://en.wikipedia.org/wiki/T-shaped_skills), such that all team
      members share core competencies, and individual team members provide depth
      in particular areas.

1. Use Slack for studio and team communication.
    - The #general and #random channels are available for studio-wide communication.
    - Each team sets up its own channels as needed, giving each a recognizable
      prefix corresponding to the project. (For example, #sim-programming would
      be a channel about programming for the project codenamed "sim".)

1. We start each production day with a 9AM daily standup meeting, during which each member reports on the following to their team:
    - What did you contribute since last time?
    - What do you plan to accomplish before next time?
    - Are there any impediments in your way?

    Note that _impediments_ are obstacles that stand in your way but that can be
    removed or worked around. They are never excuses for failing to meet
    commitments.

    If a team member is unable to attend a meeting, they must post to the
    #general channel on Slack.

1. Each team designates one team member as _producer_. 
    - The producer role may change at any time by majority vote of the team,
       although it is preferable to keep the role for one iteration.
    - The producer's primary role is _to remove impediments to the team's progress_.
    - The producer's secondary role is to communicate progress to the project
      mentor in his capacity as executive producer.
    - The producer or their designate gives an informal update to the executive
      producer on each production day.


1. The team's plan will be recorded and managed on [Trello](trello.com).
    - Ensure that your profile uses your natural name and initials for ease of
      identification.
    - Each team will have its own board within [the organization](https://trello.com/spring2020gamestudio).
    - Each board will have the following top-level lists:
        - _Not Yet Started_ for work items that are part of the sprint but have not yet been started;
        - _In Progress_ for work items that are currently being completed;
        - _Needs Validation_ for work that is complete to the best ability of those working on it, but which has not yet been reviewed by the team or corresponding lead;
        - _Done_ for work that is done.
        - Optionally, a _Backlog_, which
          contains work items that are not part of the current sprint but may be
          picked up in the future.
    - Each card in a list represents a "work item", most of which are features expressed
     from the player's perspective. 
       - Prefix each card's name with the total number of hours estimated
         remaining to complete it, written in parentheses. For example, "(6)
         Control the camera with the right stick".
       - Non-atomic work items use named checklists to track the tasks necessary to 
       complete a feature.
         - Each checklist item should be expressed as a _condition of satisfaction_ or
         an _acceptance test_. Each should be [specific, measurable, assignable,
         relevant, and timely](https://en.wikipedia.org/wiki/SMART_criteria).
       - Team members are assigned to features when they commit to working on them.
         - These team members are responsible for ensuring that the feature is completed.
         This does not mean that they have to be the ones to do all the work, but it does
         mean that they should always know the state of the feature.
    - After every work session, each team member updates the number of hours
      estimated remaining on the features they have touched. Note that estimates
      may increase, decrease, or remain the same. 
       - A feature that is complete to the working group's satisfaction is moved
         to _Needs Validation_, with its estimate updated to be the time for
         validation. The nature of validation is task-dependent, but it
         frequently includes playtesting with representative players.
       - A feature that has been validated and has no hours remaining on it
         should be moved to _Done_.

1. The producer maintains a _burndown chart_, which plots time against
 the estimated number of hours remaining. The chart is updated after each
 planning and standup meeting.

1. Maintain effort only on tasks that are part of the current release.
    - Corollary: Solve the problems you have, not the problems you might have later.

1. Use the  _mission statement_ to analyze project ideas. It allows you to say
   "no" to good ideas.

1. Team access to shared resources (such as rooms and devices) is negotiated via
   communication between producers.

1. Every team member has _Stop Work Authority_. This means that if you witness
something that impacts the safety of the team, you may signal for the team
to Stop Work. The team then redirects their attention to the safety issue.
    - Stop Work Authority cards will be available in RB368. A good way to signal
      Stop Work is to hold up one of these cards.
  
1. Keep a respectful volume level in order to respect the focus of your
   studiomates.

1. Keep the discussion in our shared spaces about the projects. If you would
   like to talk about something unrelated (including taking a phone call), take
   it to the hallway or another location so as not to distract those who are
   focused on the project.

1. If a team member has a conflict with another team member, he or she should
   talk to that individual about it privately first, face-to-face. If a
   resolution is not met, the issue should be brought to the project mentor.

1. When faced with a design conflict (including software architecture,
   implementation details, user interface design, and game design) where two or
   more team members disagree, monitor the amount of time spent on the
   discussion. If a resolution is not found within five minutes, take one of the
   following options:
    - Invite the project mentor for a consultation.
    - Get a volunteer for each side. Schedule a follow-up meeting, with all
      relevant stakeholders, at which time each volunteer will be expected to
      demonstrate prototypes to defend their positions. After this, the
      stakeholders vote on which direction to pursue.

1. Prefer working in pairs whenever possible, particularly on technical and
   integration tasks. Rotate pairs at least once a week to ensure that knowledge
   is distributed across the team.

1. Each team chooses a version control system and follows the conventions for that
   system.