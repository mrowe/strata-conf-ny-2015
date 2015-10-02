# Data 101

This was the 30,000 ft view of the data science/big data world (which seemed an appropriate way to kick off the conference),  In O'Reilly editor Paco Nathan's words, it was a "Story arc - for mostly "business" audience. What does the data landscape look like? Reports from the field."

It covered things like:

- what are distributed systems? how are they different to "classical" systems?
- how do you make a business case for all the hot new technology?
- demystifying machine learning
- how to build a data science team
- how to become data-driven organisation

Of course jamming all this into 3 hours meant it was pretty light on detail, but still a good way to get into the mindset of the conference.

# Architecting a Data Platform

This tutorial was presented by three people from Silicon Valley Data Science, a leading consultancy in the "data science" world. John Akred, their CTO, gave a great overview, talking about how to "draw value from your strategic data assets": think about what you can do with data rather than to data. You should define success the success of projects (first pilots, and then production products) in business terms, not technical (revenue, time to market, cost avoidance, brand beneit, etc.)

Then the VP of Engineering Stephen O'Sullivan gave a tour of the technical components. This was basically a buzzword overview of processing/compute technologies (spark, storm, kafka, flume, oozie, etc.) and storage technologies (hadoop, HDFS, tachyon, cassandra, etc. etc.) and when they are most appropriate to use.

## Analytics

Back to John for this bit. He talked about how Exploratory and development mode analytics are not the same as production pipelines: it puts very different demands on your architecture.

Also, don't forget testing with REAL data when you go to productionise your algorithms.


## Data Services

With turned out to really just be about microservices. Everybody loves their synchronous microservices! I suppose it's better than integrating at the database...

Key points: you have to have the organisational culture and comms (and trust) for this to work across teams. You have to have your deployment story down. And you _have_ to make metrics and monitoring part of every deployed service.

## Extensibility

I have no idea what this was about. He didn't seem to say anything at all, just linked to a couple of third party products.

# Summary

Overall it was a pretty good day, and achieved my objective of a high level immersion into All Things Data.
