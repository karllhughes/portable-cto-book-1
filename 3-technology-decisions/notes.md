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
