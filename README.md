# fpoc-starter
# This is the collector repo for all fpoc projects.
fpoc simple means Football POC

# Goal

As a manager my key responsibilities are often lying too far away from actual coding. I have to keep up with technologies and architectural trends to foster technical decision-making as an engineering lead, but being a Senior Software Engineer my eagerness to code (more) has not faded at all in the recent years.

My best bets are hobby projects (with potential business value interest), coding exercises (katas) and **heavily learning/tech focussed dummy** (no business value) **projects**.

## This **fpoc** project is the latter one, it **is** purely existing to let me:
- finger exercise ExpressJS and refresh my knowledge
- see how my beloved NodeJS (and it's frameworks) evolved in the past 2 years
- explore the opportunities ReactJS can give us over Angular (which I have had plenty experience in the past with)
- have a meaningful peek into Kotlin (with Spring) and allow me to reconsider if Java have had finally overcome its bloated nature or not (I was a JAVA backend developer for ages)
- experiment with Python while doing data processing (I was graduated from the university as a Data Engineer)
- beat challenges in the domain of microservices, docker containerisation and AWS deployment

## In the other hand it is definitely **NOT**:
- a fully pledged, production ready all-around solution
- maintaining the best tech decisions (for instance, because trying out something was more important than the memory footprint)
- robust, because of the allocated time, the NFRs and test requirements are often neglected
- bulletproof: security considerations only applied when the purpose was to meet them
- a real life scenario, just a dummy project that allows fiddling around
- reflecting the way I would build or maintain a business application in real life

# Parts and purpose of those
## fpoc-be-express-vanilla
[Repository](https://github.com/ttoth/fpoc-be-express-vanilla)

In this vanilla ExpressJS application I aim for:
- building a scalable (multi instance) express app with basic default tooling (like: config management, logging, async/await support, linting, mongoose over MongoDB, code structuring)
- using message queues to consume queue elements only once
- bootstrapping simple REST APIs
- fabricating some unit testing for business logic
- creating some component test to validate API responses
- leveraging an ODM (Mongoose) over MongoDB 

## fpoc-be-data-proc-js-vanilla
Next up!