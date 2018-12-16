# Finding local events using Twitter data

## Introduction
Twitter is a social media platform that millions of users use to share
updates abouot their lives. Often, these tweets are about local events
happening around the user. Though new agencies report on local events,
the time it takes an agency to learn about, investigate, and report
on the event can be substantial, especially when compared to the
length of the event. In contrast, users' interpretations of a possible
event are uploaded onto Twitter in real-time and a follower on their
Twitter feed can learn about an event before a news outlet could
broadcast the information.

In this project, we analyze tweets from a given geographical region to
determine if an event has occurred. We then report the most
descriptive tweet associated with the event. Solving this problem
would be a quick way to alert an user about an incident that may be
occuring in the area. Our approach splits data into location buckets,
identifies spikes in tweet activity, and then clusters tweets based on
similiarity.

## Project Overview
- Goal: Identify a local event given geotagged Twitter data
- Application: If done in real time, users can be notified of local
  events before news outlets can report them. Exact application varies
  on the type of event identified. For example, if a traffic delay is
  detected, a user can avoid the delay by taking an alternative route.
  Our system would be able to provide information to news stations so
  they can investigate further.

### Outline of approach
1. Obtain and preprocess tweets for a particular area
2. Divide tweets into location buckets
3. Detect an anomaly
4. Define a significant event
5. Select a headline accordingly

## Installation Instructions
0. git clone https://github.com/davidzchen-ut/TwitterEvents.git
1. pip install virtualenv
2. virtualenv ENV
3. source ENV/bin/activate (linux) or source ENV/scripts/activate(.bat)
   (windows)
4. pip install -r requirements.txt
5. jupyter notebook

For more information on this project, please visit our [medium post](https://medium.com/@shruthi.krish/finding-local-events-using-twitter-data-18298f03ead6).
