# 2. Developing an MVP

"It's more about understanding what to build and if it’s worth building instead of how to build it" - [Thomas Trajan](https://medium.com/@tomastrajan/how-can-you-increase-your-value-as-a-software-engineer-cab9599bbbe)

## What is an MVP?

For most entrepreneurs with an idea it’s hard to compromise on quality. In their mind, the product or service they want to deliver is top-notch, but in reality they rarely have the resources to build anything like what they imagine.

The term MVP, which stands for “minimum viable product” gets thrown around all the time in startups. It was popularized by Eric Ries in his book The Lean Startup (http://www.startuplessonslearned.com/2009/03/minimum-viable-product.html), which is well worth the weekend it will take you to read.

The goal of an MVP in business development is to create something that meets just enough of the business need to test or validate an assumption, allowing the entrepreneur (or intrapreneur) to save on scarce resources until the project is proven “viable.” In The Lean Startup, Ries says that an MVP is “not necessarily the smallest product imaginable...it is simply the fastest way to get through the Build-Measure-Learn feedback loop with the minimum amount of effort.”

So an MVP is less about building a product, and more about [learning what your product needs to be](https://steveblank.com/2013/07/22/an-mvp-is-not-a-cheaper-product-its-about-smart-learning/3-1-defining-mvp.md). I think of the MVP as a “pre-product” phase. Some good examples of an MVP might be:

- A software as a service company runs a pilot service with three paying customers using spreadsheets, online forms, and email.
- An app maker creates mock-ups of his app, creates a free landing page website, and measures the number of people who click the “Download Now” button.
- A writer releases the first three chapters of his book and directs potential buyers to fill out a form with their email address if they want to know when more is released.

There are [dozens of ways you can build an MVP](http://mlsdev.com/en/blog/50-types-of-mvp), but you might have noticed that none of the examples above require work from a software developer. This is intentional. Software is expensive to build and maintain, so an ideal MVP requires no dev work to get out the door. This allows the business team to learn whether or not their idea is viable before they invest heavily in product development.


## Where Does the CTO Fit In?

An early stage CTO who's building an MVP has the job of figuring out how to piece together a "product" that will prove the business' viability as quickly as possible.

Notice that I didn't say an early stage CTO should write a custom CMS, build something in the latest exciting framework, or even write code at all. If you are a software developer then great. You'll have an advantage over startups whose head of product or engineering is less technical. Still, that doesn't mean you should spend a ton of time writing code in the beginning.

Once the business has tested its hypothesis and you're ready to invest in a more robust product, your job will change. You'll need to break out your architecture skills and make decisions about what kind of tech stack to use, the kind of team you want to hire, and the product release cycle you want to employ. In the MVP phase, these decisions don't really matter much.

The truth is that many software startups in the MVP phase [don't need a developer to figure out if their idea is viable](https://www.karllhughes.com/posts/creating-a-tech-startup-without-a-developer). They need a way to put their idea into the world, and [plenty of low-cost tools exist for exactly that purpose](http://blog.stridenyc.com/blog/you-dont-need-a-cto-you-need-squarespace/).


## Minimal MVPs

> "Premature scaling is putting the cart before the proverbial horse, and in the case of startups this can potentially relate to both engineering and operations...For the engineering team, there’s the often obsessed about notion of having a robust platform that can handle millions of users before the startup even gets to 10’s of thousands on there. The team starts to worry about all the technical issues that they’ll have to deal with when success comes, but they lose track of what is actually going to make them succeed." - [Michael A. Jackson, Advent Venture Partners](https://www.linkedin.com/in/michaeljacksonvc/)

Many software engineers get stuck in the mindset that a product isn't "good" if it wasn't well-built, tested, and professionally engineered, so I'm devoting the rest of this chapter to show you how real companies have built MVPs with little to no custom development work. These solutions aren't meant to carry a startup through to millions in revenue or "scale", but [more startups have been burned by premature scaling than have been burned by not building a robust enough platform on day 1](https://s3.amazonaws.com/startupcompass-public/StartupGenomeReport2_Why_Startups_Fail_v2.pdf).


### A Startup Pivot

Around the middle of my tenure at Packback, we began a "pivot." Our textbook rental platform wasn't picking up traction like we had hoped, so one of our founders came up with a new idea for a product that would eventually become Packback's primary focus.

At the time, however, we didn't know that this new concept would become our biggest revenue generating opportunity, so we didn't start by pulling the engineering team off our existing product. Instead, we cobbled together a stack of services to test our idea before employing our engineering team's time.

Before bringing any engineers onto the new product, we cobbled together some off-the-shelf services and used a little elbow grease to support around 100 users. [Our first tech "stack" was completely devoid of custom code](https://blog.codeship.com/incremental-software-development-with-php-microservices/), and it had all the basic features that are still present in Packback's Question and Answer platform today.

The product had to do three basic things:

- Users had to be able to log in and post questions and answers (think Quora, but for a single classroom).
- Professors wanted a report outlining their students' participation on the platform (eg: number of questions asked and answered) in order to tell who was engaged and who wasn't.
- We wanted to be able to market various paid products to students or remind them to log in and post new content weekly.

That first bullet point could have been accomplished with just about any open source or cheap forum software. We found one a little more specialized for our use case, and even better it had an API that we could hook into later.

In order to create reports for professors we had an intern go through and count the number of questions and answers posted by students each week - remember, there were only around 100 users - knowing that while this wouldn't scale, it would help us learn about the things professors wanted in these reports. The ""reports" ended up being Google Sheets that we would then email to professors every week.

Finally, in order to market to students, we put all users who signed up into Mailchimp email lists so that we could communicate with them periodically. The whole setup cost us less than $100/month, so while we knew it wouldn't scale to millions - or even thousands - of users, it allowed us to test and validate our idea before we went all-in.

I've written more about the process of cobbling together third party services as an MVP for Packback before, so if you want more details, check out [this post on Codeship's blog](https://blog.codeship.com/incremental-software-development-with-php-microservices/).

The point is though that Packback was able to build a real product and sell it to real users without investing any real developer time, and I would argue that most software businesses could probably start the same way. While the grand vision that founders have might be impossible without custom code, the first step on a long journey is to get people using your product. You can't do that with just an idea.

### Running a Business on Spreadsheets

Packback isn't the only company that has run a product in Google Sheets or Excel files.

One of the first companies I worked for in college tested power plants. With millions in revenue, they were a bit out of the early stage startup phase, but they were a young company with a lot of internal innovation. One of the primary software "products" we used was written entirely in Visual Basic for Excel macros.

While Excel might not be as clean or flashy as a custom UI in an app or website, it can certainly get the job done. Spreadsheets are universal - every business person knows how to open and manipulate an Excel document - and extremely versatile. Even without code you can automate things, build advanced formulas with conditional logic, and decorate your documents with charts, graphs, and images. It's probably the most powerful engine for an MVP in software development today.

When I first joined The Graide Network, the product was in its very early stages. The code that was there had been built by a low-cost offshore team, so the reliability was low and new features frequently "broke". Since the founders were non-technical, they had to find workarounds for when their MVP fell down, so they simply fell back to spreadsheets and emails.

This allowed them to generate revenue even before having a fully-baked product, which in turn allowed them to raise money to hire developers and scale up their operations. Many times, founders get stuck focusing on building a perfect product before they sell anything to customers, but this is a dangerous move for companies that should be in the MVP stage.

### Overbuilding the MVP

I've had to opportunity to learn from both the successes and mistakes of many other CTOs in Chicago. While I've heard many stories of overbuilding MVPs, one sticks out in particular. I've changed the names of the company and people involved, but the number of examples like this are amazingly common.

My friend John was the founder and CTO at a startup that collects data and essentially sells it to customers. This is an increasingly common business model for startups as companies are interested in "big data" but often lack the expertise needed to collect and organize it. John's startup was in this industry, but like many early stage companies, they didn't really know who their customer was.

That, of course, didn't stop them from raising money on the promise of better data available to everyone. They put together a product designed for the consumer market, gave away most of their data for free, and then sold a premium tier access to their biggest users. Building a product that works well for thousands or millions of users is expensive, and because only a certain percentage will ever become paid users, it can take a long time to reach profitablity.

Still, investors saw lots of companies making this kind of product, and John's company raised over $2 million promising to capture a percentage of a highly lucrative consumer market. The continued beefing up the product, but sales never came. They made a few sales, but such a laughably small number that it was better to tell investors they were focusing on grabbing free users who they would later upsell rather than admit they didn't have a product anyone wanted to pay for.

Eventually things came to a head when the company started to run out of money. With less than 3 months of runway, they started letting people go and looking for an emergency round of funding. Raising money when you're cutting jobs is never a good thing because it means investors can cut your valuation in John's case, they even got old investors to give up much of their equity.

The good thing about going through such desperate times was that the company _had_ to focus on building a real business rather than making a shiny consumer product. They started talking to companies who would license some of their software or pay for access to mass amounts of data, and built a very minimal product to deliver it to them. Many of the consumer-focused product features they built turned out to be wasted effort, but they were able to salvage some of their core data collection and organization services for a new customer who had money and wanted their data.

It's easy in hindsight to ask why John's company didn't just go for enterprise sales from day one. It's also easy in hindsight to see that they overbuilt a product for a market that had neither the ability or the need for it. That said, half the CTOs I know have made this mistake at some point in their career because as engineers, we have a tendancy to build first and think of the business second.

Don't make this mistake. Build a truly lean MVP; rely on manual, non-scalable architecture; discover your business. Once you have a model that you know can make money and that the market will pay for it's time to enter the next phase of your early startup's life-cycle.

