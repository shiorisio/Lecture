2016/04/26

What is Time?

Process arrow means that ping message.
In different process

How is this transport to programmers?

LVT: local virtual Time
GVT: global virtual Time(old time from all messegers. GVT is not need roll back.)

positive message
negative message: copy of positive message

[shiori]
 Sending some message needs to use same virtual time like GVT. If use LVT not GVT, some mail are delaying.
[shiori]


1. Metadata
Presenter: iomz
Lead summarizer: Shiori Hikichi
Conversation contributors: rdv, iomz, nitish, shiori
Written contributors:
n.b.: Every paragraph not explicitly tagged with the author's name will be assumed to be a product of the lead summarizer. Tag your work with e.g. [rdv]!
2. Basic Data
Title:  Virtual Time
Authors: D. R. Jefferson
pub info: published in 1985
related pubs/websites:
funding:
Award: won the Dijkstra Award in 2000.  
3. Original Ideas
- The way of share the same time with some different processors like Global Virtual Time(GVT)
4. Context
5. Reality
Implemented to send some message between different processors.
6. Lessons
How are positive/negative message transporting to programmers?
7. Choices
8. Focus
Primarily something to be aware of, as it affects your own writing.
9. Presentation
Again, something for your own writing.
10. Writing Style
Again, part of the checklist when writing, but look to see how the authors of this paper have done it.
11. Data
This should generate a lot of discussion, in class and online.
12. Impact
Since this class is covering many important, historic papers, we should be able to identify the impact of this paper on later work, and, especially for the design principles papers, identify cases where people have ignored (or been ignorant of) the advice and gotten into trouble.

13. Commentary:
Does the group consensus agree or disagree with the paper, or some important aspect of it? (Essentially, a summary of the discussion below, to be done by the summarizer one week after the presentation.)

-----------------------------------------------------------------

In-class discussion:

<rdv>I love this paper, and not because it’s from USC -- I happen to think this is one of the most important ideas around. Like Lamport, it starts with the idea of special relativistic time: events are distributed in physical space, and their ordering is limited by message transit time. But what he has done here is impose a Newtonian idea of time on top of the constraints of physical messaging.
</rdv>



After-class discussion:
