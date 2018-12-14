---
layout: post
title: TestBash San Francisco 2018
---

Last week I had the pleasure of attending my first professional conference at TestBash San Francisco. TestBash is a single-track software testing conference organized by the UK-Based Ministry of Testing with events for testers all over the world including Australia, Germany, the Netherlands, Dublin, Manchester, and Brighton just to name a few. The single-track feature of this conference is great because attendees don’t have to pick and choose between any competing topics, everyone sees every session. This year’s TestBash SF featured awesome speakers on a range of topics from leadership and quality culture to test data management and testing serverless applications.

### Highlights
* Elisabeth Hendrickson (author of Explore It!, VP at Pivotal) kicked off the conference with a talk about influence and leadership, which touched on techniques for gaining influence and becoming a leader. Her key points were that each of us has agency to lead by example, fear makes a lousy compass, and to focus on shaving the right yak [Yak Shaving](https://www.dailymotion.com/video/x2est2c).

* Rick Clymer spoke about his experiences with testing Mobile apps and the mobile testing pyramid. His experience and the model speak to why it is so important to understand what we are testing and how we are achieving coverage. That is, test for things like code correctness or functional verification on simulators/emulators, and focus real-device testing on things like user experience, network connectivity, interaction with background apps etc.

* Paul Grizzafi’s talk “Automation Declared Software” focused on the fact that test automation is software development and should be treated as such. Development considerations like planning, building, version control, deployment, debugging etc. all need to be accounted for when creating automated tests. Focus for test automation frameworks/script needs to be applied towards being good stewards, minimizing maintenance, and providing appropriate documentation to create value for the consumers of automation.

* Glenn Buckholz gave a live demonstration on testing serverless applications with an AWS Lambda application and although the topic was specific, it was a great example of how important context is to test strategy. For example, serverless applications have incredible scalability, but that comes at a cost so handling DDOS attacks is incredibly important or even a small sustained effort could bankrupt a company. Trade-offs in system architecture decisions need to be matched by understanding the risks they bring and devising a strategy to mitigate them.

* Dan Ashby and Richard Bradshaw explored the power of models as communication and collaboration tools to aid in problem solving and challenging our current level of thinking. They argue that working without a model is virtually impossible and adds risk to any complex task. The key point here was that models are incredibly useful tools in software development because they help teams arrive at an explicitly defined shared understanding much faster than by any other means.

* Omose Ogala showed real examples of how his team iterated on managing external data requirements, going from using hard set examples of response data to mocking and generating data on the fly and adapting their automated assertions to the generated data.

* Jasmin Smith shared her experience with Mob Programming and how uncertainty and doubt for those without a technical background is unfounded, because the diverse experiences and perspectives that each person brings to the Mob are all valuable and help teams build better software together. This talk inspired me to try to experiment more with pair and mob programming because the outcomes described by her and others have great potential.

The conference wrapped up with 99 second talks, which gave an opportunity for any attendee to discuss a topic of their choice for 99 seconds. This feature of the conference, the speaker lineup, the conference organizers, and the attendees are just small examples of why the testing community is so extraordinary. It was a fantastic experience learning and sharing with like-minded quality professionals and I’m looking forward to taking some of the new things I learned around automation practices, test data management, and communication and collaboration back to the Sunquest team.
