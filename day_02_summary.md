# Keynote

Actually a series of 5-10 minute "lightning keynotes", most of which were either product sales pitches or "look at this cool thing I did" without much substance. I guess I have been spoilt by YOW keynotes like the [classic][] by Richard Gabriel and Guy Steele.

[classic]: https://vimeo.com/25958308

Today I also learned, the hard way, that you have to be early for popular sessions or you won't get in. So the morning was a bit of a write-off, between fluffy keynotes and a couple of ordinary sessions that weren't my first choice.

Things picked up a bit in the afternoon...

# How a global entertainment company successfully built a data lake for continued digital dominance

Don't let the silly title put you off. The guys from Caserta (a boutique data science consultancy) seemed really sharp, and said lots of sensible things. In particular, they emphasised treating data as the important, persistent part of your architecture (e.g. just put everything in S3) and the compute/processing resources should be ephemeral ("never ssh into servers") and expenable.

The key ideas of a "data lake":

 * scalable storage (e.g. S3)
 * plugable processing (e.g. EMR)
 * remove barriers from ingestion and analysis
 * governance can be tweaked as you go

They also spoke about a "data pyramid" as a way of understanding the prerequisites for doing useful things with "big data":

    landing area -> data lake -> analysis workspace -> big data warehouse

(just imagine that's a pyramid, with the things to the left being the foundation.)

# Data Science in the Wall Street Journal

Juan Huerta, the Head of Data Science at Dow Jones, spoke mostly about the interesting analysis of consumer behaviour they've been doing and how it has led to better targetting of products. He didn't go into a lot of technical details, other than saying they process "millions of events per second, and update the model in milliseconds". Their data science team is about 20 people (and growing), and split more or less down the middle between "scientists" (i.e. analysis/modelling) and engineering.

# Data liberation and data integration with Kafka

Another great speaker. Martin has published a couple of widely read blog posts (on event sourcing/stream processing and more recently "Kafka, Samza, and the Unix philosophy of distributed data"). This talk was specifically about Kafka and how to use it as an integration platform/backbone. He wants people to consider abandoning JSON as the default serialisation format for something like AVRO, which is more compact and has the advantage of built in, versioned schema.

He also presented a "data needs" hierarchy (a la Maslow), in a similar vein to Caserta's pyramid:

             -> vision/mission
          -> products
       -> data science (analysis/munging)
    -> data infrastructure
    data access

(Does that look any more like a pyramid than my last effort?)

# Combining open source software and cloud-native data processing services on Google Cloud Platform

Basically a sales pitch for Google Cloud. (Which is fair enough--it was advertised as a "sponsored talk".) But I thought it would be worth the overview of what not-Amazon is doing. It seems very similar to S3/EC2/EMR, with the notable difference that they bill _by the minute_ not hour, so it can be very cheap to spin stuff up for a short time.

Their web console also has a neat feature where you can see the JSON payload of an API request for any operation, so it's easy to click around to work out how to do stuff then copy/paste into a script to automate it.


# Booths

I also spent a bit of time wandering around the expo hall. There are a LOT of vendors wanting to solve All Your Problems in big data. All the t-shirts were pretty dorky.
