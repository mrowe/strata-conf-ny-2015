# Keynotes

The keynotes today were much more interesting and thought provoking, but still pretty light due to only being 10-15 minutes long. One of the more notable ones, "In praise of boredom" by Maria Konnikova, emphasised how we typically don't allow ourselves the time to just reflect and think (always checking email, twitter, etc.), which costs a lot in terms of our sanity over time, but also our ability to creatively solve deep problems (anyone who quotes Bertrand Russell at a tech conference is alright with me).

# Big data at Netflix

Lots of interesting stuff about their tech stack and platform... including the fact that they have one. Is a centralised data platform a good idea? Would it work for us?

Anyway, the foundation for Netflix is using S3 as their "data warehouse". I.e. everything goes into S3, and then Hadoop, spark, etc. can access it directly there. They also use Cassandra extensively as their analytics data store.

I also tried to listen to their next talk, on "Integrating Spark at petabyte scale", but there was literally no space even to stand. I will have to hunt down the slides later.

# Democratisation vs governance?

His point was mostly that it's not either/or. You can democratise data (i.e. make it available to everyone in your organisation) without giving up on governance, it just requires a bit of thought and application of appropriate tools (e.g. attribute-based access control).

# Ask Me Anything - developing a modern data strategy

This was a bit of a mixed bag, but I really liked John Akred (the CTO at Silicon Valley Data Science) from day one, so thought it might be interesting. I guess the headline would be: when developing a data strategy, think about what business needle you are trying to move. And don't gold plate it, you should only spend a month or two developing the strategy... everything is going to change anyway.

# Science fiction to product: Data-driven development

I thought I'd head into product-land for the Final session. Micha's main point was that the "science" in data science is just that: you are doing research, and you have to treat it that way. Don't expect to know the answers, or even necessarily if you've found the "right" answers. Be focused on asking the right question, i.e. the one that actually leads to value for your customers.

# Booths

I spent a bit more time wandering around the expo hall and chatting to a few folks. Again, it was mostly vendors wanting to sell proprietary solutions (including some we already use like Splunk, Tableau, etc.) and I'm not sure we want to go down that path in general. Slightly more interesting were a couple of consultancies. [Silicon Valley Data Science][] and [Caserta][] both seem to have really sharp people, but alas, no presence outside North America (yet).

[Silicon Valley Data Science]:http://www.svds.com
[Caserta]:http://casertaconcepts.com
