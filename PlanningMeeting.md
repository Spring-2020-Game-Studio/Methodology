# Planning Meeting Details

This document provides detailed notes about the expectations of an
iteration planning meeting. 

## Caveats

Note that for our purposes, a "board" means a Trello Board. I have not found
another tool that is as robust, accessible, and affordable as Trello for this purpose.
However, a more powerful tool than Trello by far is an actual, physical board.
I have not been able to come up with a way to give each team a persistent,
secure, physical board, and so we're using Trello as a runner-up.

## Board Configuration

The board consists of the following columns, as outlined in [the methodology](Methodology.md):

- _Backlog_: This column contains all of the work items that the team envisions
  for the project but has not scheduled for completion. In Scrum, this is called
  the _Product Backlog_, not to be confused with the _Sprint Backlog_, the
  latter being the list of work items to which the team has committed for the
  current sprint.

- _Not Yet Started_: This column contains all the work items to which the team
  has committed for the current sprint, but for which no effort has yet been
  expended in the current sprint.

Only those two columns are needed for iteration planning, but as a reminder,
here are the other columns that are needed during the sprint.

- _In Progress_: This column contains all of the work that the team is actively
  working on. It therefore contains work to which the team committed, for this
  sprint, that has not yet been completed.

- _Needs Validation_: This column is for work that is completed but requires
  validation before it is considered done. The nature of this validation is
  context-dependent. Source code requires peer review, features require
  playtesting, other creative works require different lenses and perspectives.
  During a sprint, work that does not pass validation is moved back to
  _In Progress_.

- _Done_: This column is for work that is complete and validated.

## Planning Meeting

There are two parts to this meeting: feature articulation and team commitment.
During the first part of the meeting, the team figures out what needs to be done.
During the second part of the meeting, the team commits to getting it done.

### Feature Articulation

This is the process that generates the work items that are put in the backlog.
The key to writing a good feature is that it should be small enough to complete
in a few days and it should obviously and immediately add value to the
player's experience. 

Each feature is expressed as a _user story_. This technique comes from
agile software development as a way of keeping the focus on adding value
to the user--in our case, the player. There are several different philosophies about how to articulate the stories. A popular one that I have used is
[Mike Cohn's format](https://www.mountaingoatsoftware.com/agile/user-stories).
His format names stories in the format:

> As a _role_, I want _goal_ [so that _reason_].

An example that might come up in a platform or open-world game is: As an
explorer, I want to jump so that I can reach new areas. Note that here, I'm
drawing casually from [Bartle's player
typology](https://en.wikipedia.org/wiki/Bartle_taxonomy_of_player_types) to
contextualize what kind of player might do this, although I could also make use
of other techniques such as
[personas](http://www.agilemodeling.com/artifacts/personas.htm).

Others suggest that user stories should be more narrative, more like the 
colloquial use of the word "stories." For example, one might write a user
story like this:

> The player presses right on the controller, and Mario runs that 
direction on the screen. He runs under a box emblazoned with a question mark.
The player presses 'A', causing Mario to jump straight up with a sproing sound.
Mario hits his head on the box, which shakes and produces a chime and a coin.

Regardless of the format used to articulate the story, the team will probably
want to come up with a short name to quickly reference the story (such as "Jumping").
The full name of the story then can be given in the description of the card.

In either case, a crucial part of describing a feature is to include
its _conditions of satisfaction_. These are the [specific, measurable,
assignable, relevant, and timely](https://en.wikipedia.org/wiki/SMART_criteria)
criteria by which anyone on the team can determine that the feature is done.
These should be listed as checklist items on the card. A good name for the
checklist would be "conditions of satisfaction", since that's what they are.

During or after feature articulation, the team should prioritize the stories
in order of decreasing value to the user.
That is, the stories that add the most value to the user should be highest
priority. Keep in mind that there is an implicit dependency management process
here as well: while it's true that your players may really enjoy your dynamic
quest generation system, your RPG will have no value at all if players cannot
move their heroes around the screen.
"Value" is about _playability_ and not marketing or abstract concepts.

### Team Commitment

During this phase, the team moves features from the backlog to the
_Not Yet Started_ column.
Here is an algorithm to describe the process. Note that the estimates
are done in clock hours, not person-hours.

1. The team looks at the top priority item from the backlog and estimates
how long it will take to complete.  Put this number in parentheses before the
name of the card. 

    - The estimate needs to include the time it takes to integrate and 
    validate the feature. 
    - Keep in mind Rule of Pi, which suggests multiplying every estimate in a technology project by pi, as well as [Hofstadter's law](https://en.wikipedia.org/wiki/Hofstadter%27s_law), which states that it always takes longer than
    you expect, even when you take into account Hofstadter's law.

1. If the number of hours available to the team allows them to pick up the
top-priority story, move it to _Not Yet Started_ and go back to the top.

1. If the number of hours available is not sufficient to complete the
feature, then browse the items of slightly-lower priority that are significantly
smaller to determine if there are any items that should be completed out of
priority order. (Usually, the answer is "no" because value to the user is of utmost importance. However, sometimes features are of essentially equivalent priority
but must be sequenced due to the restrictions of the tool.)

Repeat until the team's plate is full.


## Commentary

In Scrum, it's not the team who documents and prioritizes the user stories but the
Product Owner. We are taking collective ownership of these projects, which has
the benefit that everyone is involved but it also has the drawback that 
responsibility and authority for this process become distributed.
It is possible that I may need to articulate as a formal option whether a team
wishes to have a centralized decision-maker or a collective approach. 