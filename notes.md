## Outline

- Intro: Who is this for? What is this book? Who is the author? What are early stage startups?
- Part 1: Personal Effectiveness: Know yourself, know what you're getting into, and know how to effectively manage your time and interactions with others.
  - Should you join a startup? Equity vs salary, etc
  - Defining Success: Before you start/join this business, what does success look like for you?
  - Fear/Balance: Minimizing fear by keeping things in perspective, and keeping your life in balance.
  - Work Habits: Using your time more efficiently by batching similar tasks, staying focused on one thing per day, and delegating the things that you aren't good at.
  - Team: Handling relationships with cofounders, angel investors, other engineers/designers/etc.
  - Networking: Building a habit of making and maintaining connections.
- Part 2: Building MVPs
  - What is an MVP?: What does this mean? What is the goal of an MVP? When does a company need one, and when do they need something "better"? When will we "outgrow" the MVP?
  - Defining business goals: Finding out what we are testing, what a successful test will look like, and scraping ideas down to their bare essentials.
  - Finding solutions: Sometimes this requires writing software and sometimes it's simply cobbling together third party software. Here's how to know which route to go.
- Outro: What's next?

## Technology decisions

### How much should CTOs code?
- "Embrace your ability to learn, [but] Be careful not to get so immersed in the minutia that you lose sight of your overall responsibility to drive technology at a broad level." https://www.recode.net/2017/6/15/15332486/cto-code-coding-skills-developer-education-engineer

### Choosing tools and technologies
- Use well-established, tried and true tech that you know
  - You are not google/amazon/linkedin: https://getpocket.com/a/read/1774906855
- Pick a language everybody on the team knows well
- Decouple things as much as is reasonable
- Don't overcomplicate things until you have to
  - "Often complexity is generated when there is no willingness to recognized that a non fundamental goal of a project is accounting for a very large amount of design complexity, or is making another more important goal very hard to reach, because there is a design tension among a fundamental feature and a non fundamental one." - http://antirez.com/news/112

### Testing
- What kind of testing can you do?
- How much testing is appropriate?
- Layers of testing
- Pragmatic testing of a fluid product
- Continuous integration

### Architecture
- Decouple things
- When in doubt, choose the simplest path, you can make it more complex later
- "Architecture is expensive, especially when a new domain is being explored. Getting the system right seems like a pointless luxury once the system is limping well enough to ship. An investment in architecture usually does not pay off immediately. Indeed, if architectural concerns delay a product’s market entry for too long, then long-term concerns may be moot. Who benefits from an investment in architecture, and when is a return on this investment seen? Money spent on a quick-and-dirty project that allows an immediate entry into the market may be better spent than money spent on elaborate, speculative architectural fishing expedition. It’s hard to recover the value of your architectural assets if you’ve long since gone bankrupt." - Big Ball of Mud, http://www.laputan.org/mud/mud.html
- "focus first on features and functionality, then focus on architecture and performance." - Big Ball of Mud, http://www.laputan.org/mud/mud.html
- "Make it work. Make it right. Make it fast" - http://wiki.c2.com/?MakeItWorkMakeItRightMakeItFast

## Management

### Building trust within the organization
- Transparency - Show people what you're doing
- Explain technical concepts, they aren't that hard
- Let everyone in the meeting
- Working with founders

### Growth/hiring
- Recruiting: Always be recruiting
- Working with recruiters:
  - they try to push a sense of urgency on you that doesn't exist
  - don't waste time going to their office unless you see the resumes
  - negotiate, but realize that if you're the lowest rate, you get the last pick of the talent
- Interview process
- Onboarding

### Metrics
"Ticket trackers grossly understate the impact of your best employees, and grossly overstate the value of your least valuable developers. Why?
Your best developers spend disproportionately more time helping other developers perform at their peak. Their contributions are not easily tracked by project issue trackers.
Likewise, inexperienced developers are what I call “drive by coders.” They’re incentivized by shallow ticket numbers to close issues as fast as they can. They throw a quick fix in the general direction of the problem & leave heaping piles of technical debt in their wake." - https://medium.com/javascript-scene/how-to-build-a-high-velocity-development-team-4b2360d34021

- Performance assessments: https://medium.com/javascript-scene/assessing-employee-performance-1a8bdee45c1a

### Meetings
- 4 essential parts to a good meeting: https://blog.trello.com/productive-team-blueprint-free-guide

### Performance reviews
- Weekly checkups
- Quarterly reviews

### Letting people go
- Keeping a paper trail
- Letting them down

### Culture
- Standing up for your team
- Space, volume, comfort
- Encourage balance
- Maker vs. manager calendar, time spent
  - "Makers need long, uninterrupted time to go heads down and create work without any distractions. Managers, on the other hand, are people who coordinate across teams, move teams towards goals, and manage projects. Managers need effective meetings and good, consistent systems for getting status updates." - https://blog.trello.com/productive-team-blueprint-free-guide

## Introduction

While much has been written on management, programming, product development, and productivity there is a lack of writing on these topics as they are encountered by CTOs and tech leads and young startup companies.

Our skillsets as startup CTOs are unique. Unlike software developers in large corporations, we can't allow ourselves to be caught up in every minute detail of our software, and unlike corporate CTOs, we can't take our hands out of the day-to-day operations to solely focus on the big picture. We must be hybrids, learning bits and pieces of what would be 5 or 6 different jobs in a larger company because until we get there, someone's got to do everything.

It's possible that this niche - startup CTOs - is not large or marketable enough. Maybe we just don't tend to be big readers? But I've seen an increasing number of technology-enabled companies popping up without great technical leaders in place. When I fell into my first engineering leadership role at a startup, I certainly didn't know where to start. Now that I've come out the other side, I'm piecing together this book for people like my past self.

## Format

This text seeks to provide a library of patterns that can be used by new or experienced CTOs at startups to help make their jobs more approachable and predictable. Like programming books that center on patterns, I'll try to provide examples and edge cases for each pattern here. Also like programming patterns, no one should blindly follow all this advice all the time. Each company, employee, product, and situation is different; it's impossible to write a book that encapsulates every situation a startup CTO will see.

Each chapter will start with a short introduction to the topic, usually framed around a real technology leadership problem. Next, I will lay out a framework for dealing with the issue in a repeatable manner. Finally, I'll offer specific examples of the concept in practice.

I like books with predictable patterns, and like many engineers, my brain enjoys order. That said, what I find orderly may not be right for every reader, so if you find the format distracting I welcome your feedback. This is a repository, so make a pull request if you feel so inclined.
