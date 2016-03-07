# specifications

## Basis

Based on whosonfirst by mapzen. Github: [https://github.com/whosonfirst](https://github.com/whosonfirst), site: [http://whosonfirst.mapzen.com/](http://whosonfirst.mapzen.com/)

## Language of Server Component
Rails or Python. Working code decides.

## API
URL patterns:
    geo4lib.com
      /api/v.x
      /search

URL params:
    q=[String]  (Potentially allow for a list)
    parse=[Boolean]
    withIn=[WoF ID]
    reverseGeocode=[coords]
    date=[???]

Some services:
    Disambiguation
    Relevancy Score
    Certainty / Confidence
    Alternative Name Search

Potentially "increase relevancy" of certain things.
    Identifiers
    Exact search strings that are used often

## Logging
    Query made
    Whether it returned results
    What results returned (identifiers) + relevancy score
    Was there a subsequant query 
    API Key
    IP of the host it comes from
    Session
    Response time of request
    
## Server
Stanford is seeing if they can provide space.
