# 1. Agile in a Nutshell

One of the most popular organizational frameworks for building software today is Agile. Its tenants of rapid development cycles and iterative changes are especially compelling for startups who don't know exactly what their product needs to be and don't have the resources to build everything they can imagine. Every startup I've been at generated 10 to 100 times as many ideas as they could execute, so the real challenge for product leaders is to prioritize these new developments.

I'm not an expert in Agile, but you don't have to be in order to lead a team of engineers or product developers either. As your organization grows, it will benefit you to either learn more about product development methodologies or hire people who do, but it's helpful if you can at least hold a conversation about Agile and maybe use some of its practices in your early development process. In a later chapter I'll give you a couple product development frameworks that have worked well for myself and others, but I would encourage you to tweak your process as often as you need to.

## What is Agile?

When people first started building software in a corporate setting, the experience was wildly different than it is today. Legendary software book, [The Mythical Man-Month](http://amzn.to/2nCT4dj) talks about writing reams of documentation, waiting hours or days for code to compile, and programming via hand-written or typed instructions. In addition to the challenges engineers faced in constructing and compiling their code, the mediums they had available to distribute it were much slower than they are today. People relied on physical tapes, disks, or drives to send software to customers, so upgrading wasn't a trivial task.

Naturally, the only way to release software with these technical limitations in place was with large-scale, thoroughly-tested releases. This method of completing a large number of features and bug fixes before a distant release date (usually 3-12 months away) is known as the "waterfall" method, and until software updates became more trivial thanks to the internet, it was pretty much the way all commercial software was built.

As the first dotcom bubble burst in the early 2000s, a wave of overfunded tech companies fell, and software developers started exploring new release cycles and methodologies. Because engineers and managers with varied backgrounds now had the ability to communicate and pass information around more quickly, some of the best ideas started to get used more widely. In 2001, a [group of these software thinkers](http://agilemanifesto.org/history.html) came together and wrote the first "Agile Manifesto."

Agile itself does not dictate a specific workflow or outline steps to take to release software. The Agile Manifesto is instead a listing of priorities that the software developers who wrote it believed were most important. It has since been adopted by countless companies and spun out dozens of frameworks - some more rigid than others. The Agile Software Development Manifesto reads\*:

> We are uncovering better ways of developing software by doing it and helping others do it. Through this work, we have come to value:
>
> - _Individuals and interactions_ over processes and tools
> 
> - _Working software_ over comprehensive documentation
>
> - _Customer collaboration_ over contract negotiation
>
> - _Responding to change_ over following a plan
> 
> That is, while there is value in the items on the right, we value the items on the left more.

So in theory Agile sounds great, right? But how can you actually use it in the day-to-day operations at your startup? What does it mean to collaborate with customers and respond to change? How can Agile actually help you make a more successful company faster?

That's where the various Agile methodologies can help you. I won't cover all of them here, but I'll try to offer a brief overview of three of the most common, and hopefully give you enough information that you can start researching them more for yourself.


### Scrum

Scrum is probably the most commonly used an Agile framework. A lot of people immediately think of Scrum when they hear Agile, but it's not the only way to follow the manifesto as we will see. Still, Scrum can be a great framework for project management, especially in larger projects with more clear beginning and endpoints.

Scrum uses [ome terminology that's important to understand first. This makes it a little intimidating to outsiders, but it's really not too complicated. I'm not going to try to cover everything involved in Scrum as that's worthy of a book in itself (check out [Essential Scrum](http://amzn.to/1JQvi0X) if you're interested), but I will attempt to give you a quick overview.

#### The Sprint Process

A "sprint" is a set time period (usually between 1 week and 4 weeks) where work will be done. At the beginning of the sprint, you should have well-developed requirements for each feature to be worked on, and at the end you should have working software that meets those requirements and is ready to be released. Here are the meetings usually held within each sprint:

##### Sprint Planning Meeting

##### Daily Scrum

##### Sprint Review/Demo

##### Sprint Retrospective


#### Scrum Team

##### Product Owner

##### Development Team

##### Scrum Master

While you can really dig in and make yourself an expert in Scrum, I don't think that's the best way for a startup CTO to spend his time. You're more likely to borrow pieces of Scrum that help you depending on where you are in your company's lifetime. As you get larger and more rigid processes become important, consider getting deeper training in Scrum, sending one of your team members to train in it, or hiring a Scrum Master to help you.


### Extreme Programming

### Kanban

While not mutually exclusive with Scrum, Kanban is another Agile method based on [a Japanese lean manufacturing system](https://leankit.com/learn/kanban/what-is-kanban/). When applied to software development, [Kanban helps visualize work](https://www.themuse.com/advice/an-underrated-way-for-engineering-teams-to-improve-their-workflow) as it flows through steps in a system and limits the amount of work that is in progress at any given time.

Kanban means "board" in Japanese, so unsurprisingly, the core element of the system's organization is a board. I like [Trello](https://trello.com/) for managing Kanban boards, but you can try other systems or use a real physical board if that works best for your team.

### What Kanban Looks Like

A simple Kanban board might have six columns that show where each piece of work is in the product development cycle. Here's a Kanban board my team might use:

![](http://i.imgur.com/EyhkfxW.png)

#### Column 1: Backlog

The Backlog column should contain a prioritized list of ideas, bugs, or business needs. The card doesn’t have to have a ton of detail yet, but it should have enough information that your team members understand why it’s important.

#### Column 2: Planning

In this column, a product manager will fill out a specification for the feature by meeting with business stakeholders, engineers, and designers. When it’s ready, he or she will move it to the “Ready for Engineering” column.

#### Column 3: Ready for Engineering

At this stage, all cards should have detailed specifications. While you may still have questions about technical details, the business requirements should be clear.

#### Column 4: In Progress

You can move a card over to “In Progress” at any time. This self-driven “pull” system builds a culture of personal accountability and curiosity.

#### Column 5: Testing

When you have completed work on the card, move it to “Testing” where another engineer (or someone on the QA team) will pick it up.

#### Column 6: Deployed

Another defining feature is that work should be delivered continually to a staging or production environment. This column allows anyone on the team to see what work has been released recently.

-----
\* ©Agile Manifesto Copyright 2001: Kent Beck, Mike Beedle, Arie van Bennekum, Alistair Cockburn, Ward Cunningham, Martin Fowler, James Grenning, Jim Highsmith, Andrew Hunt, Ron Jeffries, Jon Kern, Brian Marick, Robert C. Martin, Steve Mellor, Ken Schwaber, Jeff Sutherland, Dave Thomas.

This declaration may be freely copied in any form, but only in its entirety through this notice.
